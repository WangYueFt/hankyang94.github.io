---
layout: page
permalink: /publications/
title: Publications
description:
years: [2022,2021,2020,2019]
nav: true
---

Please see my [Google Scholar](https://scholar.google.com/citations?user=GuKEDfixZqsC&hl=en) for a full list of publications.

<!-- _pages/publications.md -->
<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>
