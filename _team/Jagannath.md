---
title: "Jagannath Satpathy"
collection: team
header:
  teaser: Jagannath.jpg
tags: phd
tagline: OptoMat project <br> co-promotor
date: 2022-09-01
subject: "Optical binding of nanoparticles outside the photon beam"
email: jagannath.satpathy@kuleuven.be
sidebar:
  nav: "Team"
author_profile: false
---

<p align= "justify">
In this project, we will investigate the unexplored phenomenon of optical binding outside of the irradiated area, which has a unique potential to develop sub-millimeter-sized optical matter. Our initial working hypothesis considers that the NPs are optically bound outside the focal spot by the back-scattered light and multi-channel light scattering, forming a dynamic optical binding network. We will explore the different experimental conditions, which yield optical binding outside the irradiated area, from both optical (e.g., laser beam mode pattern, laser polarization, number of laser beams, etc.) and material (e.g., size, shape, metallic vs dielectric vs hybrid materials, surface decoration, etc.) viewpoints. Considering that optical binding is a 3D phenomenon, we will study the system by single-particle tracking using a recently home-built multiplane widefield microscope, which records a volumetric image of 50x50x4 mm3. Moreover considering the recent advances in liquid-phase electron microscopy, we will simultaneously develop the technology to couple an optical tweezer to a scanning electron microscope as well as develop the corresponding data analysis methods. Indeed, this will be a key development in the optical trapping field, yielding complementary information to the one obtained using optical microscopy (e.g., potential better accuracy, structural order, etc). With the obtained results, we will develop qualitative/quantitative models on optical binding outside the irradiated area at interfaces, where not only optical forces are important, but also the so far unexplored hydrodynamic effects will play a critical role when a large number of NPs are involved. The foreseen results will pave the way for understanding the light-induced colloidal assembly, crystallization, and organization of templates for biological and colloidal sciences as well as will be used to generate novel submillimetre sized optical-mater assemblies, which could not be obtained by the current state of the art procedures.

<h2> Publications </h2>
{% for post in site.publications reversed %}
  {% if post.authors contains 'Haoxiang Zhang' %}
    {% include archive-single-pub.html %}
  {% endif %}
{% endfor %}
