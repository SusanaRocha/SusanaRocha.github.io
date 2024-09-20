---
title: "Samet Aytekin"
collection: team
header:
  teaser: samet.png
tags: phd
subject: "Cells under pressure: the role of mechanical cues on cellular force transmission"
tagline: FWO fellowship <br> promotor
date: 2021-04-01
email: samet.aytekin@kuleuven.be
sidebar:
  nav: "Team"
author_profile: false
---

<p align= "justify">
Mechanobiology is the interdisciplinary study of how mechanical forces influence the structure, function, and behavior of living cells and tissues. A key focus in this field is mechanotransduction, where cells sense and respond to forces from their environment. Focal adhesions are the major structural elements of mechanotransduction, acting as molecular machinery connecting the cell to its surroundings and transmitting forces in both directions. Understanding the mechanical forces over focal adhesions is crucial for unraveling how cells behave in different environments and contribute to the overall function of tissues and the development of pathological conditions.
In this project, we focus on investigating the cellular and molecular forces that drive mechanobiology, particularly within the lung fibroblasts. By utilizing advanced tools such as FRET-based molecular tension probes (TSMods), DNA-force sensors, and traction force microscopy (TFM), aim to visualize and measure the forces exerted at the intra- and extracellular level. The final aim of this research is to compare the mechanobiology of normal and activated fibroblasts in both healthy and fibrotic lung tissues. This approach will provide insight into how mechanical forces contribute to tissue homeostasis and fibrosis, with potential implications for understanding and treating lung diseases.
<br>

{% include base_path %}

<h2> Publications </h2>
{% for post in site.publications reversed %}
  {% if post.authors contains 'Samet Aytekin' %}
    {% include archive-single-pub.html %}
  {% endif %}
{% endfor %}
