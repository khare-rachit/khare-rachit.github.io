---
layout: page
permalink: /presentations/
title: presentations
description: talks and posters in reversed chronological order.
years: [2022, 2021, 2020, 2019, 2016, 2015, 2014, 2013, 2009]
nav: true
nav_order: 3
---
<!-- _pages/presentations.md -->
<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f presentations -q @*[year={{y}}]* %}
{% endfor %}

</div>