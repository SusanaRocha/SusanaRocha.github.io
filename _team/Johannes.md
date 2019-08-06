---
title: "Johannes Vandaele"
collection: team
header:
  teaser: johannes.png
tags: phd
tagline: co-promotor
date: 2017-11-01
subject: "Studying nanoscale heterogeneities and dynamics of new biomimetic polymer gels using advanced microscopy"
prom: Prof. Johan Hofkens
email: johannes.vandaele@kuleuven.be
---
<p align= "justify">
Organ failure and tissue lost are challenging health issues due to the lack of organs for transplantation and the limitations of conventional artificial implants. Tissue engineering has emerged as a promising approach to generate biological substitutes. In tissue engineering applications, cells are grown in a three-dimensional platform which is known as a scaffold.
In the last years a great effort has been made in the development of new synthetic biomimetic materials to be used as scaffolds in tissue engineering. Recent studies have shown that the structure and mechanical properties of the materials play a crucial role in regulating cell behaviour. The adjustable mechanical properties of synthetic materials provide more control over the induced cellular behaviours. However, there is lack of technologies that can investigate the role of mechanical and structural properties at the subcellular and molecular level.
In this project I will develop new microscopic approaches to investigate both the structure and mechanics of hydrogels at the nano- and micrometer scale, and their influence in cellular behaviours. As a model, polyisocyanopeptide (PIC) gels will be used. This unique material resembles naturally occurring polymers, while maintaining tunable properties. However, the microscopic toolbox developed will be easily applied to other materials. The fundamental knowledge acquired will be crucial to develop the next generation of biomimetic materials for tissue engineering.

<h2> Publications </h2>
{% for post in site.publications reversed %}
  {% if post.authors contains 'Johannes Vandaele' %}
    {% include archive-single-pub.html %}
  {% endif %}
{% endfor %}
