---
title: 关于
layout: page
comments: no
---

### 个人兴趣

1. 直观的、负责的和用脑子的编程
    - 直观就是能讲给老太太听
    - 负责就是自己真的明白自己讲的话
    - 用脑子就是不盲目套模型，不搞模型崇拜
1. 老少咸宜的笑话
    - 笑一笑，十年少，为什么要板着脸生活呢？
    - 欢迎大家给我发好的笑话，比如你要是遇到一个问题想问我的话，可以顺便发个笑话给我，以提升回复速度
1. 聪明的、有趣的计算机程序
    - 计算机是用来为人类服务的，让聪明的程序替代你的非智力劳动吧
    - 计算机自己不懂如何变得有趣，但人懂


----

### 本站架构

本站目前采用Jekyll作为后台系统，纯码农的乐土(^_^)，Jekyll，一个以纯文本文件形式写博客的系统，其作者在写出这套系统后曾经写了一篇日志“[像一个黑客一样写博客](http://tom.preston-werner.com/2008/11/17/blogging-like-a-hacker.html)”，最初我在[Charlie Sharpsteen](https://github.com/Sharpie)那里看到这个标题时并没有在意，但过了很长时间之后，我开始感受到GitHub的日益强大，越来越对我的胃口，于是我的世界完全被GIT化了，我的个人小项目都到那里，直到现在连博客也搬过来了。

博客模板是在[rusty shutter](http://lhzhang.com/)那里偷偷扒过来的，虽然很无耻，但我实在是很喜欢这个简洁的设计，唉，即使挨骂我也想偷，设计的很棒。我对CSS和字体做了一些局部微调，主要功劳都是他的，哪天要是有机会见到你我一定请客。

----

###联系方式：

{% if site.qq %}
ＱＱ：[{{ site.qq }}](tencent://message/?uin={{ site.qq }})
{% endif %}
网站：[{{ site.name }}]({{ site.url }})

邮箱：[{{ site.email }}](mailto:{{ site.email }})

GitHub : [http://github.com/{{ site.github }}](http://github.com/{{ site.github }})

[See my Resume](http://stackvoid.com/about/profile)
----

{% if site.weibo %}
[![新浪微博](http://service.t.sina.com.cn/widget/qmd/1766253541/013bec28/1.png)](http://weibo.com/u/{{ site.weibo }})
{% endif %}
