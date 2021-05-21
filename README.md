# Vulnerability

<p align="center"><img border="0" src="images/logo.jpeg" width="200" height="200"></p>
<p align="center"><b><font face="微软雅黑"><a target="_blank" href="https://forum.ywhack.com/">纪念我们始终热爱的</a></font></b></p>
<p align="center"><font size="2" face="微软雅黑">来人皆是朋友 去人也不留</font></p>
<p align="center"><font size="2" face="微软雅黑">© Edge Security Team</font></p>

> 本项目多数漏洞为互联网收集(多数均注明了原作者链接🔗,如有侵权请联系我们删除,谢谢),部分漏洞进行了复现。
>
> 如有引用**请注明文章内原作者链接**，谢谢！！！ 
>
> 免责申明：项目所发布的资料\FOFA搜索语法\POC\EXP仅用于安全研究！

### 20210522 更新：

* 阿里巴巴otter manager分布式数据库同步系统信息泄漏-默认口令（CNVD-2021-16592）
* 爱快(iKuai) 后台任意文件读取(0day)
* 安天高级可持续威胁安全检测系统 越权访问漏洞
* 碧海威科技 L7 多款产品 后台命令执行
* 帆软 V9未授权RCE漏洞
* 帆软报表 v8.0 任意文件读取漏洞 CNVD-2018-04757
* 泛微 OA 前台 GetShell 复现
* 泛微e-cology任意文件上传
* 泛微OA E-cology WorkflowServiceXml 远程代码执行漏洞
* 飞鱼星 家用智能路由 cookie.cgi 权限绕过
* 孚盟云 CRM系统多个高危漏洞
* 海康威视 流媒体管理服务器任意文件读取-通用弱口令 CNVD-2021-14544
* 和信创天云桌面系统命令执行，文件上传 全版本 RCE
* 宏电 H8922 路由器中多个漏洞（CVE-2021-28149~52）
* 华硕-GT-AC2900-身份验证绕过（CVE-2021-32030）
* 会捷通云视讯 敏感信息泄漏
* 金和OA C6 后台越权敏感文件遍历漏洞
* 金山 V8 终端安全系统 任意文件读取漏洞
* 金山 V8 终端安全系统 pdf_maker.php 未授权 RCE
* 金山终端安全系统 V8-V9存在文件上传漏洞
* 蓝海卓越计费管理系统 任意文件读取漏洞
* 蓝凌OA 前台 SSRF 到 RCE
* 蓝凌OA custom.jsp 任意文件读取漏洞
* 蓝凌OA EKP 后台SQL注入漏洞 CNVD-2021-01363
* 默安幻阵蜜罐安装平台未授权访问
* 齐治堡垒机任意用户登陆
* 奇安信天擎 越权访问
* 奇安信NS-NGFW 网康下一代防火墙 前台RCE
* 锐捷 EG 易网关RCE 0day
* 锐捷Smartweb管理系统 密码信息泄露 CNVD-2021-17369
* 狮子鱼社区团购系统 wxapp.php 文件上传漏洞
* 思福迪堡垒机(Logbase)任意用户登录-默认口令
* 腾达路由器 AC11 堆栈缓冲区溢出（CVE-2021-31758）
* 腾达路由器 D151-D31未经身份验证的配置下载
* 天清汉马USG防火墙 逻辑缺陷漏洞 CNVD-2021-12793
* 网康 NS-ASG安全网关 任意文件读取漏洞
* 微信客户端远程命令执行漏洞
* 亿邮邮件系统远程命令执行漏洞 (CNVD-2021-26422)
* 银澎云计算 好视通视频会议系统 任意文件下载
* 用友 NCCloud FS文件管理SQL注入
* 用友 U8 OA test.jsp SQL注入漏洞
* 用友NC 6.5 反序列化命令执行
* 佑友防火墙 后台RCE-默认口令
* 云尚在线客服系统任意文件上传
* 致远OA A8-V5 任意文件读取
* 智慧校园管理系统 前台任意文件上传
* Adobe ColdFusion 远程代码执行漏洞（CVE-2021-21087）
* Afterlogic Aurora & WebMail Pro 任意文件读取（CVE-2021-26294）
* Afterlogic Aurora & WebMail Pro 文件上传漏洞（CVE-2021-26293）
* Apache Druid 远程代码执行漏洞（CVE-2021-25646）
* Apache Druid 远程代码执行漏洞（CVE-2021-26919）
* Apache OFBiz 反序列化（CVE-2021-30128）
* Apache OFBiz RMI Bypass RCE（CVE-2021-29200）
* Apache OFBiz RMI反序列化任意代码执行（CVE-2021-26295）
* Apache Solr Replication handler SSRF（CVE-2021-27905）
* Apache Solr stream.url任意文件读取漏洞
* Apache Solr<= 8.8.2 (最新) 任意文件删除
* BIG-IP- BIG-IQ iControl REST 未经身份验证的RCE (CVE-2021-22986)
* C-Lodop打印机任意文件读取漏洞
* Cacti SQL 注入漏洞（CVE-2020-14295）
* Chrome 远程代码执行漏洞 1Day（CVE-2021-21220）
* Cisco HyperFlex HX 命令注入（CVE-2021-1497-CVE-2021-1498）
* Cisco HyperFlex HX 任意文件上传（CVE-2021-1499）
* Coremail论客邮件系统路径遍历与文件上传漏洞
* D-Link DCS系列监控 账号密码信息泄露 CVE-2020-25078
* D-LINK DIR-802 命令注入漏洞（CVE-2021-29379）
* D-Link DIR-846路由器 命令注入 (CVE-2020-27600)
* DD-WRT 缓冲区溢出漏洞（CVE-2021-27137）
* Dell BIOS驱动权限提升漏洞（CVE-2021-21551）
* Discuz 3.4 最新版后台getshell
* Eclipse Jetty 拒绝服务 (CVE-2020-27223)
* Emlog v5.3.1 - v6.0.0 后台 RCE（CVE-2021-31737）
* Emlog v6.0.0 ZIP插件GETSHELL（CVE-2020-21585）
* ERPNext 13.0.0-12.18.0 中的多个XSS漏洞
* ERPNext 13.0.0-12.18.0 中的SQL注入漏洞
* ExifTool 任意代码执行漏洞 (CVE-2021-22204)
* FastAdmin 框架远程代码执行漏洞
* Gitlab Kramdown RCE（CVE-2021-22192）
* Gitlab SSRF-信息泄漏漏洞 (CVE-2021-22178-CVE-2021-22176)
* Gogs Git Hooks 远程代码执行漏洞（CVE-2020-15867）
* GravCMS未经身份验证的任意YAML写入-RCE（CVE-2021-21425）
* H3C-SecPath-运维审计系统(堡垒机)任意用户登录
* HTTP协议栈远程代码执行漏洞（CVE-2021-31166）
* IE 脚本引擎 jscript9.dll 内存损坏漏洞（CVE-2021-26419）
* Ivanti Avalanche 目录遍历漏洞
* JD-FreeFuck 后台命令执行漏洞
* JEEWMS 未授权任意文件读取漏洞
* Jellyfin 任意文件读取（CVE-2021-21402）
* jinja服务端模板注入漏洞
* KEADCOM 数字系统接入网关任意文件读取漏洞
* Kubernetes 准入机制绕过（CVE-2021-25735）
* Mark Text Markdown 编辑器RCE（CVE-2021-29996）
* MediaWiki <1.3.1.2 跨站脚本攻击(XSS)（CVE-2021-30157）
* MessageSolution 企业邮件归档管理系统任意文件上传（CNVD-2021-10543）
* MessageSolution 企业邮件归档管理系统信息泄露漏洞 CNVD-2021-10543
* Microsoft Exchange Server远程执行代码漏洞（CVE-2021-28482）
* MyBB sql注入导致的远程代码执行 (CVE-2021-27890)
* Nagios Network Analyzer SQL 注入漏洞（CVE-2021-28925）
* NETGEAR R7000 缓冲区溢出漏洞（CVE-2021-31802）
* Nokia G-120W-F 路由器存储型XSS（CVE-2021-30003）
* OneBlog开源博客管理系统 远程命令执行
* OpenSSL 拒绝服务漏洞（CVE-2021-3449）
* Panabit 智能应用网关 后台命令执行漏洞
* PEGA pega infinity 授权认证绕过RCE（CVE-2021-27651）
* PHP Composer命令注入漏洞（CVE-2021-29472）
* QNAP QTS Surveillance Station插件远程代码执行漏洞（CVE-2021-28797）
* rConfig 3.9.6 远程 Shell Upload
* RDoc 命令注入（CVE-2021-31799）
* Ruby目录遍历漏洞（CVE-2021-28966）
* SaltStack命令注入漏洞（CVE-2021-31607）
* ShopXO 任意文件读取漏洞（CNVD-2021-15822）
* Steam远程代码执行漏洞（CVE-2021-30481）
* TG8 防火墙中的 RCE 和密码泄漏
* Thymeleaf 3.0.12 RCE Bypass
* TP-link 栈溢出漏洞（CVE-2021-29302）
* TP-Link WR2041 v1拒绝服务漏洞（CVE-2021-26827）
* TVT数码科技 NVMS-1000 路径遍历漏洞
* Ubuntu OverlayFS 权限提升漏洞（CVE-2021-3493）
* VMware vRealize Operations Manager API SSRF漏洞 (CVE-2021-21975)
* VMware Workspace ONE Access 命令注入漏洞（CVE-2020-4006）
* VoIPmonitor UnAuth RCE（CVE-2021-30461）
* Wazuh Manager 代码执行漏洞（CVE-2021-26814）
* Webmin 多个高危漏洞（CVE-2021-31760~62）
* Windows TCP-IP拒绝服务漏洞 (CVE-2021-24086)
* Windows容器管理器服务提升权限漏洞（CVE-2021-31169）
* WordPress 5.6-5.7-经过身份验证的XXE（CVE-2021-29447）
* WordPress Elementor Page Builder Plus插件身份验证绕过（CVE-2021-24175）
* WordPress GiveWP 2.9.7 反射型XSS（CVE-2021-24213）
* WordPress WP Super Cache 插件 < 1.7.2 RCE（CVE-2021-24209）
* WordPress插件Tutor LMS SQL注入漏洞（CVE-2021-24186）
* Xmind 2020 XSS漏洞导致命令执行
* zzzcms 远程代码执行漏洞（CVE-2021-32605）

