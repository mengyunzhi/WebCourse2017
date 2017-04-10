---
layout: post
title:  "第二节：http-server"
description: "安装http-server服务"
date: 2017-04-10T11:31:53+08:00
categories: chapter1
author: ""
---
在上一节中，我们接触了`nodejs`下的第一款软件`npm`, 当我们使用命令行来启用这款软件时，得到了这个软件给我们的一些回执信息。

我们把`nodejs`比作为操作系统，那么`npm`就是这个操作系统下的360软件管家。我们在`nodejs`这个操作系统下，使用的所有软件，都是要通过`npm`这个软件管家来实现的。

本节中，我们共同来使用`npm`软件管家，来安装第二款`nodejs`中的软件 -- `http-server`

地址: [https://www.npmjs.com/package/http-server](https://www.npmjs.com/package/http-server)

在页面中，我们找到:
![{{site.imageurl}}/chapter1/2.1.png]({{site.imageurl}}/chapter1/2.1.png)

并按提示在命令行中输入以下命令：
`npm install http-server -g`


依网速的不时，在安装过程中，等待的时间也会不同。耐心等待，直至安装完成。如果你等了5分钟左右，还是没有提示任何信息的话，你可以考虑使用ctrl+c，终止程序安装，然后再继续使用`npm install http-server -g`来重新安装一次了。

安装完成后，我们在命令行中，输入`http-server`, 当看到类似于如下提示时，证明安装成功。
```
Starting up http-server, serving 你当前运行cmd的目录名
Available on:
  http://127.0.0.1:8080
  http://192.168.1.100:8080
```

一般情况下，我们将看到两个IP地址，一个是127.0.0.1,代表本机。另一个依我们的网络连接的路由器不同，会显示不同的信息。没关系，不管显示的是什么IP，只要显示了，那就说明http-server安装并启动成功了。

此时，我们随意打开一个浏览器，比如说firefox，比如说chrome。然后在地址栏中输入`http://127.0.0.1:8080`，最终你将看到：成功的构建了本地http服务。

<hr />
为了不影响下一节的操作，上面的实验成功后，我们可以在命令行中使用ctrl+c来终止程序，也可以点击命令行窗口右上方的关闭按钮。

![{{site.imageurl}}/chapter1/2.1.gif]({{site.imageurl}}/chapter1/2.1.gif)