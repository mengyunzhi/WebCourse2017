---
layout: post
title:  "第五节：设置安全组"
description: "设置腾讯云的安全组，以打开80端口对外提供服务"
date: 2017-05-12T09:14:19+08:00
categories: chapter4
author: "河北工业大学"
---
腾讯云默认关闭了80端口，我们提供服务的为80端口，需要手动设置将其打开。
登录腾讯云，并打开控制台，找到 安全组 -- 编辑规则
![{{site.imageurl}}/chapter4/16.png]({{site.imageurl}}/chapter4/16.png)

![{{site.imageurl}}/chapter4/17.png]({{site.imageurl}}/chapter4/17.png)

![{{site.imageurl}}/chapter4/18.png]({{site.imageurl}}/chapter4/18.png)

使用浏览器打开公网IP地址：
![{{site.imageurl}}/chapter4/19.png]({{site.imageurl}}/chapter4/19.png)

至此，一台运行于腾讯云的server 2008服务器，便开始在网络上为我们提供7*24小时的不间断服务了。