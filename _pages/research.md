---
layout: page
permalink: /research/
title: research
description: This page contains information about research projects in which I have previously been involved. Before I started my dissertation project, I worked on various topics in the field of public opinion research. Reach me out at <a href='mailto::kc3580@columbia.edu'>kc3580@columbia.edu</a> if you need additional information about these projects or want to collaborate on some of them.
years: [2022, 2021]
nav: true
nav_order: 2
---
<!-- _pages/publications.md -->
<div class="publications">

<h3>public opinion during wartime</h3>
On the night of February 24, 2022, the President of Ukraine Volodymyr Zelensky addressed the Russian population when the threat of the Russian invasion was imminent: “Do Russians want war? The answer is up to you”. Since then I have never stopped thinking about the war. The question of Mr. Zelensky made me think of the validity of the public opinion data collected during wartime. Can we use these data to figure out the reasons why the population support this egregious use of  violence by the Russian state in Ukraine? If yes, what are these reasons?

<b>Related funding:</b> Communication Factors of Political Behavior. HSE University. PI: Nikita Savin.
{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}


<h3>public opinion in times of the pandemic</h3>
With the spread of the novel coronavirus in 2020, the number of published articles, preprints, and manuscript was unprecedentedly rising. I also embarked on multiple research projects about the societal consequences of the COVID-19, as well as initiated several projects to study its implications for political preferences and voting. Quarantine times have been the most productive in my academic career so far.

<b>Related funding (1):</b> Values Transformation and Subjective Well-being: a Regional Perspective (№18-18-00341). The Russian Science Foundation. PI: Eduard Ponarin.
<b>Related funding (2):</b> Mechanisms of Public Opinion Formation Under the Crisis Media Agenda (№20-011-31725). Russian Foundation for Basic Research. PI: Aigul Klimova.
{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}


<h3>public opinion under the media influence</h3>
{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}


<h3>education policy</h3>
{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>
