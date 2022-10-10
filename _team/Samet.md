---
title: "Samet Aytekin"
collection: team
header:
  teaser: samet.png
tags: phd
subject: "Cells under pressure: the role of mechanical cues on cellular force transmission"
tagline: FWO fellowship <br> promotor
date: 2021-04-01
email: samet.aytekin@kuleuven.be
---

<p align= "justify">
Cells are known to probe their environment by applying force to it. As a result, cells adapt their behaviour to the properties of extracellular matrix (ECM) and the forces applied to the system. An increasing number of reports shows that mechanical cues provide additional inputs into molecular signaling networks, which in turn regulate cell adhesion and ECM remodeling. Despite the growing interest in the field, understanding mechanotransduction at a cellular level is hindered by a lack of suitable model systems and characterization methods. In this project, we will use synthetic fibrous hydrogels to systematically evaluate the relation between matrix mechanics and cellular forces. FRET-based force sensors will be used to quantify cell-matrix and cell-cell forces in 3D. To mimic the physiologic conditions, we will develop a custom microfluidic device for control of both interstitial flow and compression forces. These tools will be used to investigate the influence of mechanical cues on force transduction in cancer associated fibroblasts (CAFs) in 3D cell models. However, this combination of technologies will lay the groundwork for a multitude of other mechanobiology studies.

{% include base_path %}

<h2> Publications </h2>
{% for post in site.publications reversed %}
  {% if post.authors contains 'Samet Aytekin' %}
    {% include archive-single-pub.html %}
  {% endif %}
{% endfor %}
