---
title: "Laurens D'Huys"
collection: team
header:
  teaser: Laurens.png
tags: phd
tagline: co-promotor
date: 2017-09-08
subject: "Expansion microscopy: towards spatially resolved trancriptomics"
prom: Prof. Johan Hofkens
email: laurens.dhuys@kuleuven.be
---
<p align= "justify">


<h2> Publications </h2>
{% for post in site.publications reversed %}
  {% if post.authors contains 'Laurens D Huys' %}
    {% include archive-single-pub.html %}
  {% endif %}
{% endfor %}
