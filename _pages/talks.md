---
layout: page
permalink: /talks/
title: talks
<!-- description: talks by categories in reversed chronological order. generated by jekyll-scholar. -->
years: [2022, 2021, 2020, 2019, 2018, 2016]
nav: true
nav_order: 3
---

<!-- _pages/talks.md -->
<div class="publications">

{%- for y in page.years %}

  <h2 class="year">{{y}}</h2>
  {% bibliography -f talks -q @*[year={{y}}]* %}
{% endfor %}

</div>
