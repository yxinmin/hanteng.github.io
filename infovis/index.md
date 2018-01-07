---
layout: archive
title: "信息可视化作品集"
date: 2017-12-30T11:40:45-04:00
modified:
excerpt: "作品"
tags: []
image: 
  feature: infovis.jpeg
  teaser:
---


<div class="tiles">
{% for post in site.categories.portfolio %}
  {% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles 把所有categories 有tableau的列出來-->

