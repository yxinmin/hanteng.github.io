---
layout: archive
title: "期末项目"
date: 2018-01-07T11:40:45-04:00
modified:
excerpt: "化妆品零售店分布"
tags: []
image: 
  feature: 
  teaser: Portfolio.svg
---

<h4>随着经济发展，人们生活品质的提高，对于自己形象的注意程度也越来越高。化妆品的普及确实是一个女生都会关注的一个重要的点</h4>
『哪一家市场优势大？』『门店分布范围广？』从高德地图中提取数据，用七个关键词：屈臣氏，娇兰佳人，莎莎，唐三彩，妍丽 ，千色店，美颜坊。

此研究根据读取高德地图约四千笔数据。

<div class="row">
<div class="col-sm-7" markdown="1"><!-- left -->
##### 门店数量：屈臣氏门店最多
从全国范围内选取，从条形图上可以看出。

![品牌比较]({{ "/images/条形图.png" | absolute_url }})

##### POI结果城市比较：上海市居冠

- 单就城市为比较单位，上海市居冠，广东省内分成主要的深圳及广州。
- 上海市引领最大两类别：体育休闲及购物服务。
- 广东省深圳的公司企业多，展示深圳的私部门在此领域创新的重要地位

![各店铺分布]({{ "/images/地图.png" | absolute_url }})

</div> 
<div class="col-sm-5" markdown="1" ><!-- right -->
##### POI结果：高德为百度两倍

- 高德地图：<i class="fa fa-map-marker" aria-hidden="true"></i><i class="fa fa-map-marker" aria-hidden="true"></i> 799笔
- 百度地图：<i class="fa fa-map-marker" aria-hidden="true"></i> 388笔

##### POI分布：珠江三角洲
![各省比较]({{ "/images/city.png" | absolute_url }})

* 就珠江三角洲地区来看，数量最多的体育休闲服务分布最广。
* 公司企业集中在深圳；生活服务多在广州，东莞两类各一点。
* 政府机构及社会团体方面，就一点在广州。

</div>


<hr>
<br/>
以下展示其他学生作品集，好的丶可改进的及有趣的

<div class="tiles">fovis
{% for post in site.categories.infovis %}
  {% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles 把所有categories 有 infovis 的列出来-->
