---
title: "Maria Bravo"
collection: team
header:
  teaser: Maria.jpg
tags: phd
subject: " Advanced cell models and multifunctional nanomaterials for light-mediated cancer therapies"
prom: Global PhD Partnership (Melbourne University)
tagline: Global PhD Partnerships <br> promotor
date: 2021-10-01
email: maria.bravo@student.kuleuven.be
---
<p align= "justify">

Despite significant advances in cancer therapy over the past decades, cancer remains the number one cause of death worldwide. In the last years there has been increasing interest in the development of new treatment modalities with reduced side effects for difficult-to-cure cancers. A prominent example is Photothermal Therapy (PTT), designed to selectively kill cancerous tissue in the body through localized, light-induced thermal stress. The development of nanomaterials marks a significant step forward in photothermal therapy of cancers.
Nanomaterials smaller than 200 nm accumulate in the tumour tissue and exhibit strong absorption in the near-infrared range, making them effective photothermal transducers with cancer targeting capabilities. Nanomaterial-mediated PTT has reached clinical trials but knowledge concerning the efficiency, mechanism and toxicity of this therapy remains limited. This project aims to unravel the mechanisms involved in nanomaterial-mediated PTT, using microscopy to monitor intracellular temperature and cell death pathways simultaneously. To mimic the physiological features present in solid tumors most accurately, multicellular tumor spheroids will be used.
The fabrication and characterisation of novel nanomaterials will also be a major part of this project, targeting nanosensors for mapping intracellular temperature, and gold-based stimuli-responsive nanocrystals with enhanced solid tumor penetration and efficient photothermal transduction for long-wavelength light. The information obtained thereby will be crucial for the rational design of next-generation nanomaterials for targeted light-mediated cancer therapies.
However, as for any novel cancer therapy, before its wide application at the clinical level, it is desired to have a complete understanding of the efficiency, mechanism and toxicity of nanomaterial-based PTT. In this project this will be achieved by developing new nanomaterials, to both induce and probe light-induced hyperthermia. A full understanding of the mechanism behind nanomaterial-mediated PTT requires monitoring the intracellular temperature and cell death pathways during light irradiation. Only a systematic investigation will allow proper adjustment of treatment parameters to achieve the best therapeutic efficiency in solid tumors.

<h2> Publications </h2>
{% for post in site.publications reversed %}
  {% if post.authors contains 'Maria Bravo' %}
    {% include archive-single-pub.html %}
  {% endif %}
{% endfor %}
