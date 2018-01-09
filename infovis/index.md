---
layout: archive
title: "信息可视化作品集"
date: 
modified:
excerpt: ""
tags: []
image: 
---
<br/>高德地图API作品期末
<a href="https://yxinmin.github.io/infovis/%E6%9C%9F%E6%9C%AB%E9%A1%B9%E7%9B%AE//"><img src="/images/data.png" width="700" height="587" border="0" /></a>

<br/>其他可视化作品
<div class="tiles">
{% for post in site.categories.infovis %}
  {% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles 把所有categories 有 infovis 的列出来-->
