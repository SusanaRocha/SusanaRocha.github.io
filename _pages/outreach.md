---
layout: archive
title: "Science Outreach"
permalink: /outreach/
author_profile: true
---

<p align= "justify">

In our research group we use nanotechnology and cutting-edge microscopy techniques to understand life at the molecular scale.

How do cells form an organ? How do they communicate with each other?
Can we develop new (and hopefully better) ways to treat cancer?
How can we improve our health by looking at single molecules?


<div class="grid__wrapper">
  {% for post in site.mainoutreach %}
    {% include archive-single-proj.html type="grid" %}
  {% endfor %}
</div>
