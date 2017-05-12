---
layout: post
title:  "第四节：上线自己的网站至服务器"
description: "将自己开发的网站源代码复制至服务器"
date: 2017-05-12T09:12:42+08:00
categories: chapter4
author: "河北工业大学"
---
apache服务的目录位于 c:\xmapp\htdocs文件夹，我们找开此文件夹。
![{{site.imageurl}}/chapter4/6.png]({{site.imageurl}}/chapter4/6.png)

然后清空该文件夹，没错，就是删除这个文件夹中的所有内容：
![{{site.imageurl}}/chapter4/7.png]({{site.imageurl}}/chapter4/7.png)

最后，打开我的电脑，选择共享于服务器上的自己本地电脑相关盘符。找到自己开发的网站，将其网页文件复制到c:\xmapp\htdocs文件夹。

比如：
![{{site.imageurl}}/chapter4/8.png]({{site.imageurl}}/chapter4/8.png)

我们再次打开 http://127.0.0.1 ，看新的文件是否成功。
![{{site.imageurl}}/chapter4/12.png]({{site.imageurl}}/chapter4/12.png)

找开http://123.206.44.131 (替换为你自己的), 看访问公网IP是否成功。
![{{site.imageurl}}/chapter4/15.png]({{site.imageurl}}/chapter4/15.png)

至此，服务器配置信息完毕。自下节开始，我们开始操作自己的电脑。