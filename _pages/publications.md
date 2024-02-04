---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% assign curr_year = site.time | date: '%Y' %}
{% for y in (2020..curr_year) reversed %}
  <h3 class="year">{{y}}</h3>
  {% bibliography -q @*[year={{y}}]* %}
{% endfor %}
