---
title: "Pierre Cybulski"
collection: team
header:
  teaser: Pierre.jpg
tags: Alumni
tagline: Marie-Curie ITN <br> promotor
date: 2020-07-01
prom: SuperCol (Marie-Curie Innovative Training Network)
subject: "Tracking the Biological Fate of Functional Nanoparticles Using Fluorescence Microscopy"
email: pierre.cybulski@kuleuven.be
sidebar:
  nav: "Team"
author_profile: false
---
<p align= "justify">
The use of nanotechnology in cancer therapy has attracted growing attention over the past decade. Many drug nanocarriers offering considerable advantages over conventional chemotherapy have been developed. Although binding strength and selectivity of nanocarriers with cell membranes can be controlled and has been investigated, the selective interaction with membrane receptors in e.g. drug delivery builds upon a sequence of steps, ranging from cellular uptake to apoptosis. Particles designed for this application, need to be evaluated for each and all of these using a realistic model.<br>
Promising results in vitro can often not be translated in vivo. This is linked to the in vitro testing of nanocarriers in 2D cultures, which can hardly mimic the complex network of a 3D tumor. To form a bridge between the in vitro and in vivo, it is crucial to test the performance of drug nanocarriers in advanced 3D cell models. The models involved in this project include multicellular tumor spheroids and cancer organoids grown using cells from tumor biopsies. They will be used to track and evaluate the biological fate of functional colloids using advanced fluorescence microscopy. This will allow us to establish the selectivity of the particle-cell interactions, the cellular uptake, endosomal escape, and intracellular drug release.

<h2> Publications </h2>
{% for post in site.publications reversed %}
  {% if post.authors contains 'Pierre Cybulski' %}
    {% include archive-single-pub.html %}
  {% endif %}
{% endfor %}
