---
layout: post
title:  "第五节：我的建议模块"
description: "使用无序列表"
date: 2017-04-10T16:57:31+08:00
categories: chapter2
author: "河北工业大学"
---
本节中，我们共同来完成我的建议模块：
![{{site.imageurl}}/chapter2/18.png]({{site.imageurl}}/chapter2/18.png)

有了前面我的课程模块，这个模块就变成了本章中最简单的模块了。

## 初始化
```
<!DOCTYPE html>
<html>

<head>
    <meta charset="UTF-8">
    <title>我是标题</title>
</head>

<body>
    <h1>Hello World!</h1>

    <!-- 导航 -->
    <table>
        <tr>
            <td>自我介绍</td>
            <td>所学课程</td>
            <td>我的建议</td>
            <td>友情链接</td>
            <td>生活中的我</td>
        </tr>
    </table>
    <hr />
    <!-- 导航 结束 -->

    <!-- 基本信息 -->
    <img src="duolaiameng.png" />
    <p>梦云智软件开发团队. 2014.12.20. <a href="mailto:3792535@qq.com">3792535@qq.com</a></p>
    <hr />
    <!-- 基本信息 结束 -->

    <!-- 所学课程 -->
    <h2>所学课程</h2>
    <ol>
        <li>软件工程</li>
        <li>数据库</li>
        <li>C语言程序设计</li>
        <li>面向对象的编程思想</li>
    </ol>
    <hr />
    <!-- 所学课程 结束 -->

    <!-- 我的建议 -->
    <h2>我的建议</h2>
    <hr />
    <!-- 我的建议 结束 -->
</body>

</html>
```
刷新页面：

![{{site.imageurl}}/chapter2/19.png]({{site.imageurl}}/chapter2/19.png)

## 增加无序列表
在上节中，我们使用的是有序列表`ordered list` => `ol`, 本节中，我们将有序列表`ol`，更换为 无序列表 => `unordered list` => `ul`

{% highlight html %}
    <!-- 我的建议 -->
    <h2>我的建议</h2>
    <ul>
        <li></li>
        <li></li>
        <li></li>
        <li></li>
    </ul>
    <hr />
    <!-- 我的建议 结束 -->
{% endhighlight %}

刷新页面：

![{{site.imageurl}}/chapter2/20.png]({{site.imageurl}}/chapter2/20.png)

正如我们看到的一样，无序列表没有自动生成1，2，3，4这样的序号，而是生成了小圆点。

最后，让我们来一起加入我的建议中的内容。

{% highlight html %}
    <!-- 我的建议 -->
    <h2>我的建议</h2>
    <ul>
        <li>乐于帮助他人，善于向他人寻求帮助。</li>
        <li>充分接触计算机工程，进一步的了解它是否适合于自己</li>
        <li>如果有梦想，就要敢于付出。因为只有这样，才能自信满满地来取悦自己。</li>
        <li>如果你愿意，我愿意与你共同进度。</li>
    </ul>
    <hr />
    <!-- 我的建议 结束 -->
{% endhighlight %}

刷新页面：
![{{site.imageurl}}/chapter2/21.png]({{site.imageurl}}/chapter2/21.png)

# 总结：
本节中，我们学习了标签`ul (unordered list)` -- 无序列表，并使用其开发了“我的建议”模块。

> 参考：| [http://www.runoob.com/tags/tag-ul.html](http://www.runoob.com/tags/tag-ul.html) 