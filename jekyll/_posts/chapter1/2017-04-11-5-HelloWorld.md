---
layout: post
title:  "第五节：Hello World!"
description: "你好，世界"
date: 2017-04-10T11:36:53+08:00
categories: chapter1
author: "作者"
---
终于可以开发编写`HelloWorld!`了。
我们使用的系统，默认是隐藏了文件的扩展名的。比如一个`word`文档 -- `hebut`, 它的全称应该是`hebut.docx`或`hebut.doc`。对普通的用户而言，显示扩展名无增加它使用系统的成本，因为大多数的非计算机专业的普通人，是搞不清同时也不愿意搞清什么`.docx`的。但对于我们，查看并显示文件的扩展名，是一项不得不做的工作。

> 如果你手上适好有已经中了减毒的U盘，你可以在启动扩展名的同时显示隐藏及系统文件。此时，你们发现，在你心目中那个`文件夹`，已经变成了`文件夹.exe`。没错，正如我说过的，眼见并不见得为实。

那么如何启用扩展名呢？
如果你的操作系统是win7, 你可以这样：
![{{site.imageurl}}/chapter1/5.1.png]({{site.imageurl}}/chapter1/5.1.png)


启用显示扩展名后，我们发现自己电脑中的文件基本上都有了个 `.xxx`的后缀。是的，我们需要的，就是要把它们显示出来。


# Hello World!

我们打开d盘中的web文件夹，新建一个文本文档，并将其重命名为`index.html`。

> 注意：是`index.html`，而不是`index.html.txt`。

然后使用`sublime`打开它, 你可以选择如下方式的任意一种来完成这个操作。
1. 用鼠标点击`index.html`后，将其托动到`sublime`图标上。
2. 在`sublime`中，选择`file` -> `opnen file`，然后找到d盘中web这个文件夹。
3. 在`index.html`上点击右键，然后选择打开方式，在打开方式中选择`sublime`

使用`sublime`打开后`index.html`, 我们共同来输入以下代码：
```
<h1>Hello World!</h1>
```

`ctrl` + `s` 保存文件!

然后在d盘中的web文件夹中右键打开`git bash here`，输入`http-server`，在浏览器中打开`127.0.0.1:8080`来查看吧。
![{{site.imageurl}}/chapter1/5.2.png]({{site.imageurl}}/chapter1/5.2.png)

> 如果你前面没有关闭`http-server`，你将得到一个端口被占用的提示。解决的方法也很简单，将前面没有关闭的`http-server`关闭一下就可以了。
