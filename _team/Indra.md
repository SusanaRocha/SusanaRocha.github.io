---
title: "Indra van Zundert"
collection: team
header:
  teaser: indra.png
tags: phd
tagline: FWO fellowship <br> co-promotor
date: 2017-10-01
subject: "Next-generation cancer therapy: gene editing meets nanotechnology"
prom: Prof. Hiroshi Uji-i (promotor)
email: indra.vanzundert@kuleuven.be
---
<p align= "justify">
Cancer is one of the major causes of death in our society. The anti-cancer drugs currently used in chemotherapy produce several side effects and, although fatal for almost all cells in a tumor, a small percentage of cells appear to resist the treatment. Therefore, it is urgent to design new therapies that specifically target these cells while causing no harm to healthy tissue. The resistance to multiple drugs is linked to the presence of specific molecules at the cellular plasma membrane, that actively pump out chemical drugs (efflux pumps). Multi-drug resistant cells are suggested to be the main cause of treatment failure and relapse.
In recent years, nanoparticle-based drug delivery platforms have emerged as the next-generation of pharmaceutical compounds. The surface of the nanoparticles can be modified to target specific cells, while the core of the particle can be loaded with anti-cancer drugs. In this project we want to go one step further and develop multifunctional nanoparticles to attack multi-drug resistant cells. In addition to loading the particles with anti-cancer drug(s) and targeting them to cancer cells, we will supply them with tools to reduce the amount of efflux pumps at the cell membrane. This can be achieved using cutting-edge gene editing methodologies. The versatility of the resulting nanoparticles can be infinite.

<h2> Publications </h2>
{% for post in site.publications reversed %}
  {% if post.authors contains 'Indra Van Zundert' %}
    {% include archive-single-pub.html %}
  {% endif %}
{% endfor %}
