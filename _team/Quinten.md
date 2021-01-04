---
title: "Quinten Coucke"
collection: team
header:
  teaser: Quinten.png
tags: phd
tagline: FLOF grant <br> co-promotor
date: 2018-10-01
subject: "Imaging the forces driving cancer progression"
prom: Prof. Johan Hofkens
email: "quinten.coucke@kuleuven.be"
---

<p align= "justify">
Mechanical forces play an undisputed elementary role in the interactions between cells and the surrounding extracellular matrix (ECM). Not only are these forces essential for the cell migratory behavior, they also influence proliferation (including tumor growth) and differentiation. These forces are transferred across focal adhesions (FAs) which connect ECM and cell skeleton through patches of activated integrin proteins. Since the origin of exerted cellular forces lies in these FAs, they are the ideal starting point for characterization of mechanotransduction pathways.
Consequently, studying how the properties of the ECM affect the cellular forces is key in understanding how cells connect to their environment and alter their behavior appropriately.  While the scientific field of cellular mechanosensation has been studied for years, recent developments in imaging techniques and force sensor development enable us to dig deeper.
A home-built confocal Fluorescence Lifetime Imaging Microscopy (FLIM) microscope is used to measure Förster Resonance Energy Transfer (FRET) in FAs.

One of the hallmarks of cancer is the invasion into new tissues, i.e., when some pioneer mutant cells leave the tumor mass and start new colonies in other areas of the body. These distant settlements of cancer cells are named metastases and cause the majority of cancer related deaths. The involvement of ECM and cancer associated fibroblasts (CAFs) in metastasis is only now coming into the light, with accumulating evidence of the crucial role of biomechanics in this process. In this project new biomimetic polymers and state-of- the-art microscopic methods will be combined to study the interplay between the mechanical properties of the ECM and behavior of CAFs. A deep comprehension of how physical forces affect the tumour microenvironment will help scientists to develop novel diagnostic and therapeutic tools for more early detection and delayed cancer progression.

<h2> Publications </h2>
{% for post in site.publications reversed %}
  {% if post.authors contains 'Quinten Coucke' %}
    {% include archive-single-pub.html %}
  {% endif %}
{% endfor %}
