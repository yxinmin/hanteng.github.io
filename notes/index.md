---
layout: archive
title: "个人心得与笔记"
date: 2017-12-29T11:40:45-04:00
modified:
excerpt: "作品"
tags: []
image: 
  feature: note.gif
  teaser:
---

以下是我的学习笔记


<br/>[RWD学习笔记](https://690244957.github.io/notes/rwd)
<div class="tiles">
{% for post in site.categories.rwd %}
  {% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles 把所有categories 有 rwd 的列出来-->


<br/>[Infovis学习笔记](https://690244957.github.io/notes/infovis)
<div class="tiles">
{% for post in site.categories.infovis %}
  {% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles 把所有categories 有 infovis 的列出来-->
