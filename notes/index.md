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


<div class="tiles">
{% for post in site.categories.portfolio %}
  {% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles 把所有categories 有notes的列出來-->

