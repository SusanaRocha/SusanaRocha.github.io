---
title: "Ana Cunha"
collection: team
header:
  teaser: anacunha.jpg
tags: Alumni
subject: "Cystic fibrosis is not only an ion channel defect - investigation of the role of senescence in chronic inflammation as a novel therapeutic strategy"
prom: Prof. Zeger Debyser  (promotor)
tagline: co-promotor
date: 2021-01-01
email: analucia.dasilvacunha@kuleuven.be
sidebar:
  nav: "Team"
author_profile: false
---

<p align= "justify">
Cystic Fibrosis (CF) is a monogenic, multi-systemic disease that mainly affects the airways and is caused by mutations in the CF Transmembrane Conductance Regulator (CFTR) gene. Currently, treatment relies on symptomatic therapies and CFTR modulators, small molecules rescuing the mutant protein, but infection and inflammation in the lung persist even while on treatment, requiring alternative therapeutic options to address these remaining CF defects. Inflammation results from the interplay of different cell types and current models do not reflect the complexity of this process. I propose to address outstanding questions in the field of lung disease in CF. Markers of senescence have been reported in CF lung epithelia, but it remains unclear whether this is a cause or consequence of CF lung pathology. In fact, the chronic inflammatory state seen in the CF lung closely resembles the SASP (Senescence- Associated Secretory Phenotype). It is not known yet whether CF and senescence are related or if what is seen in the lung is a result of accelerated ageing. In this project, I propose to study the causal or consequential sequence of events between senescence and CF. Moreover, I will explore the role of the immune system, in particular neutrophils, on the onset of a senescent phenotype in the airways. I also propose the combination of CFTR modulators and senolytics (drugs capable of selectively killing senescent cells) as a promising avenue for the treatment of CF.
{% include base_path %}

<h2> Publications </h2>
{% for post in site.publications reversed %}
  {% if post.authors contains 'Ana Cunha' %}
    {% include archive-single-pub.html %}
  {% endif %}
{% endfor %}
