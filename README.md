# -FMZ-

<BR>
  
如何在发明者量化平台(FMZ)上部署托管者

<BR>

<font face="微软雅黑" color=575757 size=4>

<BR>

[发明者主页](https://www.fmz.com/)

发明者是区块链里一个非常著名的量化社区，里面有很多策略源码可以学习，也有很多教程。而在上面做策略，则绕不开托管者的部署，托管者的部署需要云服务器，通过云服务器它可以永远不休息的为你执行策略。

<BR>

在看了很多文档后，发现目前官方的视频已经过时。所以对这个教程做了重新的梳理。希望对大家有帮助，帮大家少走弯路。


<BR>



<BR>

**1、购买阿里云轻量应用服务器组**

<BR>

请注意，如果是数字货币，一定要选用海外服务器。我选用的是新加坡。

一年是288元，应该可以按月付费，一个月就是24

操作系统选Linux

显示是 CenOS

买最低配置即可

<BR>

![](https://hbimg.huabanimg.com/89f30804f3f1079568028f59070db9ba8a59bb8e376f-cKgkQ7_fw658)

<BR>

**2、下载工具**

<BR>

winscp 相当于一个远程文件管理软件，它可以对云端服务器进行文件修改，查看的一个图形化软件。

Putty 可以远程对 服务器运行命令，并且一键安装脚本，解压缩文件。

winscp 就是电脑上的资源管理器，putty 就是电脑上的 CMD。

<BR>

[Wincp 目前官方最新绿色免安装版下载](https://winscp.net/download/WinSCP-5.13.3-Portable.zip)

<BR>

[Wincp 汉化下载](https://winscp.net/translations/dll/5.13.3/chs.zip)

<BR>

[putty 下载链接](https://winscp.net/download/putty.exe)

<BR>

**3、Winscp 如何连接 阿里云**

<BR>

用scp 密钥的方式链接阿里云，方便也快捷，参考官方文档即可。

<BR>

[Winscp 连接 阿里云教程](https://help.aliyun.com/knowledge_detail/60132.html)

<BR>

**4、Putty 部署托管者**

在这里分为 下载 robot 压缩包

对压缩包进行解压缩

测试服务器

最后正式部署

[Putty 部署教程](https://www.fmz.com/bbs-topic/2848)

</font>
