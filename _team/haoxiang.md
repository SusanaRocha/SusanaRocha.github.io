---
title: "Haoxiang Zhang"
collection: team
header:
  teaser:Haoxiang.png
tags: phd
tagline: CSC fellowship <br> promotor
date: 2022-10-01
subject: "DNA-functionalized fibrous hydrogels to quantify cell-matrix interactions"
email: haoxiang.zhang@kuleuven.be
---

<p align= "justify">
Cells physically interact with the extracellular matrix (ECM) through cellular forces. These forces are involved in matrix remodeling, cell‑cell mechanical communication, and tissue mechanics, further guiding cell migration and development. Several reports indicate that cells can physically remodel ECM through fiber alignment and densification, creating a mechanically specific micro-niche to suit their needs. At the same time, the forces applied by the cell propagate a long distance through the matrix, allowing cell–cell mechanical communication.
Fiber remodeling and long-range force propagation are mostly observed in biological ECMs, namely collagen, and fibrin gels, due to the nonlinear mechanics and fibrous structure of these materials. These phenomena are therefore difficult to mimic using synthetic hydrogels. In this project we will use a fully synthetic hydrogel, that mimics biological gels in nearly all aspects, particularly the fibrous architecture and the strong nonlinear mechanical response. The developed polyisocyanides (PIC) gels are suitable for culturing many different cell types in 3D, and show strain-stiffening behaviour.
The main goal of this project is to develop a toolbox to investigate the role of cellular forces and force propagation in cell behavior. In more detail, we will investigate how cellular forces affect the matrix, how far do they propagate within the matrix, and how are forces transmitted from the matrix to distance cells, with subcellular resolution, in 3D. We will used DNA-functionalized PIC gels to quantify cellular traction forces in mechano-sensitive hydrogels, investigate fiber remodeling at the nanometer level and investigate how cellular forces are transmitted through the matrix.
The smart DNA-PIC gels developed in this project will provide an essential tool to understand the role of cell-induced mechanical cues in cancer progression. Importantly, the toolbox developed within this project will be useful to investigate a wide array of biological diseases and processes where biomechanics play an important role.

<h2> Publications </h2>
{% for post in site.publications reversed %}
  {% if post.authors contains 'Haoxiang Zhang' %}
    {% include archive-single-pub.html %}
  {% endif %}
{% endfor %}
