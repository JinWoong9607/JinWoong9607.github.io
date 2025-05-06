---
layout: default
title: Algorithms
permalink: /algorithms/
---

<ul>
{% for doc in site.algorithms %}
  <li>
    <a href="{{ doc.url }}">{{ doc.title }}</a>
  </li>
{% endfor %}
</ul>
