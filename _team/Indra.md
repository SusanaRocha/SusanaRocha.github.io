---
title: "Indra van Zundert"
collection: team
header:
  teaser: indra.png
tags: post-doc
tagline: FWO fellowship <br> promotor
date: 2024-09-01
subject: "From Design to Action: DNA Nanostructures in siRNA Delivery"
prom:
email: indra.vanzundert@kuleuven.be
sidebar:
  nav: "Team"
author_profile: false
---
<p align= "justify">
The versatile properties of DNA nanostructures have garnered attention in the field of nanotechnology, presenting opportunities for designing nanoscale architectures that hold great promise in biological applications. Here, we aim to explore the potential of DNA nanostructures in siRNA delivery for anticancer treatment. While siRNA holds promise for selectively silencing oncogenes, its clinical translation faces obstacles. Naked siRNAs are vulnerable to nucleases, prone to immunotoxicity, and swiftly cleared, hampering them to reach specific target cells. Common delivery systems like viral vectors pose limitations due to immunogenicity and complex production, while lipid or polymeric nanoparticles lack diverse clinical translation. In this project, I will optimize siRNA-DNA nanocomplexes by systematically tailoring parameters like size, shape, charge, and surface modifications. This customization aims to enhance stability, cellular uptake, and selective siRNA release. Unique DNA-labelling strategies will be used to follow the fate of the nanostructures within biological samples. Our evaluation will encompass simple 2D cell monolayers and advanced 3D cancer model systems, ranging from spheroids to patient-derived organoids. The outcomes of this project are expected to provide crucial insights into the biological fate of siRNA-DNA nanocomplexes and establish a foundation for their clinical application in gene therapy.

<h2> Publications </h2>
{% for post in site.publications reversed %}
  {% if post.authors contains 'Indra Van Zundert' %}
    {% include archive-single-pub.html %}
  {% endif %}
{% endfor %}
