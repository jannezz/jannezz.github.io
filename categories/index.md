---
layout: page
title: Categories
---

{% for category in site.categories %}
<p>
  <a href="/categories/{{ category | first }}">{{ category | first }}</a>
  &nbsp;&nbsp;<span class="badge rounded">{{ category[1].size }}</span>
</p>
{% endfor %}