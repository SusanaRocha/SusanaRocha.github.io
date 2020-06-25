---
title: "Kaizheng Liu (Max)"
collection: team
header:
  teaser: Profile_Max.jpg
tags: post-doc
tagline:  
date: 2020-02-15
subject: "Feel the force: cell adhesion in 3D biomimetic hydrogels"
prom:
---
<p align= "justify">
Recent developments in mechanobiology have revealed that mechanosensing is an important regulator of cell behavior. In healthy tissues, mechanical homeostasis dominates the interconnected intra- and extra-cellular stress fibers by cell adhesion to the extracellular matrix (ECM). Focal adhesions are one of the core players in this process as they connect the cytoskeleton to the ECM, transmitting mechanical forces and regulatory signals from the matrix to the nucleus.
To direct (stem) cell fate in 3D culturing experiments, synthetic hydrogels with intrinsically high tunability should make ideal matrices, however, they rarely mimic the rich mechanical properties of natural ECM materials. Recently, synthetic polyisocyanopeptide (PIC)-based hydrogels were developed by Rowan/Kouwer's lab. This is the first fully synthetic material that exhibits strain-stiffening properties comparable to what is found in nature. Moreover, as it is fully synthetic, the actual material stiffness, pore size, ligand density, and ligand identity can be tightly controlled independently from each other.
Because of its high structural and mechanical similarity to natural gels, this material allows us to study the influence of biochemical and mechanical properties of the ECM on cell behavior in a physiologically relevant and systematic manner. My research aims to unveil how ECM properties regulate cell-matrix interactions at the nano-scale. The results will have a high impact on tissue engineering practices and the development of new materials as artificial ECM.

<h2> Publications </h2>
{% for post in site.publications reversed %}
  {% if post.authors contains 'Kaizheng Liu' %}
    {% include archive-single-pub.html %}
  {% endif %}
{% endfor %}
