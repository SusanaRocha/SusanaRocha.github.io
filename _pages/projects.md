---
layout: archive
title: "Research Projects"
permalink: /projects/
author_profile: false
sidebar:
  nav: "Projs"
---

<a id="Topics" data-hs-anchor="true"></a>
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
<a id="Networks" data-hs-anchor="true"></a>
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
<a id="Collaborations" data-hs-anchor="true"></a>
<h2>Collaborations</h2>
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
