---
layout: page
title: Teaching
permalink: /teaching/
description:
nav: true
nav_order: 6
display_categories: [Bachelor, Masters, Previous]
---

I teach various courses as a member of the [Department of Computer Science](http://www.racunarstvo.matf.bg.ac.rs/) at the [Faculty of Mathematics](http://www.matf.bg.ac.rs/eng/) in Belgrade.

Detailed information about my courses and course notifications can be found 
@ [my faculty website](https://matf.ristovic.net).

<!-- pages/courses.md -->
<div class="publications">
  <!-- Display categorized courses -->
  {%- for category in page.display_categories %}
  <h2 class="category">{{ category }}</h2>
  <hr/>
  {%- assign categorized_courses = site.courses | where: "category", category -%}
  {%- assign sorted_courses = categorized_courses | sort: "importance" %}
  <!-- Generate cards for each course -->
  <ol class="bibliography">
    <li>
    {%- for course in sorted_courses -%}
      {% include courses.html %}
    {%- endfor %}
    </li>
  </ol>
  {% endfor %}
</div>
