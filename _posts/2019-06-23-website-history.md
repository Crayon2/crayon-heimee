---
layout: page
title: 网站设计history
date: 2019-6-23
categories:
     - 网站设计
---

### 网站设计是将策划案中的内容、网站的主题模式，以及结合自己的认识通过艺术的手法表现出来；

关于Jekyll 静态网站，算起来是我们第二次接触了。而我们现在主要是修改别人的模板。

对于一个网站来讲，最主要的就是它的标题，就拿期末项目来讲，标题是在theme.yml里进行修改的，而其字体大小、颜色，则是在global.scss中修改

<img src="/assets/images/global.png">

关于面包屑搜索导航，其实没有想象中的复杂，只需要开启config.yml文件当中的search即可

<img src="/assets/images/true.png">

侧边导航栏则只需要先在根目录那里创建你要的文档，然后在theme.yml中的navigation_pages里添加你创建的文档的名字，记得要加上你文档的格式

<img src="/assets/images/theme.png">

<img src="/assets/images/data.png">

在创建的文档里还要加入集合页路径，方便你写的文章的归类。

而我们每个文档中的文章，则是以md格式创建在_posts文档里，文章命名以日期加名字为宜，在文章的开头，还要加上文章属性归类。

<img src="/assets/images/history.png">

接下来讲一下如何加入banner图，其实很简单，只需先上传你的图片，对它加以命名，然后在你想加的文档的头部插上链接即可。

<img src="/assets/images/zhizuosvg.png">

开启分页功能，也是在config.yml当中修改

<img src="/assets/images/fenye.png">

接着将根目录的index.md改为index.html,并且在头部增加paginate: true这一行代码

在首页中，我们可以发现，标题重复了一次，那么怎样去删除或者是隐藏掉标题呢？隐藏标题主要在_layouts/home.html里面增加以下代码就行

<img src="/assets/images/yincang.png">

而移除掉重复的标，则在index.md里增加以下代码。

<img src="/assets/images/yichu.png">

当然，在这里因为将index.md改为index.html了，所以建议隐藏重复的标题。

本次Jekyll 静态网站项目，主要的内容就是这些，虽然还不太全面。

