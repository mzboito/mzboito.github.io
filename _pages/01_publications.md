---
layout: page
permalink: /publications/
title: Publications
description: Publications in reversed chronological order including <span style="color:#EF476F; font-weight:bold;">International Conferences</span>, <span style="color:#118AB2; font-weight:bold;">International Workshops</span>, <span style="color:#12B589; font-weight:bold;">Journals</span> and <span style="color:#5555B6; font-weight:bold;">Local Conferences and Workshops</span>.
years: [2026, 2025, 2024, 2023, 2022, 2021, 2020, 2019, 2018, 2017, 2014]
nav: true
---

<div class="publications">

{% for y in page.years %}

  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>
