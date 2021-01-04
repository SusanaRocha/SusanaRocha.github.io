---
title: "Marisa Vanheusden"
collection: team
header:
  teaser: marisa.jpeg
tags: phd
tagline: FWO-SB fellowship <br> co-promotor
date: 2018-01-01
subject: "In situ, spatially resolved 'omits' at the single cell level, unlocked through expansion microscopy"
prom: Prof. Johan Hofkens
email: marisa.vanheusden@kuleuven.be
---
<p align= "justify">
Cells are fundamental functional unit in all forms of life and subcellular processes are at the origin of most, if not all, disease processes. Proper cellular function requires the carefully coordinated action of numerous biomolecular actors. Organelles and multi-protein structures that compose the molecular machinery are often much smaller than ~200 nm. As a result, direct visualisation and study of these phenomena, e.g. through microscopy imaging is challenging.
Expansion microscopy (ExM) addresses this issue in an elegant and cost-effective way: By embedding cells or whole tissues in a suitable super-absorbent polymer their size can be be expanded, laying bare their subcellular structure.
The versatility of ExM allows it to be combined with state-of the art methods in single cell analysis of genetic information in an effort to truly advance our understanding the high level function of complex organs such as the brain, or to harness the existence of cell heterogeneity in pathologies such as cancer.
To achieve this goal, microscopy methods for3D visualisation of large samples will be combined with conjugation and labelling strategies to visualise the transcriptome of individual cells in complex tissues.

<h2> Publications </h2>
{% for post in site.publications reversed %}
  {% if post.authors contains 'Marisa Vanheusden' %}
    {% include archive-single-pub.html %}
  {% endif %}
{% endfor %}
