---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: false
sidebar:
  nav: "Projs"
---

<h2>Main Research Topics</h2>
<hr>
<div class="grid">
<div class="wrapper">
  {% for post in site.projects %}
    {% if post.tags contains 'individual' %}
      {% include archive-single-proj.html type="grid" %}
    {% endif %}
  {% endfor %}
</div>
</div>

<hr-bold>
<h2>Research Networks</h2>
<hr>

<div class="grid">
<div class="wrapper">
  {% for post in site.projects %}
    {% if post.tags contains 'network' %}
      {% include archive-single-proj.html type="grid" %}
    {% endif %}
  {% endfor %}
</div>
</div>


<hr-bold>
<h2>Other Collaborations</h2>
<hr>

<div class="grid">
<div class="wrapper">
  {% for post in site.projects %}
    {% if post.tags contains 'collaboration' %}
      {% include archive-single-proj.html type="grid" %}
    {% endif %}
  {% endfor %}
</div>
</div>
