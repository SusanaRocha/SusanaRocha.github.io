---
title: "Boris Louis"
collection: team
header:
  teaser: boris.jpg
tags: post-doc
tagline: FWO fellowship <br> co-promotor
date: 2023-01-01
subject: "Optical binding of nanoparticles outside the photon beam: creation of primeval optical matter"
prom: Prof. Johan Hofkens
email: boris.louis@kuleuven.be
sidebar:
  nav: "Team"
author_profile: false
---
<p align= "justify">
Since the pioneering work of Ashkin in 1986, optical trapping has been used in various research fields (e.g., biology, chemistry, physics, and material sciences) for three-dimensional trapping and manipulation of micro- and nano-scale objects (e.g., nanoparticles (NPs), live cells, proteins, DNA, or small molecules). When trapping at an interface, all the optical forces (gradient, scattering and absorption) contribute to trapping the objects. As a result, so-called “dynamic evolving assemblies” have been recently reported using different types of nano- and micro-objects. These assemblies can gather more than hundreds of objects outside the irradiated area, which can only be explained by an expansion of the optical potential, most likely through multiple scattering processes and optical binding. In this project, we will further investigate the unexplored optical binding outside of the irradiated area, which has a unique potential to develop sub-millimetre-sized optical matter. Our initial working hypothesis considers that the NPs are optically bound outside the focal spot by the back-scattered light and multi-channel light scattering, forming a dynamic optical binding network. We will explore the different experimental conditions which yield optical binding outside the irradiated area, from both optical (e.g., laser beam mode, pattern, polarization...) and material (e.g., size, shape, metallic vs dielectric vs hybrid materials, surface decoration, etc.) points of view.

<h2> Publications </h2>
{% for post in site.publications reversed %}
  {% if post.authors contains 'Boris Louis' %}
    {% include archive-single-pub.html %}
  {% endif %}
{% endfor %}