-------

* [Gitlab 敏感信息泄露漏洞 (CVE-2021-22188)](https://github.com/EdgeSecurityTeam/Vulnerability/blob/main/Gitlab%20%E6%95%8F%E6%84%9F%E4%BF%A1%E6%81%AF%E6%B3%84%E9%9C%B2%E6%BC%8F%E6%B4%9E%20(CVE-2021-22188).md)
* [朗视TG400 GSM 网关目录遍历 (CVE-2021-27328)](https://github.com/EdgeSecurityTeam/Vulnerability/blob/main/%E6%9C%97%E8%A7%86TG400%20GSM%20%E7%BD%91%E5%85%B3%E7%9B%AE%E5%BD%95%E9%81%8D%E5%8E%86%20(CVE-2021-27328).md)
* [浪潮 ClusterEngineV4.0 集群管理系统 命令执行漏洞 (CVE-2020-21224)](https://github.com/EdgeSecurityTeam/Vulnerability/blob/main/%E6%B5%AA%E6%BD%AE%20ClusterEngineV4.0%20%E9%9B%86%E7%BE%A4%E7%AE%A1%E7%90%86%E7%B3%BB%E7%BB%9F%20%E5%91%BD%E4%BB%A4%E6%89%A7%E8%A1%8C%E6%BC%8F%E6%B4%9E%20(CVE-2020-21224).md)
* [日产聆风电动汽车(Leaf EV) 2018款本地拒绝服务漏洞](https://github.com/EdgeSecurityTeam/Vulnerability/blob/main/%E6%97%A5%E4%BA%A7%E8%81%86%E9%A3%8E%E7%94%B5%E5%8A%A8%E6%B1%BD%E8%BD%A6(Leaf%20EV)%202018%E6%AC%BE%E6%9C%AC%E5%9C%B0%E6%8B%92%E7%BB%9D%E6%9C%8D%E5%8A%A1%E6%BC%8F%E6%B4%9E.md)
* [锐捷RG-UAC 账户硬编码漏洞](https://github.com/EdgeSecurityTeam/Vulnerability/blob/main/%E9%94%90%E6%8D%B7RG-UAC%20%E8%B4%A6%E6%88%B7%E7%A1%AC%E7%BC%96%E7%A0%81%E6%BC%8F%E6%B4%9E.md)
* [锐捷SSL VPN 越权访问漏洞](https://github.com/EdgeSecurityTeam/Vulnerability/blob/main/%E9%94%90%E6%8D%B7SSL%20VPN%20%E8%B6%8A%E6%9D%83%E8%AE%BF%E9%97%AE%E6%BC%8F%E6%B4%9E.md)
* [通达OA11.7 任意用户登陆.md](/EdgeSecurityTeam/Vulnerability/blob/main/%E9%80%9A%E8%BE%BEOA11.7%20%E4%BB%BB%E6%84%8F%E7%94%A8%E6%88%B7%E7%99%BB%E9%99%86.md "通达OA11.7 任意用户登陆.md")
* [通达OA11.7 未授权RCE.md](/EdgeSecurityTeam/Vulnerability/blob/main/%E9%80%9A%E8%BE%BEOA11.7%20%E6%9C%AA%E6%8E%88%E6%9D%83RCE.md "通达OA11.7 未授权RCE.md")
* [通达OA11.9 低权限SQL注入漏洞.md](/EdgeSecurityTeam/Vulnerability/blob/main/%E9%80%9A%E8%BE%BEOA11.9%20%E4%BD%8E%E6%9D%83%E9%99%90SQL%E6%B3%A8%E5%85%A5%E6%BC%8F%E6%B4%9E.md "通达OA11.9 低权限SQL注入漏洞.md")
* [Apache Velocity 远程代码执行 (CVE-2020-13936).md](/EdgeSecurityTeam/Vulnerability/blob/main/Apache%20Velocity%20%E8%BF%9C%E7%A8%8B%E4%BB%A3%E7%A0%81%E6%89%A7%E8%A1%8C%20(CVE-2020-13936).md "Apache Velocity 远程代码执行 (CVE-2020-13936).md")
* [Appspace 6.2.4 SSRF (CVE-2021-27670).md](/EdgeSecurityTeam/Vulnerability/blob/main/Appspace%206.2.4%20SSRF%20(CVE-2021-27670).md "Appspace 6.2.4 SSRF (CVE-2021-27670).md")
* [BIG-IP 缓冲区溢出漏洞 (CVE-2021-22991).md](/EdgeSecurityTeam/Vulnerability/blob/main/BIG-IP%20%E7%BC%93%E5%86%B2%E5%8C%BA%E6%BA%A2%E5%87%BA%E6%BC%8F%E6%B4%9E%20(CVE-2021-22991).md "BIG-IP 缓冲区溢出漏洞 (CVE-2021-22991).md")
* [D-Link DAP-2020远程代码执行 (CVE-2021-27249-2021-27250).md](/EdgeSecurityTeam/Vulnerability/blob/main/D-Link%20DAP-2020%E8%BF%9C%E7%A8%8B%E4%BB%A3%E7%A0%81%E6%89%A7%E8%A1%8C%20(CVE-2021-27249-2021-27250).md "D-Link DAP-2020远程代码执行 (CVE-2021-27249-2021-27250).md")
* [D-LINK DIR-841 命令注入（CVE-2021-28143）.md](/EdgeSecurityTeam/Vulnerability/blob/main/D-LINK%20DIR-841%20%E5%91%BD%E4%BB%A4%E6%B3%A8%E5%85%A5%EF%BC%88CVE-2021-28143%EF%BC%89.md "D-LINK DIR-841 命令注入（CVE-2021-28143）.md")
* [Dell OpenManage Server Administrator 任意文件读取 (CVE-2021-21514).md](/EdgeSecurityTeam/Vulnerability/blob/main/Dell%20OpenManage%20Server%20Administrator%20%E4%BB%BB%E6%84%8F%E6%96%87%E4%BB%B6%E8%AF%BB%E5%8F%96%20(CVE-2021-21514).md "Dell OpenManage Server Administrator 任意文件读取 (CVE-2021-21514).md")
* [DNS Server远程代码执行漏洞(CVE-2020-1350).md](/EdgeSecurityTeam/Vulnerability/blob/main/DNS%20Server%E8%BF%9C%E7%A8%8B%E4%BB%A3%E7%A0%81%E6%89%A7%E8%A1%8C%E6%BC%8F%E6%B4%9E(CVE-2020-1350).md "DNS Server远程代码执行漏洞(CVE-2020-1350).md")
* [Eclipse Theia < 0.16.0 Javascript注入 (CVE-2021-28162).md](/EdgeSecurityTeam/Vulnerability/blob/main/Eclipse%20Theia%20%3C%200.16.0%20Javascript%E6%B3%A8%E5%85%A5%20(CVE-2021-28162).md "Eclipse Theia < 0.16.0 Javascript注入 (CVE-2021-28162).md")
* [FortiLogger-未经身份验证的任意文件上传（CVE-2021-3378）.md](/EdgeSecurityTeam/Vulnerability/blob/main/FortiLogger-%E6%9C%AA%E7%BB%8F%E8%BA%AB%E4%BB%BD%E9%AA%8C%E8%AF%81%E7%9A%84%E4%BB%BB%E6%84%8F%E6%96%87%E4%BB%B6%E4%B8%8A%E4%BC%A0%EF%BC%88CVE-2021-3378%EF%BC%89.md "FortiLogger-未经身份验证的任意文件上传（CVE-2021-3378）.md")
* [GitLab Graphql 邮件地址信息泄露 (CVE-2020-26413).md](/EdgeSecurityTeam/Vulnerability/blob/main/GitLab%20Graphql%20%E9%82%AE%E4%BB%B6%E5%9C%B0%E5%9D%80%E4%BF%A1%E6%81%AF%E6%B3%84%E9%9C%B2%20(CVE-2020-26413).md "GitLab Graphql 邮件地址信息泄露 (CVE-2020-26413).md")
* [Internet Explorer内存损坏漏洞（CVE-2021-26411）.md](/EdgeSecurityTeam/Vulnerability/blob/main/Internet%20Explorer%E5%86%85%E5%AD%98%E6%8D%9F%E5%9D%8F%E6%BC%8F%E6%B4%9E%EF%BC%88CVE-2021-26411%EF%BC%89.md "Internet Explorer内存损坏漏洞（CVE-2021-26411）.md")
* [Joomla com_media 后台 RCE (CVE-2021-23132).md](/EdgeSecurityTeam/Vulnerability/blob/main/Joomla%20com_media%20%E5%90%8E%E5%8F%B0%20RCE%20(CVE-2021-23132).md "Joomla com_media 后台 RCE (CVE-2021-23132).md")
* [LightCMS 存储型XSS（CVE-2021-3355）.md](/EdgeSecurityTeam/Vulnerability/blob/main/LightCMS%20%E5%AD%98%E5%82%A8%E5%9E%8BXSS%EF%BC%88CVE-2021-3355%EF%BC%89.md "LightCMS 存储型XSS（CVE-2021-3355）.md")
* [Maxum Rumpus 命令注入漏洞（CVE-2020-27575）.md](/EdgeSecurityTeam/Vulnerability/blob/main/Maxum%20Rumpus%20%E5%91%BD%E4%BB%A4%E6%B3%A8%E5%85%A5%E6%BC%8F%E6%B4%9E%EF%BC%88CVE-2020-27575%EF%BC%89.md "Maxum Rumpus 命令注入漏洞（CVE-2020-27575）.md")
* [Microsoft Exchange SSRF（CVE-2021-26855）.md](/EdgeSecurityTeam/Vulnerability/blob/main/Microsoft%20Exchange%20SSRF%EF%BC%88CVE-2021-26855%EF%BC%89.md "Microsoft Exchange SSRF（CVE-2021-26855）.md")
* [Microsoft Graphics Components 代码执行漏洞 (CVE-2021-24093).md](/EdgeSecurityTeam/Vulnerability/blob/main/Microsoft%20Graphics%20Components%20%E4%BB%A3%E7%A0%81%E6%89%A7%E8%A1%8C%E6%BC%8F%E6%B4%9E%20(CVE-2021-24093).md "Microsoft Graphics Components 代码执行漏洞 (CVE-2021-24093).md")
* [Microsoft Windows10 本地提权漏洞（CVE-2021-1732）.md](/EdgeSecurityTeam/Vulnerability/blob/main/Microsoft%20Windows10%20%E6%9C%AC%E5%9C%B0%E6%8F%90%E6%9D%83%E6%BC%8F%E6%B4%9E%EF%BC%88CVE-2021-1732%EF%BC%89.md "Microsoft Windows10 本地提权漏洞（CVE-2021-1732）.md")
* [Nagios 代码注入漏洞 (CVE-2021-3273).md](/EdgeSecurityTeam/Vulnerability/blob/main/Nagios%20%E4%BB%A3%E7%A0%81%E6%B3%A8%E5%85%A5%E6%BC%8F%E6%B4%9E%20(CVE-2021-3273).md "Nagios 代码注入漏洞 (CVE-2021-3273).md")
* [Netgear JGS516PE-GS116Ev2 交换机中多个高危漏洞.md](/EdgeSecurityTeam/Vulnerability/blob/main/Netgear%20JGS516PE-GS116Ev2%20%E4%BA%A4%E6%8D%A2%E6%9C%BA%E4%B8%AD%E5%A4%9A%E4%B8%AA%E9%AB%98%E5%8D%B1%E6%BC%8F%E6%B4%9E.md "Netgear JGS516PE-GS116Ev2 交换机中多个高危漏洞.md")
* [Node.js命令注入漏洞（CVE-2021-21315）.md](/EdgeSecurityTeam/Vulnerability/blob/main/Node.js%E5%91%BD%E4%BB%A4%E6%B3%A8%E5%85%A5%E6%BC%8F%E6%B4%9E%EF%BC%88CVE-2021-21315%EF%BC%89.md "Node.js命令注入漏洞（CVE-2021-21315）.md")
* [Open5GS 默认密码漏洞 (CVE-2021-25863).md](/EdgeSecurityTeam/Vulnerability/blob/main/Open5GS%20%E9%BB%98%E8%AE%A4%E5%AF%86%E7%A0%81%E6%BC%8F%E6%B4%9E%20(CVE-2021-25863).md "Open5GS 默认密码漏洞 (CVE-2021-25863).md")
* [OpenCMS 11.0.2 文件上传到命令执行.md](/EdgeSecurityTeam/Vulnerability/blob/main/OpenCMS%2011.0.2%20%E6%96%87%E4%BB%B6%E4%B8%8A%E4%BC%A0%E5%88%B0%E5%91%BD%E4%BB%A4%E6%89%A7%E8%A1%8C.md "OpenCMS 11.0.2 文件上传到命令执行.md")
* [Saltstack 未授权RCE漏洞 （CVE-2021-25281-25282-25283）.md](/EdgeSecurityTeam/Vulnerability/blob/main/Saltstack%20%E6%9C%AA%E6%8E%88%E6%9D%83RCE%E6%BC%8F%E6%B4%9E%20%EF%BC%88CVE-2021-25281-25282-25283%EF%BC%89.md "Saltstack 未授权RCE漏洞 （CVE-2021-25281-25282-25283）.md")
* [TP-Link AC1750 预认证远程代码执行漏洞（CVE-2021-27246）.md](/EdgeSecurityTeam/Vulnerability/blob/main/TP-Link%20AC1750%20%E9%A2%84%E8%AE%A4%E8%AF%81%E8%BF%9C%E7%A8%8B%E4%BB%A3%E7%A0%81%E6%89%A7%E8%A1%8C%E6%BC%8F%E6%B4%9E%EF%BC%88CVE-2021-27246%EF%BC%89.md "TP-Link AC1750 预认证远程代码执行漏洞（CVE-2021-27246）.md")
* [VMware vCenter Server 服务器端请求伪造漏洞 (CVE-2021-21973).md](/EdgeSecurityTeam/Vulnerability/blob/main/VMware%20vCenter%20Server%20%E6%9C%8D%E5%8A%A1%E5%99%A8%E7%AB%AF%E8%AF%B7%E6%B1%82%E4%BC%AA%E9%80%A0%E6%BC%8F%E6%B4%9E%20(CVE-2021-21973).md "VMware vCenter Server 服务器端请求伪造漏洞 (CVE-2021-21973).md")
* [VMware View Planner 未授权RCE (CVE-2021-21978).md](/EdgeSecurityTeam/Vulnerability/blob/main/VMware%20View%20Planner%20%E6%9C%AA%E6%8E%88%E6%9D%83RCE%20(CVE-2021-21978).md "VMware View Planner 未授权RCE (CVE-2021-21978).md")
* [WebMail Pro 7.7.9 目录遍历 (CVE-2021-26294).md](/EdgeSecurityTeam/Vulnerability/blob/main/WebMail%20Pro%207.7.9%20%E7%9B%AE%E5%BD%95%E9%81%8D%E5%8E%86%20(CVE-2021-26294).md "WebMail Pro 7.7.9 目录遍历 (CVE-2021-26294).md")
* [XStream 1.4.16 多个RCE（CVE-2021-21344~50）.md](/EdgeSecurityTeam/Vulnerability/blob/main/XStream%201.4.16%20%E5%A4%9A%E4%B8%AARCE%EF%BC%88CVE-2021-21344%7E50%EF%BC%89.md "XStream 1.4.16 多个RCE（CVE-2021-21344~50）.md")
* [VMware vCenter Server 远程执行代码漏洞 (CVE-2021-21972)](https://github.com/EdgeSecurityTeam/Vulnerability/blob/main/VMware%20vCenter%20Server%20%E8%BF%9C%E7%A8%8B%E6%89%A7%E8%A1%8C%E4%BB%A3%E7%A0%81%E6%BC%8F%E6%B4%9E%20(CVE-2021-21972).md)
* [中新金盾信息安全管理系统 默认密码漏洞](https://github.com/EdgeSecurityTeam/Vulnerability/blob/main/%E4%B8%AD%E6%96%B0%E9%87%91%E7%9B%BE%E4%BF%A1%E6%81%AF%E5%AE%89%E5%85%A8%E7%AE%A1%E7%90%86%E7%B3%BB%E7%BB%9F%20%E9%BB%98%E8%AE%A4%E5%AF%86%E7%A0%81%E6%BC%8F%E6%B4%9E.md)
* [Adminer SSRF（CVE-2021-21311）](https://github.com/EdgeSecurityTeam/Vulnerability/blob/main/Adminer%20SSRF%EF%BC%88CVE-2021-21311%EF%BC%89.md)
* [Apache Shiro < 1.7.1 权限绕过漏洞（CVE-2020-17523）](https://github.com/EdgeSecurityTeam/Vulnerability/blob/main/Apache%20Shiro%20%3C%201.7.1%20%E6%9D%83%E9%99%90%E7%BB%95%E8%BF%87%E6%BC%8F%E6%B4%9E%EF%BC%88CVE-2020-17523%EF%BC%89.md)
* [Microsoft Edge浏览器 45.9.5地址栏欺骗POC](https://github.com/EdgeSecurityTeam/Vulnerability/blob/main/Microsoft%20Edge%E6%B5%8F%E8%A7%88%E5%99%A8%2045.9.5%E5%9C%B0%E5%9D%80%E6%A0%8F%E6%AC%BA%E9%AA%97POC.md)
* [nagios-xi-5.7.5 多个漏洞（CVE-2021-25296~99）](https://github.com/EdgeSecurityTeam/Vulnerability/blob/main/nagios-xi-5.7.5%20%E5%A4%9A%E4%B8%AA%E6%BC%8F%E6%B4%9E%EF%BC%88CVE-2021-25296~99%EF%BC%89.md)
* [NPM VSCode扩展中的RCE（CVE-2021-26700）](https://github.com/EdgeSecurityTeam/Vulnerability/blob/main/NPM%20VSCode%E6%89%A9%E5%B1%95%E4%B8%AD%E7%9A%84RCE%EF%BC%88CVE-2021-26700%EF%BC%89.md)
* [Palo Alto PAN-OS 防火墙多个漏洞](https://github.com/EdgeSecurityTeam/Vulnerability/blob/main/Palo%20Alto%20PAN-OS%20%E9%98%B2%E7%81%AB%E5%A2%99%E5%A4%9A%E4%B8%AA%E6%BC%8F%E6%B4%9E.md)
* [Typora 0.9.67 XSS到RCE（CVE-2020-18737）](https://github.com/EdgeSecurityTeam/Vulnerability/blob/main/Typora%200.9.67%20XSS%E5%88%B0RCE%EF%BC%88CVE-2020-18737%EF%BC%89.md)
* [Windows Installer File Read 0day](https://github.com/EdgeSecurityTeam/Vulnerability/blob/main/Windows%20Installer%20File%20Read%200day.md)
* [CVE-2021-1791 Fairplay OOB Read POC](https://github.com/EdgeSecurityTeam/Vulnerability/blob/main/CVE-2021-1791%20Fairplay%20OOB%20Read%20POC.md)
* [D-LInk DNS320 FW v2.06B01 命令注入（CVE-2020-25506）](https://github.com/EdgeSecurityTeam/Vulnerability/blob/main/D-LInk%20DNS320%20FW%20v2.06B01%20%E5%91%BD%E4%BB%A4%E6%B3%A8%E5%85%A5%EF%BC%88CVE-2020-25506%EF%BC%89.md)
* [D-Link DSR-250 DSR-1000N 命令注入（CVE-2020-18568）](https://github.com/EdgeSecurityTeam/Vulnerability/blob/main/D-Link%20DSR-250%20DSR-1000N%20%E5%91%BD%E4%BB%A4%E6%B3%A8%E5%85%A5%EF%BC%88CVE-2020-18568%EF%BC%89.md)
* [MinIO未授权SSRF漏洞（CVE-2021-21287）](https://github.com/EdgeSecurityTeam/Vulnerability/blob/main/MinIO%E6%9C%AA%E6%8E%88%E6%9D%83SSRF%E6%BC%8F%E6%B4%9E%EF%BC%88CVE-2021-21287%EF%BC%89.md)
* [TP-Link TL-WR841N远程代码执行漏洞（CVE-2020-35576）](https://github.com/EdgeSecurityTeam/Vulnerability/blob/main/TP-Link%20TL-WR841N%E8%BF%9C%E7%A8%8B%E4%BB%A3%E7%A0%81%E6%89%A7%E8%A1%8C%E6%BC%8F%E6%B4%9E%EF%BC%88CVE-2020-35576%EF%BC%89.md)
* [Windows Install(WMI)越权漏洞（CVE-2020-0683)](https://github.com/EdgeSecurityTeam/Vulnerability/blob/main/Windows%20Install(WMI)%E8%B6%8A%E6%9D%83%E6%BC%8F%E6%B4%9E%EF%BC%88CVE-2020-0683%29.md)
* [Apache Druid 远程代码执行漏洞（CVE-2021-25646）](https://github.com/EdgeSecurityTeam/Vulnerability/blob/main/Apache%20Druid%20%E8%BF%9C%E7%A8%8B%E4%BB%A3%E7%A0%81%E6%89%A7%E8%A1%8C%E6%BC%8F%E6%B4%9E%EF%BC%88CVE-2021-25646%EF%BC%89.md)
* [Anchor CMS 0.12.7 跨站请求伪造（CVE-2020-23342）](https://github.com/EdgeSecurityTeam/Vulnerability/blob/main/Anchor%20CMS%200.12.7%20%E8%B7%A8%E7%AB%99%E8%AF%B7%E6%B1%82%E4%BC%AA%E9%80%A0%EF%BC%88CVE-2020-23342%EF%BC%89.md)
* [Apache Kylin API未授权访问漏洞（CVE-2020-13937）](https://github.com/EdgeSecurityTeam/Vulnerability/blob/main/Apache%20Kylin%20API%E6%9C%AA%E6%8E%88%E6%9D%83%E8%AE%BF%E9%97%AE%E6%BC%8F%E6%B4%9E%EF%BC%88CVE-2020-13937%EF%BC%89.md)
* [Apache NiFi Api 远程代码执行(RCE)](https://github.com/EdgeSecurityTeam/Vulnerability/blob/main/Apache%20NiFi%20Api%20%E8%BF%9C%E7%A8%8B%E4%BB%A3%E7%A0%81%E6%89%A7%E8%A1%8C(RCE).md)
* [Bypass for Microsoft Exchange远程代码执行 CVE-2020-16875](https://github.com/EdgeSecurityTeam/Vulnerability/blob/main/Bypass%20for%20Microsoft%20Exchange%E8%BF%9C%E7%A8%8B%E4%BB%A3%E7%A0%81%E6%89%A7%E8%A1%8C%20CVE-2020-16875.md)
* [CISCO ASA任意文件读取漏洞 (CVE-2020-3452)](https://github.com/EdgeSecurityTeam/Vulnerability/blob/main/CISCO%20ASA%E4%BB%BB%E6%84%8F%E6%96%87%E4%BB%B6%E8%AF%BB%E5%8F%96%E6%BC%8F%E6%B4%9E%20(CVE-2020-3452).md)
* [CNVD-2020-24741 JunAms内容管理系统文件上传漏洞](https://github.com/EdgeSecurityTeam/Vulnerability/blob/main/CNVD-2020-24741%20JunAms%E5%86%85%E5%AE%B9%E7%AE%A1%E7%90%86%E7%B3%BB%E7%BB%9F%E6%96%87%E4%BB%B6%E4%B8%8A%E4%BC%A0%E6%BC%8F%E6%B4%9E.md)
* [CNVD-C-2020-121325 禅道开源版文件上传漏洞](https://github.com/EdgeSecurityTeam/Vulnerability/blob/main/CNVD-C-2020-121325%20%E7%A6%85%E9%81%93%E5%BC%80%E6%BA%90%E7%89%88%E6%96%87%E4%BB%B6%E4%B8%8A%E4%BC%A0%E6%BC%8F%E6%B4%9E.md)
* [CVE-2019-12384 jackson ssrf-rce(附exp脚本)](https://github.com/EdgeSecurityTeam/Vulnerability/blob/main/CVE-2019-12384%20jackson%20ssrf-rce(%E9%99%84exp%E8%84%9A%E6%9C%AC).md)
* [CVE-2020-10148 SolarWinds Orion API 远程代码执行漏洞](https://github.com/EdgeSecurityTeam/Vulnerability/blob/main/CVE-2020-10148%20SolarWinds%20Orion%20API%20%E8%BF%9C%E7%A8%8B%E4%BB%A3%E7%A0%81%E6%89%A7%E8%A1%8C%E6%BC%8F%E6%B4%9E.md)
* [CVE-2020-10977 Gitlab任意文件读取导致远程命令执行](https://github.com/EdgeSecurityTeam/Vulnerability/blob/main/CVE-2020-10977%20Gitlab%E4%BB%BB%E6%84%8F%E6%96%87%E4%BB%B6%E8%AF%BB%E5%8F%96%E5%AF%BC%E8%87%B4%E8%BF%9C%E7%A8%8B%E5%91%BD%E4%BB%A4%E6%89%A7%E8%A1%8C.md)
* [CVE-2020-13935 Apache Tomcat WebSocket 拒绝服务漏洞](https://github.com/EdgeSecurityTeam/Vulnerability/blob/main/CVE-2020-13935%20Apache%20Tomcat%20WebSocket%20%E6%8B%92%E7%BB%9D%E6%9C%8D%E5%8A%A1%E6%BC%8F%E6%B4%9E.md)
* [CVE-2020-13942 Apache Unomi 远程代码执行](https://github.com/EdgeSecurityTeam/Vulnerability/blob/main/CVE-2020-13942%20Apache%20Unomi%20%E8%BF%9C%E7%A8%8B%E4%BB%A3%E7%A0%81%E6%89%A7%E8%A1%8C.md)
* [CVE-2020-14815 Oracle Business Intelligence XSS](https://github.com/EdgeSecurityTeam/Vulnerability/blob/main/CVE-2020-14815%20Oracle%20Business%20Intelligence%20XSS.md)
* [CVE-2020-16846 SaltStack远程执行代码漏洞](https://github.com/EdgeSecurityTeam/Vulnerability/blob/main/CVE-2020-16846%20SaltStack%E8%BF%9C%E7%A8%8B%E6%89%A7%E8%A1%8C%E4%BB%A3%E7%A0%81%E6%BC%8F%E6%B4%9E.md)
* [CVE-2020-16898 | Windows TCP/IP远程执行代码漏洞 Exploit](https://github.com/EdgeSecurityTeam/Vulnerability/blob/main/CVE-2020-16898%20%7C%20Windows%20TCP-IP%E8%BF%9C%E7%A8%8B%E6%89%A7%E8%A1%8C%E4%BB%A3%E7%A0%81%E6%BC%8F%E6%B4%9E%20Exploit.md)
* [CVE-2020-17083 Microsoft Exchange Server 远程执行代码漏洞](https://github.com/EdgeSecurityTeam/Vulnerability/blob/main/CVE-2020-17083%20Microsoft%20Exchange%20Server%20%E8%BF%9C%E7%A8%8B%E6%89%A7%E8%A1%8C%E4%BB%A3%E7%A0%81%E6%BC%8F%E6%B4%9E.md)
* [CVE-2020-17143 Microsoft Exchange 信息泄露漏洞 PoC](https://github.com/EdgeSecurityTeam/Vulnerability/blob/main/CVE-2020-17143%20Microsoft%20Exchange%20%E4%BF%A1%E6%81%AF%E6%B3%84%E9%9C%B2%E6%BC%8F%E6%B4%9E%20PoC.md)
* [CVE-2020-17144 Exchange2010 反序列化RCE](https://github.com/EdgeSecurityTeam/Vulnerability/blob/main/CVE-2020-17144%20Exchange2010%20%E5%8F%8D%E5%BA%8F%E5%88%97%E5%8C%96RCE.md)
* [CVE-2020-17518 Apache Flink 任意文件写入](https://github.com/EdgeSecurityTeam/Vulnerability/blob/main/CVE-2020-17518%20Apache%20Flink%20%E4%BB%BB%E6%84%8F%E6%96%87%E4%BB%B6%E5%86%99%E5%85%A5.md)
* [CVE-2020-17519 Apache Flink 任意文件读取](https://github.com/EdgeSecurityTeam/Vulnerability/blob/main/CVE-2020-17519%20Apache%20Flink%20%E4%BB%BB%E6%84%8F%E6%96%87%E4%BB%B6%E8%AF%BB%E5%8F%96.md)
* [CVE-2020-17532 Apache servicecomb-java-chassis Yaml 反序列化漏洞](https://github.com/EdgeSecurityTeam/Vulnerability/blob/main/CVE-2020-17532%20Apache%20servicecomb-java-chassis%20Yaml%20%E5%8F%8D%E5%BA%8F%E5%88%97%E5%8C%96%E6%BC%8F%E6%B4%9E.md)
* [CVE-2020-26238 Cron-Utils 远程代码执行(RCE)漏洞](https://github.com/EdgeSecurityTeam/Vulnerability/blob/main/CVE-2020-26238%20Cron-Utils%20%E8%BF%9C%E7%A8%8B%E4%BB%A3%E7%A0%81%E6%89%A7%E8%A1%8C(RCE)%E6%BC%8F%E6%B4%9E.md)
* [CVE-2020-26258 XStream SSRF](https://github.com/EdgeSecurityTeam/Vulnerability/blob/main/CVE-2020-26258%20XStream%20SSRF.md)
* [CVE-2020-26259 XStream 任意文件删除](https://github.com/EdgeSecurityTeam/Vulnerability/blob/main/CVE-2020-26259%20XStream%20%E4%BB%BB%E6%84%8F%E6%96%87%E4%BB%B6%E5%88%A0%E9%99%A4.md)
* [CVE-2020-26935 phpmyadmin后台SQL注入](https://github.com/EdgeSecurityTeam/Vulnerability/blob/main/CVE-2020-26935%20phpmyadmin%E5%90%8E%E5%8F%B0SQL%E6%B3%A8%E5%85%A5.md)
* [CVE-2020-27131 Cisco Security Manager 反序列化RCE](https://github.com/EdgeSecurityTeam/Vulnerability/blob/main/CVE-2020-27131%20Cisco%20Security%20Manager%20%E5%8F%8D%E5%BA%8F%E5%88%97%E5%8C%96RCE.md)
* [CVE-2020-27533 DedeCMS v.5.8搜索功能 "keyword"参数XSS漏洞 PoC](https://github.com/EdgeSecurityTeam/Vulnerability/blob/main/CVE-2020-27533%20DedeCMS%20v.5.8%E6%90%9C%E7%B4%A2%E5%8A%9F%E8%83%BD%20%22keyword%22%E5%8F%82%E6%95%B0XSS%E6%BC%8F%E6%B4%9E%20PoC.md)
* [CVE-2020-27986 SonarQube api 未授权访问](https://github.com/EdgeSecurityTeam/Vulnerability/blob/main/CVE-2020-27986%20SonarQube%20api%20%E6%9C%AA%E6%8E%88%E6%9D%83%E8%AE%BF%E9%97%AE.md)
* [CVE-2020-29133 Coremail 存储型XSS](https://github.com/EdgeSecurityTeam/Vulnerability/blob/main/CVE-2020-29133%20Coremail%20%E5%AD%98%E5%82%A8%E5%9E%8BXSS.md)
* [CVE-2020-29564 Consul Docker images 空密码登录漏洞](https://github.com/EdgeSecurityTeam/Vulnerability/blob/main/CVE-2020-29564%20Consul%20Docker%20images%20%E7%A9%BA%E5%AF%86%E7%A0%81%E7%99%BB%E5%BD%95%E6%BC%8F%E6%B4%9E.md)
* [CVE-2020-35476 OpenTSDB 2.4.0 远程代码执行](https://github.com/EdgeSecurityTeam/Vulnerability/blob/main/CVE-2020-35476%20OpenTSDB%202.4.0%20%E8%BF%9C%E7%A8%8B%E4%BB%A3%E7%A0%81%E6%89%A7%E8%A1%8C.md)
* [CVE-2020-36179〜82 Jackson-databind SSRF＆RCE](https://github.com/EdgeSecurityTeam/Vulnerability/blob/main/CVE-2020-36179%E3%80%9C82%20Jackson-databind%20SSRF%EF%BC%86RCE.md)
* [CVE-2020-6019 Valve Game Networking Sockets 安全漏洞](https://github.com/EdgeSecurityTeam/Vulnerability/blob/main/CVE-2020-6019%20Valve%20Game%20Networking%20Sockets%20%E5%AE%89%E5%85%A8%E6%BC%8F%E6%B4%9E.md)
* [CVE-2020-6308 SAP POC](https://github.com/EdgeSecurityTeam/Vulnerability/blob/main/CVE-2020-6308%20SAP%20POC.md)
* [CVE-2020-8209 XenMobile(Citrix Endpoint Management) 目录遍历漏洞](https://github.com/EdgeSecurityTeam/Vulnerability/blob/main/CVE-2020-8209%20XenMobile(Citrix%20Endpoint%20Management)%20%E7%9B%AE%E5%BD%95%E9%81%8D%E5%8E%86%E6%BC%8F%E6%B4%9E.md)
* [CVE-2020-8255 Pulse Connect Secure通过登录消息组件实现任意文件读取](https://github.com/EdgeSecurityTeam/Vulnerability/blob/main/CVE-2020-8255%20Pulse%20Connect%20Secure%E9%80%9A%E8%BF%87%E7%99%BB%E5%BD%95%E6%B6%88%E6%81%AF%E7%BB%84%E4%BB%B6%E5%AE%9E%E7%8E%B0%E4%BB%BB%E6%84%8F%E6%96%87%E4%BB%B6%E8%AF%BB%E5%8F%96.md)
* [CVE-2020-8277：Node.js通过DNS请求实现拒绝服务](https://github.com/EdgeSecurityTeam/Vulnerability/blob/main/CVE-2020-8277%EF%BC%9ANode.js%E9%80%9A%E8%BF%87DNS%E8%AF%B7%E6%B1%82%E5%AE%9E%E7%8E%B0%E6%8B%92%E7%BB%9D%E6%9C%8D%E5%8A%A1.md)
* [CVE-2020–14882 Weblogic 未经授权绕过RCE](https://github.com/EdgeSecurityTeam/Vulnerability/blob/main/CVE-2020%E2%80%9314882%20Weblogic%20%E6%9C%AA%E7%BB%8F%E6%8E%88%E6%9D%83%E7%BB%95%E8%BF%87RCE.md)
* [CVE-2020–24723 存储XSS的故事导致管理帐户接管](https://github.com/EdgeSecurityTeam/Vulnerability/blob/main/CVE-2020%E2%80%9324723%20%E5%AD%98%E5%82%A8XSS%E7%9A%84%E6%95%85%E4%BA%8B%E5%AF%BC%E8%87%B4%E7%AE%A1%E7%90%86%E5%B8%90%E6%88%B7%E6%8E%A5%E7%AE%A1.md)
* [CVE-2020–4280 — IBM QRadar Java反序列化分析和绕过](https://github.com/EdgeSecurityTeam/Vulnerability/blob/main/CVE-2020%E2%80%934280%20%E2%80%94%20IBM%20QRadar%20Java%E5%8F%8D%E5%BA%8F%E5%88%97%E5%8C%96%E5%88%86%E6%9E%90%E5%92%8C%E7%BB%95%E8%BF%87.md)
* [CVE-2021-3007 zend framework3 反序列化 rce](https://github.com/EdgeSecurityTeam/Vulnerability/blob/main/CVE-2021-3007%20zend%20framework3%20%E5%8F%8D%E5%BA%8F%E5%88%97%E5%8C%96%20rce.md)
* [CloudBees Jenkins和LTS 跨站脚本漏洞 CVE-2020-2229](https://github.com/EdgeSecurityTeam/Vulnerability/blob/main/CloudBees%20Jenkins%E5%92%8CLTS%20%E8%B7%A8%E7%AB%99%E8%84%9A%E6%9C%AC%E6%BC%8F%E6%B4%9E%20CVE-2020-2229.md)
* [D-link DSL-2888A 未授权访问漏洞 (CVE-2020-24579)](https://github.com/EdgeSecurityTeam/Vulnerability/blob/main/D-link%20DSL-2888A%20%E6%9C%AA%E6%8E%88%E6%9D%83%E8%AE%BF%E9%97%AE%E6%BC%8F%E6%B4%9E%20(CVE-2020-24579).md)
* [D-link DSL-2888A 远程代码执行漏洞 (CVE-2020-24581)](https://github.com/EdgeSecurityTeam/Vulnerability/blob/main/D-link%20DSL-2888A%20%E8%BF%9C%E7%A8%8B%E4%BB%A3%E7%A0%81%E6%89%A7%E8%A1%8C%E6%BC%8F%E6%B4%9E%20(CVE-2020-24581).md)
* [DNSpooq PoC - dnsmasq cache poisoning (CVE-2020-25686, CVE-2020-25684, CVE-2020-25685)](https://github.com/EdgeSecurityTeam/Vulnerability/blob/main/DNSpooq%20PoC%20-%20dnsmasq%20cache%20poisoning%20(CVE-2020-25686%2C%20CVE-2020-25684%2C%20CVE-2020-25685).md)
* [Docker 容器逃逸漏洞（CVE-2020-15257）](https://github.com/EdgeSecurityTeam/Vulnerability/blob/main/Docker%20%E5%AE%B9%E5%99%A8%E9%80%83%E9%80%B8%E6%BC%8F%E6%B4%9E%EF%BC%88CVE-2020-15257%EF%BC%89.md)
* [Git <= 2.29.2 Git-LFS-RCE-Exploit-CVE-2020-27955](https://github.com/EdgeSecurityTeam/Vulnerability/blob/main/Git%20%3C%3D%202.29.2%20Git-LFS-RCE-Exploit-CVE-2020-27955.md)
* [Git CLI远程代码执行漏洞（CVE-2020-26233）](https://github.com/EdgeSecurityTeam/Vulnerability/blob/main/Git%20CLI%E8%BF%9C%E7%A8%8B%E4%BB%A3%E7%A0%81%E6%89%A7%E8%A1%8C%E6%BC%8F%E6%B4%9E%EF%BC%88CVE-2020-26233%EF%BC%89.md)
* [Git LFS 远程代码执行漏洞 CVE-2020–27955](https://github.com/EdgeSecurityTeam/Vulnerability/blob/main/Git%20LFS%20%E8%BF%9C%E7%A8%8B%E4%BB%A3%E7%A0%81%E6%89%A7%E8%A1%8C%E6%BC%8F%E6%B4%9E%20CVE-2020%E2%80%9327955.md)
* [IBM Maximo Asset Management XXE漏洞（CVE-2020-4463）](https://github.com/EdgeSecurityTeam/Vulnerability/blob/main/IBM%20Maximo%20Asset%20Management%20XXE%E6%BC%8F%E6%B4%9E%EF%BC%88CVE-2020-4463%EF%BC%89.md)
* [Infinite WP管理面板中的身份验证绕过和RCE（CVE-2020-28642）](https://github.com/EdgeSecurityTeam/Vulnerability/blob/main/Infinite%20WP%E7%AE%A1%E7%90%86%E9%9D%A2%E6%9D%BF%E4%B8%AD%E7%9A%84%E8%BA%AB%E4%BB%BD%E9%AA%8C%E8%AF%81%E7%BB%95%E8%BF%87%E5%92%8CRCE%EF%BC%88CVE-2020-28642%EF%BC%89.md)
* [Jackson-databind RCE（CVE-2020-35728）](https://github.com/EdgeSecurityTeam/Vulnerability/blob/main/Jackson-databind%20RCE%EF%BC%88CVE-2020-35728%EF%BC%89.md)
* [Joomla CMS 框架 ACL 安全访问控制漏洞（CVE-2020-35616）](https://github.com/EdgeSecurityTeam/Vulnerability/blob/main/Joomla%20CMS%20%E6%A1%86%E6%9E%B6%20ACL%20%E5%AE%89%E5%85%A8%E8%AE%BF%E9%97%AE%E6%8E%A7%E5%88%B6%E6%BC%8F%E6%B4%9E%EF%BC%88CVE-2020-35616%EF%BC%89.md)
* [JumpServer远程执行漏洞](https://github.com/EdgeSecurityTeam/Vulnerability/blob/main/JumpServer%E8%BF%9C%E7%A8%8B%E6%89%A7%E8%A1%8C%E6%BC%8F%E6%B4%9E.md)
* [Laravel <= V8.4.2 Debug模式远程代码执行漏洞（CVE-2021-3129）](https://github.com/EdgeSecurityTeam/Vulnerability/blob/main/Laravel%20%3C%3D%20V8.4.2%20Debug%E6%A8%A1%E5%BC%8F%E8%BF%9C%E7%A8%8B%E4%BB%A3%E7%A0%81%E6%89%A7%E8%A1%8C%E6%BC%8F%E6%B4%9E%EF%BC%88CVE-2021-3129%EF%BC%89.md)
* [Microsoft Windows 10 蓝屏死机漏洞](https://github.com/EdgeSecurityTeam/Vulnerability/blob/main/Microsoft%20Windows%2010%20%E8%93%9D%E5%B1%8F%E6%AD%BB%E6%9C%BA%E6%BC%8F%E6%B4%9E.md)
* [Microsoft Windows NTFS磁盘损坏漏洞](https://github.com/EdgeSecurityTeam/Vulnerability/blob/main/Microsoft%20Windows%20NTFS%E7%A3%81%E7%9B%98%E6%8D%9F%E5%9D%8F%E6%BC%8F%E6%B4%9E.md)
* [Nacos Bypass身份验证](https://github.com/EdgeSecurityTeam/Vulnerability/blob/main/Nacos%20Bypass%E8%BA%AB%E4%BB%BD%E9%AA%8C%E8%AF%81.md)
* [Nagios XI 5.7.X 远程代码执行](https://github.com/EdgeSecurityTeam/Vulnerability/blob/main/Nagios%20XI%205.7.X%20%E8%BF%9C%E7%A8%8B%E4%BB%A3%E7%A0%81%E6%89%A7%E8%A1%8C.md)
* [Nexus Repository Manager 3 XML外部实体注入(CVE-2020-29436)](https://github.com/EdgeSecurityTeam/Vulnerability/blob/main/Nexus%20Repository%20Manager%203%20XML%E5%A4%96%E9%83%A8%E5%AE%9E%E4%BD%93%E6%B3%A8%E5%85%A5(CVE-2020-29436).md)
* [PHP图像处理组件：Intervention/image 目录遍历漏洞](https://github.com/EdgeSecurityTeam/Vulnerability/blob/main/PHP%E5%9B%BE%E5%83%8F%E5%A4%84%E7%90%86%E7%BB%84%E4%BB%B6%EF%BC%9AIntervention-image%20%E7%9B%AE%E5%BD%95%E9%81%8D%E5%8E%86%E6%BC%8F%E6%B4%9E.md)
* [Packer-Fuzzer 漏扫工具 < 1.2 远程代码执行漏洞](https://github.com/EdgeSecurityTeam/Vulnerability/blob/main/Packer-Fuzzer%20%E6%BC%8F%E6%89%AB%E5%B7%A5%E5%85%B7%20%3C%201.2%20%E8%BF%9C%E7%A8%8B%E4%BB%A3%E7%A0%81%E6%89%A7%E8%A1%8C%E6%BC%8F%E6%B4%9E.md)
* [Pydio 网盘系统 RCE （CVE-2020-28913）](https://github.com/EdgeSecurityTeam/Vulnerability/blob/main/Pydio%20%E7%BD%91%E7%9B%98%E7%B3%BB%E7%BB%9F%20RCE%20%EF%BC%88CVE-2020-28913%EF%BC%89.md)
* [SAP_EEM_CVE-2020-6207 PoC](https://github.com/EdgeSecurityTeam/Vulnerability/blob/main/SAP_EEM_CVE-2020-6207%20PoC.md)
* [SeaCMS SQL注入漏洞（CVE-2020-21378）](https://github.com/EdgeSecurityTeam/Vulnerability/blob/main/SeaCMS%20SQL%E6%B3%A8%E5%85%A5%E6%BC%8F%E6%B4%9E%EF%BC%88CVE-2020-21378%EF%BC%89.md)
* [ShowDoc 前台文件上传漏洞](https://github.com/EdgeSecurityTeam/Vulnerability/blob/main/ShowDoc%20%E5%89%8D%E5%8F%B0%E6%96%87%E4%BB%B6%E4%B8%8A%E4%BC%A0%E6%BC%8F%E6%B4%9E.md)
* [SonicWall SSL-VPN 未授权RCE漏洞](https://github.com/EdgeSecurityTeam/Vulnerability/blob/main/SonicWall%20SSL-VPN%20%E6%9C%AA%E6%8E%88%E6%9D%83RCE%E6%BC%8F%E6%B4%9E.md)
* [Struts2 s2-061 Poc (CVE-2020-17530)](https://github.com/EdgeSecurityTeam/Vulnerability/blob/main/Struts2%20s2-061%20Poc%20(CVE-2020-17530).md)
* [TerraMaster TOS 未授权 RCE (CVE-2020-28188)](https://github.com/EdgeSecurityTeam/Vulnerability/blob/main/TerraMaster%20TOS%20%E6%9C%AA%E6%8E%88%E6%9D%83%20RCE%20(CVE-2020-28188).md)
* [UCMS文件上传漏洞(CVE-2020-25483)](https://github.com/EdgeSecurityTeam/Vulnerability/blob/main/UCMS%E6%96%87%E4%BB%B6%E4%B8%8A%E4%BC%A0%E6%BC%8F%E6%B4%9E(CVE-2020-25483).md)
* [VMware vCenter 未经身份验证任意文件读取漏洞 < 6.5u1](https://github.com/EdgeSecurityTeam/Vulnerability/blob/main/VMware%20vCenter%20%E6%9C%AA%E7%BB%8F%E8%BA%AB%E4%BB%BD%E9%AA%8C%E8%AF%81%E4%BB%BB%E6%84%8F%E6%96%87%E4%BB%B6%E8%AF%BB%E5%8F%96%E6%BC%8F%E6%B4%9E%20%3C%206.5u1.md)
* [Weblogic Server远程代码执行漏洞 (CVE-2021-2109)](https://github.com/EdgeSecurityTeam/Vulnerability/blob/main/Weblogic%20Server%E8%BF%9C%E7%A8%8B%E4%BB%A3%E7%A0%81%E6%89%A7%E8%A1%8C%E6%BC%8F%E6%B4%9E%20(CVE-2021-2109).md)
* [Webmin <=1.962 任意命令执行（CVE-2020-35606）](https://github.com/EdgeSecurityTeam/Vulnerability/blob/main/Webmin%20%3C%3D1.962%20%E4%BB%BB%E6%84%8F%E5%91%BD%E4%BB%A4%E6%89%A7%E8%A1%8C%EF%BC%88CVE-2020-35606%EF%BC%89.md)
* [WordPress File Manager ＜ 6.9 RCE（CVE-2020-25213）PoC](https://github.com/EdgeSecurityTeam/Vulnerability/blob/main/WordPress%20File%20Manager%20%EF%BC%9C%206.9%20RCE%EF%BC%88CVE-2020-25213%EF%BC%89PoC.md)
* [Zoho 任意文件上传漏洞(CVE-2020-8394)](https://github.com/EdgeSecurityTeam/Vulnerability/blob/main/Zoho%20%E4%BB%BB%E6%84%8F%E6%96%87%E4%BB%B6%E4%B8%8A%E4%BC%A0%E6%BC%8F%E6%B4%9E(CVE-2020-8394).md)
* [Zyxel NBG2105 身份验证绕过（CVE-2021-3297）](https://github.com/EdgeSecurityTeam/Vulnerability/blob/main/Zyxel%20NBG2105%20%E8%BA%AB%E4%BB%BD%E9%AA%8C%E8%AF%81%E7%BB%95%E8%BF%87%EF%BC%88CVE-2021-3297%EF%BC%89.md)
* [Zyxel USG Series 账户硬编码漏洞（CVE-2020-29583）](https://github.com/EdgeSecurityTeam/Vulnerability/blob/main/Zyxel%20USG%20Series%20%E8%B4%A6%E6%88%B7%E7%A1%AC%E7%BC%96%E7%A0%81%E6%BC%8F%E6%B4%9E%EF%BC%88CVE-2020-29583%EF%BC%89.md)
* [arpping 2.0.0 远程代码执行（RCE）](https://github.com/EdgeSecurityTeam/Vulnerability/blob/main/arpping%202.0.0%20%E8%BF%9C%E7%A8%8B%E4%BB%A3%E7%A0%81%E6%89%A7%E8%A1%8C%EF%BC%88RCE%EF%BC%89.md)
* [cve-2020-14882-weblogic越权绕过登录RCE批量检测](https://github.com/EdgeSecurityTeam/Vulnerability/blob/main/cve-2020-14882-weblogic%E8%B6%8A%E6%9D%83%E7%BB%95%E8%BF%87%E7%99%BB%E5%BD%95RCE%E6%89%B9%E9%87%8F%E6%A3%80%E6%B5%8B.md)
* [jQuery >=1.0.3 <3.5.0 XSS (CVE-2020-11022/CVE-2020-11023)](https://github.com/EdgeSecurityTeam/Vulnerability/blob/main/jQuery%20%3E%3D1.0.3%20%3C3.5.0%20XSS%20(CVE-2020-11022-CVE-2020-11023).md)
* [lanproxy 目录遍历漏洞（CVE-2020-3019）](https://github.com/EdgeSecurityTeam/Vulnerability/blob/main/lanproxy%20%E7%9B%AE%E5%BD%95%E9%81%8D%E5%8E%86%E6%BC%8F%E6%B4%9E%EF%BC%88CVE-2020-3019%EF%BC%89.md)
* [xxl-job 执行器 RESTful API 未授权访问 RCE](https://github.com/EdgeSecurityTeam/Vulnerability/blob/main/xxl-job%20%E6%89%A7%E8%A1%8C%E5%99%A8%20RESTful%20API%20%E6%9C%AA%E6%8E%88%E6%9D%83%E8%AE%BF%E9%97%AE%20RCE.md)
* [yycms首页搜索框 XSS漏洞](https://github.com/EdgeSecurityTeam/Vulnerability/blob/main/yycms%E9%A6%96%E9%A1%B5%E6%90%9C%E7%B4%A2%E6%A1%86%20XSS%E6%BC%8F%E6%B4%9E.md)
* [三星路由器WLAN AP WEA453e 未授权RCE等多个漏洞](https://github.com/EdgeSecurityTeam/Vulnerability/blob/main/%E4%B8%89%E6%98%9F%E8%B7%AF%E7%94%B1%E5%99%A8WLAN%20AP%20WEA453e%20%E6%9C%AA%E6%8E%88%E6%9D%83RCE%E7%AD%89%E5%A4%9A%E4%B8%AA%E6%BC%8F%E6%B4%9E.md)
* [员工管理系统(Employee Management System)1.0 身份验证绕过](https://github.com/EdgeSecurityTeam/Vulnerability/blob/main/%E5%91%98%E5%B7%A5%E7%AE%A1%E7%90%86%E7%B3%BB%E7%BB%9F(Employee%20Management%20System)1.0%20%E8%BA%AB%E4%BB%BD%E9%AA%8C%E8%AF%81%E7%BB%95%E8%BF%87.md)
* [用友nc 6.5 文件上传 PoC](https://github.com/EdgeSecurityTeam/Vulnerability/blob/main/%E7%94%A8%E5%8F%8Bnc%206.5%20%E6%96%87%E4%BB%B6%E4%B8%8A%E4%BC%A0%20PoC.md)
* [锐捷-EWEB网管系统RCE](https://github.com/EdgeSecurityTeam/Vulnerability/blob/main/%E9%94%90%E6%8D%B7-EWEB%E7%BD%91%E7%AE%A1%E7%B3%BB%E7%BB%9FRCE.md)
* [Apache OfBiz 服务器端模板注入（SSTI）](https://github.com/EdgeSecurityTeam/Vulnerability/blob/main/Apache%20OfBiz%20%E6%9C%8D%E5%8A%A1%E5%99%A8%E7%AB%AF%E6%A8%A1%E6%9D%BF%E6%B3%A8%E5%85%A5%EF%BC%88SSTI%EF%BC%89.md)
* [Apache OfBiz 远程代码执行（RCE）](https://github.com/EdgeSecurityTeam/Vulnerability/blob/main/Apache%20OfBiz%20%E8%BF%9C%E7%A8%8B%E4%BB%A3%E7%A0%81%E6%89%A7%E8%A1%8C%EF%BC%88RCE%EF%BC%89.md)
* [Fuel CMS 1.4.1 远程代码执行](https://github.com/EdgeSecurityTeam/Vulnerability/blob/main/Fuel%20CMS%201.4.1%20%E8%BF%9C%E7%A8%8B%E4%BB%A3%E7%A0%81%E6%89%A7%E8%A1%8C.md)
* [OneDev 多个高危漏洞 （CVE-2021-21242~51）](https://github.com/EdgeSecurityTeam/Vulnerability/blob/main/OneDev%20%E5%A4%9A%E4%B8%AA%E9%AB%98%E5%8D%B1%E6%BC%8F%E6%B4%9E%20%EF%BC%88CVE-2021-21242~51%EF%BC%89.md)
* [Weblogic Server远程代码执行漏洞（CVE-2020-14756）](https://github.com/EdgeSecurityTeam/Vulnerability/blob/main/Weblogic%20Server%E8%BF%9C%E7%A8%8B%E4%BB%A3%E7%A0%81%E6%89%A7%E8%A1%8C%E6%BC%8F%E6%B4%9E%EF%BC%88CVE-2020-14756%EF%BC%89.md)
* [WordPress 插件SuperForms 4.9-任意文件上传到远程代码执行](https://github.com/EdgeSecurityTeam/Vulnerability/blob/main/WordPress%20%E6%8F%92%E4%BB%B6SuperForms%204.9-%E4%BB%BB%E6%84%8F%E6%96%87%E4%BB%B6%E4%B8%8A%E4%BC%A0%E5%88%B0%E8%BF%9C%E7%A8%8B%E4%BB%A3%E7%A0%81%E6%89%A7%E8%A1%8C.md)
* [YouPHPTube <= 10.0 and 7.8 多个漏洞 SQL注入、XSS、文件写入](https://github.com/EdgeSecurityTeam/Vulnerability/blob/main/YouPHPTube%20%3C%3D%2010.0%20and%207.8%20%E5%A4%9A%E4%B8%AA%E6%BC%8F%E6%B4%9E%20SQL%E6%B3%A8%E5%85%A5%E3%80%81XSS%E3%80%81%E6%96%87%E4%BB%B6%E5%86%99%E5%85%A5.md)
* [Zen Cart 1.5.7b 任意命令执行（CVE-2021-3291）](https://github.com/EdgeSecurityTeam/Vulnerability/blob/main/Zen%20Cart%201.5.7b%20%E4%BB%BB%E6%84%8F%E5%91%BD%E4%BB%A4%E6%89%A7%E8%A1%8C%EF%BC%88CVE-2021-3291%EF%BC%89.md)
* [若依(RuoYi)管理系统 后台任意文件读取](https://github.com/EdgeSecurityTeam/Vulnerability/blob/main/%E8%8B%A5%E4%BE%9D(RuoYi)%E7%AE%A1%E7%90%86%E7%B3%BB%E7%BB%9F%20%E5%90%8E%E5%8F%B0%E4%BB%BB%E6%84%8F%E6%96%87%E4%BB%B6%E8%AF%BB%E5%8F%96.md)
* [BloofoxCMS 0.5.2.1 存储型XSS](https://github.com/EdgeSecurityTeam/Vulnerability/blob/main/BloofoxCMS%200.5.2.1%20%E5%AD%98%E5%82%A8%E5%9E%8BXSS.md)
* [Chrome 插件 Vue.js devtools UXSS](https://github.com/EdgeSecurityTeam/Vulnerability/blob/main/Chrome%20%E6%8F%92%E4%BB%B6%20Vue.js%20devtools%20UXSS.md)
* [CVE-2021-3156 (Baron Samedit) Sudo 中基于堆的缓冲区溢出漏洞](https://github.com/EdgeSecurityTeam/Vulnerability/blob/main/CVE-2021-3156%20(Baron%20Samedit)%20Sudo%20%E4%B8%AD%E5%9F%BA%E4%BA%8E%E5%A0%86%E7%9A%84%E7%BC%93%E5%86%B2%E5%8C%BA%E6%BA%A2%E5%87%BA%E6%BC%8F%E6%B4%9E.md)
* [IBOS酷办公系统 后台命令执行](https://github.com/EdgeSecurityTeam/Vulnerability/blob/main/IBOS%E9%85%B7%E5%8A%9E%E5%85%AC%E7%B3%BB%E7%BB%9F%20%E5%90%8E%E5%8F%B0%E5%91%BD%E4%BB%A4%E6%89%A7%E8%A1%8C.md)
* [Linksys WRT160NL 身份验证命令注入（CVE-2021-25310）](https://github.com/EdgeSecurityTeam/Vulnerability/blob/main/Linksys%20WRT160NL%20%E8%BA%AB%E4%BB%BD%E9%AA%8C%E8%AF%81%E5%91%BD%E4%BB%A4%E6%B3%A8%E5%85%A5%EF%BC%88CVE-2021-25310%EF%BC%89.md)
