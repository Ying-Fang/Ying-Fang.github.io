---
layout: archive
title: "文章（信息可视化）"
date: 2018-1-1T18:46:45-04:00
modified:
excerpt: "笔记"
tags: []

---


<div class="tiles">
{% for post in site.categories.infovis %}
  {% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles 把所有categories 有 infovisnotes 的列出来-->
