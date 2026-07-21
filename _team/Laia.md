---
title: "Laia Torrella Adriaensen"
collection: team
header:
  teaser: Laia.jpg
tags: phd
subject: "Antimicrobial resistance analysis by mapping optical signatures"
tagline: FLOF grant <br>co-promotor
date: 2026-01-01
email: laia.torrellaadriaensen@kuleuven.be
sidebar:
  nav: "Team"
author_profile: false
---
<p align= "justify">

Antimicrobial resistance (AMR) is a growing global health crisis, complicating infection treatment and increasing medical costs and mortality. Current AMR detection methods, such as PCR and sequencing, face limitations in efficiency, cost, and scalability. This project aims to use Short Range Optical Mapping (SROM) to overcome these challenges and develop high-resolution genomic barcodes for AMR genes, enabling rapid and precise detection of resistant bacteria. By combining multicolor labeling, enzymatic sequence-specific DNA tagging, and super-resolution microscopy, we will enhance DNA mapping to identify structural variations at gene-level resolution. This approach will also integrate machine learning and clinical database annotation to correlate optical signatures with specific resistance markers and genomic structures. Ultimately, the developed framework will advance high-throughput AMR analysis, improving resistance monitoring and characterization in clinical microbiology.<br>


<h2> Publications </h2>
{% for post in site.publications reversed %}
  {% if post.authors contains 'Laia Torrella Adriaensen' %}
    {% include archive-single-pub.html %}
  {% endif %}
{% endfor %}
