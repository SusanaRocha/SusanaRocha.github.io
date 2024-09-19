---
title: "Sandra Krzyzowska"
collection: team
header:
  teaser: sandra.png
tags: phd
tagline: co-promotor
date: 2023-03-01
subject: "Nanoparticles-mediated phototherapies in 3D cancer models"
email: sandra.krzyzowska@kuleuven.be
sidebar:
  nav: "Team"
author_profile: false
---

<p align= "justify">
In the 21st century, cancer is expected to grow into the leading cause of death in every country. Traditional therapies’ limitations, e.g. systemic toxicity, or invasiveness, underscore the need for more effective and selective therapeutic approaches. Phototherapies, such as photodynamic (PDT) and photothermal (PTT) have emerged as promising alternatives. Combining them could result in even more effective treatment, enabling the simultaneous generation of heat and reactive oxygen species. Plasmonic nanoparticles (NPs) can further enhance the efficacy and specificity of this therapy. Despite impressive results, high specificity, and efficiency in 2D cell cultures, they remain underused treatment in clinical trials, due to the inconsistent translation to in vivo studies. Advanced 3D cancer models enable the study of different interactions between NPs and tumor cells, their penetration through the extracellular matrix (ECM) and the signal propagation within 3D tumors. This study aims to investigate the use of plasmonic NPs in combined PDT-PTT therapy using advanced multicellular tumor spheroids. Studying the interactions between plasmonic NPs, light, and cancer cells in 3D models can help us understand the underlying mechanisms of these therapies, what affects the delivery of nanosystems and identify ways to optimize efficacy and minimise adverse effect. As such, it will contribute to our knowledge of cancer treatment and help improve clinical outcomes for cancer patients.

<h2> Publications </h2>
{% for post in site.publications reversed %}
  {% if post.authors contains 'Haoxiang Zhang' %}
    {% include archive-single-pub.html %}
  {% endif %}
{% endfor %}
