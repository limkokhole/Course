# Web

>学习路线：[Web安全学习路线](http://momomoxiaoxi.com/2016/10/22/Websecurity/)


## Books

* 黑客攻防技术宝典-web实战篇
* 白帽子讲web安全
* SQL注入攻击与防御
* [腾讯实例教程] 那些年我们一起学XSS

## Practices

* SQLi_Lab(php+mysql注入实验) [github地址](https://github.com/Audi-1/sqli-labs)
* DVWA(综合渗透测试靶场) [github地址](https://github.com/ethicalhack3r/DVWA)
* xss在线练习：
    * [xss-quiz](http://xss-quiz.int21h.jp/)
    * [alert1-to-win](https://alf.nu/alert1)
    * [prompt-to-win](http://prompt.ml/0)
* [十大渗透测试演练系统](http://www.freebuf.com/sectool/4708.html)
* [实验吧](http://www.shiyanbar.com/)
* [i春秋](https://www.ichunqiu.com/)
* [bugku](http://www.bugku.com/)
* [南京邮电大学网络攻防训练平台](http://ctf.nuptsast.com/)
* [JarvisOJ](https://www.jarvisoj.com/)
* [SniperOJ](http://www.sniperoj.com/)

## Tools

* burpsuite pro(群文件中有破解版)
* AWVS(扫描器)
* 御剑(爆目录)
* 中国菜刀(CKnife java版) [github地址](https://github.com/Chora10/Cknife)
* sqlmap [github地址](https://github.com/sqlmapproject/sqlmap)
* firefox hackbar插件
* 源码泄露检测工具 [github地址](https://github.com/WangYihang/SourceLeakHacker)

## Articles
* php
	* [从弱类型利用以及对象注入到SQL注入](http://bobao.360.cn/learning/detail/3486.html)
	* [php弱类型安全问题总结](https://blog.spoock.com/2016/06/25/weakly-typed-security/)
	* [php里的随机数](http://5alt.me/2017/06/php%E9%87%8C%E7%9A%84%E9%9A%8F%E6%9C%BA%E6%95%B0/)
* 注入
	* sql注入
		* [HackMe-SQL-Injection-Challenges](https://github.com/breakthenet/HackMe-SQL-Injection-Challenges)
		* [MSSQL DBA权限获取WEBSHELL的过程](http://fuping.site/2017/05/16/MSSQL-DBA-Permission-GET-WEBSHELL/)
		* [sqlmap试用总结](http://www.zerokeeper.com/web-security/sqlmap-usage-summary.html)
		* [Linux MySQL Udf提权](http://www.91ri.org/16540.html)
		* [使用burp macros和sqlmap绕过csrf防护进行sql注入](http://bobao.360.cn/learning/detail/3557.html)
		* [MySQL 注入攻击与防御](http://bobao.360.cn/learning/detail/3758.html)
		* [SQL注入防御与绕过的几种姿势](http://bobao.360.cn/learning/detail/3801.html)
		* [MySQL False注入及技巧总结](http://bobao.360.cn/learning/detail/3804.html)
		* [MSSQL 注入攻击与防御](http://bobao.360.cn/learning/detail/3807.html)
	* XML External Entity Injection
		* [XXE漏洞分析](http://www.4o4notfound.org/index.php/archives/29/)
		* [XML实体注入漏洞攻与防](http://www.hackersb.cn/hacker/211.html)
		* [XXE (XML External Entity Injection) 漏洞实践](http://www.mottoin.com/101806.html)
		* [如何挖掘Uber网站的XXE注入漏洞](http://www.mottoin.com/86853.html)
		* [XXE被提起时我们会想到什么](http://www.mottoin.com/88085.html)
		* [XXE漏洞的简单理解和测试](http://www.mottoin.com/92794.html)
		* [XXE漏洞攻防之我见](http://bobao.360.cn/learning/detail/3841.html)
		* [XXE漏洞利用的一些技巧](http://www.91ri.org/17052.html)
	* JSONP注入
		* [JSONP注入解析](http://www.freebuf.com/articles/web/126347.html)
		* [JSONP安全攻防技术](http://blog.knownsec.com/2015/03/jsonp_security_technic/)
		*  [一次关于JSONP的小实验与总结](http://www.cnblogs.com/vimsk/archive/2013/01/29/2877888.html)
		* [利用JSONP跨域获取信息](https://xianzhi.aliyun.com/forum/read/1571.html)
		* [关于跨域和jsonp的一些理解(新手向)](https://segmentfault.com/a/1190000009577990)
	* SSTI(服务端模板注入)
		* [乱弹Flask模板注入](http://www.freebuf.com/articles/web/88768.html)
		* [服务端模板注入攻击 （SSTI）之浅析](http://www.freebuf.com/articles/web/88768.html)
		* [Exploring SSTI in Flask/Jinja2](https://nvisium.com/blog/2016/03/09/exploring-ssti-in-flask-jinja2/)
		* [Exploring SSTI in Flask/Jinja2, Part II](https://nvisium.com/blog/2016/03/11/exploring-ssti-in-flask-jinja2-part-ii/)
		* [Flask Jinja2开发中遇到的的服务端注入问题研究](http://www.freebuf.com/articles/web/136118.html)
		* [FlaskJinja2 开发中遇到的的服务端注入问题研究 II](http://www.freebuf.com/articles/web/136180.html)
* XSS
	* [浅谈跨站脚本攻击与防御](https://thief.one/2017/05/31/1/)
	* [漫谈同源策略攻防](http://bobao.360.cn/learning/detail/3848.html)
	* [XSS小记](https://xianzhi.aliyun.com/forum/read/196.html?fpage=7)
	* [XSSBypass Cookbook](https://xianzhi.aliyun.com/forum/read/536.html?fpage=7)
	* [[Web安全]当代 Web 的 JSON 劫持技巧](https://xianzhi.aliyun.com/forum/read/462.html?fpage=10)
	* [Content Security Policy 入门教程](https://jaq.alibaba.com/community/art/show?spm=a313e.7916646.24000001.49.ZP8rXN&articleid=518)
	* [不常见的xss利用探索](http://docs.ioin.in/writeup/wps2015.org/_2016_06_27__E4_B8_8D_E5_B8_B8_E8_A7_81_E7_9A_84xss_E5_88_A9_E7_94_A8_E6_8E_A2_E7_B4_A2_/index.html)
	* [CRLF Injection and Bypass Tencent WAF](https://zhchbin.github.io/2016/01/31/CRLF-Injection-and-Bypass-WAF/)
	* [chrome是怎么过滤XSS的呐](https://www.zhihu.com/question/20941818/answer/180842222?utm_source=qq&utm_medium=social)
	* [XSS Cheat Sheet](https://xianzhi.aliyun.com/forum/read/1704.html)
	* [CRLF Injection and Bypass Tencent WAF](https://xianzhi.aliyun.com/forum/read/1704.html)
