---
layout: page
title: 简介
title_home: 井底之蛙的程序人生
---
{% include JB/setup %}

吴凯，男，踩着80年代的尾巴出生，现居于武汉。

计算机科班出生，从大学到研究生再到如今就业，了解的计算机技术较多而杂，然则偶有基础不稳、所学不深之困惑。

常于网上阅览一些技术牛人的博客，盛觉自己如井底之蛙。

苦思良久，如今现状之形成有以下几点原因：

1. `所学颇杂`。大学参与游戏开发，研究生至今从事嵌入式开发工作，业余学习移动互联网。

2. `放纵自我`。没有合理规划时间，学习缺乏连续性，不够专注，缺乏毅力。	

3. `不知总结`。没有及时总结自己的学习、工作经验，没有积累（文档、代码），没有把所学知识形成系统的认知体系。

其中第三点无疑是最重要的，也是我决定写博客的一个主要原因。

<br/>
    
## 技术
---------------------------------------
技术栏目的文章主要总结、分析计算机技术.

<ul class="posts">
  {% for post in site.posts %}
	{% if post.category == "technology" %}
    		<li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
	{% endif %}
  {% endfor %}
</ul>

<br/>

## 随笔
---------------------------------------
随笔栏目的文章主要记录、分析程序人生的感悟.

<ul class="posts">
  {% for post in site.posts %}
	{% if post.category == "essay" %}
    		<li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
	{% endif %}
  {% endfor %}
</ul>


