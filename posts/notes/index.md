---
layout: archive
title: "个人心得与笔记"
date: 2017-12-30T11:40:45-04:00
modified:
excerpt: "我的笔记"
tags: []
image: 
  feature: notes.jpeg
  teaser:
---


<div class="tiles">
{% for post in site.categories.portfolio %}
  {% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles 把所有categories 有 notes 的列出來-->
