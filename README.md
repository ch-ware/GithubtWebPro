# GithubtWebPro
最近Github网站进不去的解决办法
最近突然进步了Github网站，查阅了大量资料找到解决办法如下。

在系统中找到 hosts 文件

Window：C:\Windows\System32\drivers\etc\hosts 或r Linux：/etc/hosts

之前为了能进入Github放置过一些 IP 地址则全部删除。

然放入一下两个 IP 地址：

注释# GitHub Start 
140.82.114.4 github.com
199.232.69.194 github.global.ssl.fastly.net
注释# GitHub End

存盘退出

在 CMD 命令行中执行 ipconfig/flushdns

之后就能进入Github 网址。
