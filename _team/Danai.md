---
title: "Danai Laskaratou"
collection: team
header:
  teaser: danai.png
tags: phd
tagline: FLOF grant <br> co-promotor
date: 2016-10-01
subject: "Regulation of cell signaling via ErbB3, a pseudokinase subtype of receptor tyrosine kinases"
prom: Prof. Hideaki Mizuno
email: danai.laskaratou@kuleuven.be
---
<p align= "justify">
Cells use special proteins called receptors to communicate with the extracellular environment and respond to the incoming signals accordingly. In this project we plan to study ErbB3, which belongs to the ErbB family of four receptors mediating normal cell growth, differentiation, development and cell death. The family members can interact with each other and form pairs, either between two different type of receptors (heterodimers) or between the same type of receptors (homodimers). The different pairings can lead to the activation of various signaling molecules and pathways. ErbB3 in particular forms heterodimers with other family
receptors and initiates a signaling pathway which prevents programmed cell death. Defective ErbB receptors have been found in several cancer types, but the role of ErbB3 in cancer has been recognized only recently. Here we aim to reveal the mechanisms governing the dimer formation and the cell signaling that follows. The results of the project will not only contribute to a better understanding of signaling in general, but also set a foundation for novel therapeutic applications for cancer.


<h2> Publications </h2>
{% for post in site.publications reversed %}
  {% if post.authors contains 'Danai Laskaratou' %}
    {% include archive-single-pub.html %}
  {% endif %}
{% endfor %}
