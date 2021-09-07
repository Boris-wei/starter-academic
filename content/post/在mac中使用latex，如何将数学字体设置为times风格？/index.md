---
title: How to make your math font looks like Times New Roman while using LaTeX on mac?
subtitle: ""
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
Actually, I never like the math font originally built on LaTeX. I don't like the number in 

In fact, I have never liked LaTeX's native math fonts very much, especially the way numbers are written makes me very uncomfortable, and I have always wanted to change to a different math font. I found a paper dedicated to all the free fonts in LaTeX called [A Survey of Free Math Fonts for TeX and LaTeX](http://www.nic.funet.fi/index/TeX/CTAN/info/Free_Math_Font_Survey/survey.pdf)So I found the font that I am most satisfied with so far. It has a times style. At the same time, I also like the way of writing the integral symbol and the sum symbol. The general effect is as follows:

![](截屏2021-04-21-下午4.18.31.png)

According to the paper, all you need to do is simply add

```tex
\usepackage{mathtime}
```

at the beginning。However, when I tried to do so,  the computer couldn't compile, saying that package cannot find. I tried for a long time and find out the reason in the end. Therefore, I want to write something just in case I forget it.

I use Macbook to write LaTeX, use Sublime Text as a code editor and use Skim as a pdf reader. If you want to know how to install and set LaTeX on mac, you can refer to [this](https://link.zhihu.com/?target=https%3A//www.jianshu.com/p/b1e3b029ded5).