---
title: "Samantha Zaman"
collection: team
header:
  teaser: samantha.png
tags: phd
tagline: Global PhD Partnerships <br> promotor
date: 2022-03-01
subject: "Advanced cell models and multifunctional nanomaterials for light-mediated cancer therapies"
email: "samanthaz@student.unimelb.edu.au"
sidebar:
  nav: "Team"
author_profile: false
---

<p align= "justify">
Despite significant advances in cancer therapy over the past decades, cancer remains the number one cause of death worldwide. Surgery, chemotherapy and radiation therapy often fall short due to the incomplete removal of cancerous tissue, the development of drug resistance or non-specific therapy. Light mediated cancer therapies offer a more targeted approach via localised photo-thermal and photo-chemical cell destruction. A prominent example is Photodynamic Therapy (PDT), designed to selectively kill cancerous tissue through localized, light-induced oxidative stress. The development of nanomaterials marks a significant step forward in photodynamic therapy of cancers. Nanomaterials smaller than 200nm accumulate in the tumour tissue and exhibit strong absorption in the near-infrared range, making them effective photo-generators of reactive oxygen species that induce cell death. Nanomaterial-mediated PDT may improve current clinical PDT employing molecular photo-sensitizers, but the relationship between nanoparticle size and surface chemistry, and PDT mechanism and efficiency remains an open question. This project aims to answer this question by using microscopy to monitor singlet oxygen generation and cell death pathways simultaneously. The first part of this project will focus on the fabrication and characterisation of lanthanide nanocrystals with enhanced solid tumour penetration and efficient singlet oxygen sensitization using long wavelength light. These synthesised nanoparticles will then be used in multicellular tumour spheroids which most accurately mimic the physiological features of solid tumours. Finally near-infrared camera technology will be employed to directly map intracellular singlet oxygen via its luminescence. The information obtained thereby will be crucial for the rational design of next-generation nanomaterials for targeted light-mediated cancer therapies.

<h2> Publications </h2>
{% for post in site.publications reversed %}
  {% if post.authors contains 'Samantha Zaman' %}
    {% include archive-single-pub.html %}
  {% endif %}
{% endfor %}
