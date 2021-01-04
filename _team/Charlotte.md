---
title: "Charlotte Cresens"
collection: team
header:
  teaser: charlotte.png
tags: phd
tagline: FWO fellowship <br> promotor
date: 2020-07-01
subject: "Cancer cells on the move: the role of cellular adhesion complexes and microenvironment in metastasis"
email: charlotte.cresens@student.kuleuven.be
---
<p align= "justify">
In the 21st century, cancer is expected to grow into the leading cause of death in every country. The majority of cancer-associated deaths arise from cancer metastasis, a multistep-process whereby cancer cells adapt, break free from the primary tumor site and migrate to colonize other tissues.
Recent studies have shown the importance of the microenvironment surrounding the cells in the development and progression of cancer. For instance, the higher stiffness of the tumor microenvironment affects the migration speed of cancer cells and consequently influences their capacity to migrate during metastasis. However, information concerning the influence of the microenvironment on the regulation of cellular adhesion and migration is scarce.
In this project I will combine avant-garde gene-edited 3D colorectal cancer models, fluorescence microscopy methods with molecular resolution and advanced biomimetic hydrogels with tailored properties to unravel the mechanisms underlying the influence of the tumour microenvironment in cell adhesion and migration during cancer metastasis. I will focus on characterizing the structure, organization and trafficking of adhesion complexes, in cells with different metastatic potentials, cultured on or in synthetic matrices with different mechanical properties.
This project will lead to a better understanding of the role of cell adhesion in cancer cell migration and the influence of mechanical properties of the microenvironment on those processes.

<h2> Publications </h2>
{% for post in site.publications reversed %}
  {% if post.authors contains 'Charlotte Cresens' %}
    {% include archive-single-pub.html %}
  {% endif %}
{% endfor %}
