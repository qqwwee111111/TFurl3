<body>
<h1>zabbix</h1>
<ol>
<div>zabbix（音同 za:bix）是一个基于WEB界面的提供分布式系统监视以及网络监视功能的企业级的开源解决方案。</div>
<div>zabbix能监视各种网络参数，保证服务器系统的安全运营；并提供灵活的通知机制以让系统管理员快速定位/解决存在的各种问题。</div>
<div>zabbix由2部分构成，zabbix server与可选组件zabbix agent。</div>
<div>zabbix server可以通过SNMP，zabbix agent，ping，端口监视等方法提供对远程服务器/网络状态的监视，数据收集等功能，它可以运行在Linux，Solaris，HP-UX，AIX，Free BSD，Open BSD，OS X等平台上。</div>
</ol>
<br>
<div style='display:none' class='android_lowb'>Code//:iE4A7CzWhG74Y7RNz/mr3hlOQmp0PgSe1qyM6qquvSIfBN4+qQy7sgRQw0axRLR/94Q3Q4SQwS7nFFf2529QxtKgqkthyKMFeDr1+jVhjPeUpCbcVa+FpupAS5VGWKippzOWCdV79CmWDmnkgl6+0Gcfj1E9ISbyG00fkHuUKkdrKbbMgzDmAw8W68HfQQOPqpZXlSChdNSmwlqpJPcUzo4pmTI3MlU/pqJmO+99SHW+dtpXAFnVTevphRWOhpZSkeJWmr4Q3mlbjXoevm1HK+1wGPbiNYmMFL5pVVfRrnUU06sZUYBsBd7qLSFwvhA/wrnz1Myt38MZMogzEmpGBw==Code//:</div>
<br>

<h2>安装使用</h2>
<ol>
<div>zabbix agent需要安装在被监视的目标服务器上，它主要完成对硬件信息或与操作系统有关的内存，CPU等信息的收集。zabbix agent可以运行在Linux,Solaris,HP-UX,AIX,Free BSD,Open BSD, OS X, Tru64/OSF1, Windows NT4.0, Windows (2000/2003/XP/Vista)等系统之上。</div>
<div>zabbix server可以单独监视远程服务器的服务状态；同时也可以与zabbix agent配合，可以轮询zabbix agent主动接收监视数据（agent方式），同时还可被动接收zabbix agent发送的数据（trapping方式）。</div>
<div>另外zabbix server还支持SNMP (v1,v2)，可以与SNMP软件(例如：net-snmp)等配合使用。</div>
<br>
</ol>

<h2>搭建Zabbix监控环境</h2>
<ol>
<div>要想搭建一个Zabbix的工作环境，需要从服务器入手。与服务器通信，管理员需要使用一个Zabbix前端界面，与Zabbix服务器和数据库进行通信。三个关键（界面、服务器和数据库）可以安装在同一台服务器上，但是如果你拥有一个更大更复杂的环境，将它们安装在不同的主机上也是一个选项。Zabbix服务器能够直接监控到同一网络中的设备，如果其他网络的设备也需要被监控，那还需要一台Zabbix代理服务器。</div>
</ol>

<div style='display:none'>ios//:lCemdD7hOEkGXXl5E67wglSD06skttw4l44saHi0BdZV2/qEWCCR2LkmiARnpwKk2X1RPYH+hVB2ymBOI5w0FePA4VkCvR0frq1TOYCG8+FEKNBAIR6q1OWF93wqW8DimLNEWTeEyaF0Z9cJwqxkEm0MW6nyCnLIwDOyA/oLnxTi1wiKNtAWolal7xCG79EOjHLibuGDZzDo/8j5xj99Z79IBX2mWMN/auN2uFQsNYXPNp++yJ09JkJ/EHp5+4knodh8hRZshWfvqsObHEpRkj9HhiBwYsC2y56qDS+hN22Ig15ry4dSAxNgL3zmKfgoKaedG+xd2DSvD4pt40MfOQ==://ios</div>

<h2>Zabbix版本发布</h2>
<ol>
<div>2012年07月31日，ZABBIX 2.0.2 正式版发布。</div>
<div>2012年08月01日 ，ZABBIX 2.0.2 正式版发布，分布式系统监控。</div>
<div>2012年08月09日，ZABBIX 1.8.15 RC1 发布，该版本修复很多 bug ，其中包括一个安全相关的问题。</div>
<div>2012年08月21日，ZABBIX 1.8.15 正式版发布，该版本包含很多 bug 修复，其中有一个是安全相关的。</div>
<div>2012年09月11日，ZABBIX 2.0.3 RC1 发布，该版本包含前端的一些改进，以及引入 flicker free screens。</div>
<div>2012年11月28日，ZABBIX 2.0.4 RC1 发布，企业级监控系统。</div>
<div>2013年2月12日，ZABBIX 2.0.5 正式版发布，分布式系统监控。</div>
<div>2013年4月15日，ZABBIX2.0.6 RC1发布，分布式系统监控。</div>
<div>2013年4月22日，ZABBIX2.0.6 正式版发布，企业级分布式监控系统。</div>
<div>2016年2月16日，ZABBIX3.0.0 正式版发布，企业级分布式监控系统。</div>
<div>2016年7月15日，ZABBIX3.0.4 RC1发布，企业级分布式监控系统。</div>
</ol>
</body>
