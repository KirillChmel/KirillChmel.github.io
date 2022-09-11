---
layout: page
permalink: /surveys/
title: surveys
description: This page contains information about surveys for the purposes of my own or collaborative projects. Should you have any questions about these surveys or access to the data, feel free to contact me.
years: [2022, 2021, 2020, 2019, 2018]
nav: true
nav_order: 3
---

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f surveys -q @survey[year={{y}}]* %}
{% endfor %}
