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
<div class="grid__wrapper">
  {% for post in site.projects %}
    {% if post.tags contains 'individual' %}
      {% include archive-single-proj.html type="grid" %}
    {% endif %}
  {% endfor %}
</div>
<br><br><br><br><br><br><br>
<br><br><br><br><br><br><br>

<div class="grid__wrapper">
  {% for post in site.projects %}
    {% if post.tags contains 'empty' %}
      {% include archive-single-proj.html type="grid" %}
    {% endif %}
  {% endfor %}
</div>

<hr-bold>
<h2>Collaborations</h2>
<hr>

<div class="grid__wrapper">
  {% for post in site.projects %}
    {% if post.tags contains 'collaboration' %}
      {% include archive-single-proj.html type="grid" %}
    {% endif %}
  {% endfor %}
</div>
