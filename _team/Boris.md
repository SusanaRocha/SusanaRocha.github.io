---
title: "Boris Louis"
collection: team
header:
  teaser: boris.png
tags: phd
tagline: co-promotor
date: 2017-01-01
subject: "Fluorescence microscopy, a versatile tool to unravel polymer properties"
prom: Prof. Johan Hofkens
email: boris.louis@kuleuven.be
---
<p align= "justify">
Polymers are large molecules formed by linkage of repetitive structural units leading to a molecular chain and, more recently, to sheet-like structures. Polymers properties are determined not only by their structural units but also by their conformation and environment, thus, offering great possibilities to tune their properties. Polymer materials are flexible and light while they can be stronger than steel, they can conduct electricity and emit light. Consequently, they take an important part in our modern world. Moreover, even for the same material, individual molecules differ from one another due to the different conformations they can adopt. Therefore, to better understand the world of polymers, we propose to study individual molecules rather than bulk samples in which such individual level information is averaged out. We will use fluorescence microscopy and spectroscopy to study some of the most remarkable polymers available today: conjugated polymers used in highly efficient solar cell, dendronized polymers (DP) and two- dimensional sheet-like polymers (2DP). Connecting the electronic properties of conjugated chains to their conformation is crucial for fundamental physical understanding, paving the way for improvement in opto-electronic devices. The DPs will allow us to study polymer reptation in 3D and compare it to the reptation theory. Finally, the 2DPs are interesting as a new, unexplored materials where virtually nothing is known about their potential applications

<h2> Publications </h2>
{% for post in site.publications reversed %}
  {% if post.authors contains 'Boris Louis' %}
    {% include archive-single-pub.html %}
  {% endif %}
{% endfor %}
