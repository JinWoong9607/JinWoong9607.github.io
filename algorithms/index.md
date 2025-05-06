---
layout: default
title: Algorithms
permalink: /algorithms/
---

<ul>
  {% for item in site.algorithms %}
    <li><a href="{{ item.url }}">{{ item.title }}</a></li>
  {% endfor %}
</ul>
