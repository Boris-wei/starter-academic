---
title: 在Mac中使用LaTeX，如何将数学字体设置为Times风格？
subtitle: 被这个问题困扰了大半年时间，今天终于弄明白，正好趁热打铁，总结一下。
date: 2021-04-21T07:55:43.890Z
summary: ""
draft: false
featured: false
authors:
  - admin
tags:
  - LaTeX
categories: []
image:
  filename: featured.png
  focal_point: smart
  placement: 2
  preview_only: false
---
实际上，我是一直不很喜欢LaTeX的原生数学字体的，特别是数字的写法让我非常难受，一直想换一种数学字体。后来找到了一篇论文，专门收集了LaTeX的所有免费字体，名叫[A Survey of Free Math Fonts for TeX and LaTeX](http://www.nic.funet.fi/index/TeX/CTAN/info/Free_Math_Font_Survey/survey.pdf)于是乎就找到了我至今为止最为满意的字体，有着times风格，同时积分号和求和号的写法我也大为喜欢，大体效果如下：

![](截屏2021-04-21-下午4.18.31.png)

论文上的指导非常简单，照着它的意思，直接在加载宏包区域再加一行代码

```tex
\usepackage{mathtime}
```

即可。兴冲冲的去试，立刻报错，宏包找不到，于是就有了这篇文章。

我的电脑是Mac，编译LaTeX的环境是Sublime Text+Skim，采用XeLaTeX。想要了解如何进行LaTeX在Mac上的基本配置，可以参考 https://link.zhihu.com/?target=https%3A//www.jianshu.com/p/b1e3b029ded5