---
layout: page
permalink: /publications/
title: Publications
description: A list of my publications, including scientific journal papers, conference papers and proceedings, and patents.
years: []
nav: true
nav_order: 3
---
<!-- _pages/publications.md -->
<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f {{ site.scholar.bibliography }} -q @*[year={{y}}]* %}
{% endfor %}

</div>
