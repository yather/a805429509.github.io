> 这个项目专门用来做笔记。之后也会逐步把自己整理的一些个人笔记迁移到这里。  
> 将囊括mysql、mac、centos、oracle、python、java、sqlserver、前端、以及一些日常的随记等


# 常用实例

```
代码块
```

> 引用 yes ✓ no ✘

[百度](https://www.baidu.com)

![百度logo](https://www.baidu.com/img/bd_logo1.png)

有序列表
1. a
2. b
3. c

无序列表
- a
- b
- c




| 水果 | 价格 | 数量 |
| --  | -- | -- |
| 香蕉 | 1 | 1 |
| 苹果222 | 2 | 2 |

分割线
---

:hankey:

[代码提交的emoji表情](https://gitmoji.carloscuesta.me/)

[emoji表情大全](https://www.webpagefx.com/tools/emoji-cheat-sheet/)



- [ ] c++
- [x] java


# LessOrMore


致谢
====================================
这个分支来自[LessOrMore](https://github.com/luoyan35714/LessOrMore.git)


使用
====================================

下载
------------------------------------

使用git从[LessOrMore](https://github.com/luoyan35714/LessOrMore.git)主页下载项目

``` bash
git clone https://github.com/luoyan35714/LessOrMore.git
```

配置
------------------------------------

`LessOrMore`项目需要配置的只有一个文件`_config.yml`，打开之后按照如下进行配置。

> 特别注意`baseurl`的配置。如果是`***.github.io`项目，不修改为空''的话，会导致JS,CSS等静态资源无法找到的错误

``` bash
name: 博客名称
email: 邮箱地址
author: 作者名
url: 个人网站
### baseurl修改为项目名，如果项目是'***.github.io'，则设置为空''
baseurl: "/LessOrMore"
resume_site: 个人简历网站
github: github地址
github_username: github用户名称
FB:
  comments :
    provider : duoshuo
    duoshuo:
        short_name : 多说账户
    disqus :
        short_name : Disqus账户
```

如何写文章
------------------------------------

在`LessOrMore/_posts`目录下新建一个文件，可以创建文件夹并在文件夹中添加文件，方便维护。在新建文件中粘贴如下信息，并修改以下的`titile`,`date`,`categories`,`tag`的相关信息，添加`* content {:toc}`为目录相关信息，在进行正文书写前需要在目录和正文之间输入至少2行空行。然后按照正常的Markdown语法书写正文。

``` bash
---
layout: post
#标题配置
title:  标题
#时间配置
date:   2016-08-27 01:08:00 +0800
#大类配置
categories: document
#小类配置
tag: 教程
---

* content
{:toc}


我是正文。我是正文。我是正文。我是正文。我是正文。我是正文。
```

执行
------------------------------------

``` bash
jekyll server
```

效果
------------------------------------
打开浏览器并输入URL`http://localhost:4000/`,回车。


关于作者
====================================

热爱开源，热爱折腾的Java程序猿。更多个人信息和联系方式可以参照[我的简介](http://www.hifreud.com/Resume.io/)。

