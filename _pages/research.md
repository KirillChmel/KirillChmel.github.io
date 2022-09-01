---
layout: page
permalink: /research/
title: research
description: This page contains information about research projects in which I have previously been involved. Before I started my dissertation project, I worked on various topics in the field of public opinion research.
years: [2022, 2021]
nav: true
nav_order: 2
---
<!-- _pages/publications.md -->
<div class="publications">

<h2>public opinion during wartime</h2>
{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}


<h2>public opinion in times of the pandemic</h2>
{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}


<h2>public opinion under the media influence</h2>
{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}


<h2>education policy</h2>
{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>
