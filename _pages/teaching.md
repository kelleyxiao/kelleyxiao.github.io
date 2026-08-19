---
layout: page
title: teaching
permalink: /teaching/
nav: true
nav_order: 3
calendar: false
---

{% assign ace455 = site.teachings | where: "course_id", "ace-455" | first %}
{% assign ace474 = site.teachings | where: "course_id", "ace-474" | first %}
{% assign mathcamp_instructor = site.teachings | where: "course_id", "math-camp-instructor" | first %}
{% assign mathcamp_ta = site.teachings | where: "course_id", "math-camp-ta" | first %}

<div class="teaching-list">
  <h2 class="year">2025</h2>
  <ul class="teaching-year-list">
    <li><a href="{{ ace455.url | relative_url }}">{{ ace455.title }}</a></li>
    <li><a href="{{ mathcamp_instructor.url | relative_url }}">{{ mathcamp_instructor.title }}</a></li>
  </ul>

  <h2 class="year">2024</h2>
  <ul class="teaching-year-list">
    <li><a href="{{ ace455.url | relative_url }}">{{ ace455.title }}</a></li>
    <li><a href="{{ ace474.url | relative_url }}">{{ ace474.title }}</a></li>
    <li><a href="{{ mathcamp_ta.url | relative_url }}">{{ mathcamp_ta.title }}</a></li>
  </ul>

  <h2 class="year">2023</h2>
  <ul class="teaching-year-list">
    <li><a href="{{ ace455.url | relative_url }}">{{ ace455.title }}</a></li>
    <li><a href="{{ mathcamp_ta.url | relative_url }}">{{ mathcamp_ta.title }}</a></li>
  </ul>
</div>
