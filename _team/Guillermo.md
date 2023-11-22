---
title: "Guillermo Solis"
collection: team
header:
  teaser: guille2.png
tags: post-doc
tagline: FWO fellowship <br> promotor
date: 2023-10-01
subject: "Oncoproteomics and 3D culture as tools to understand and prevent CRC metastasis"
prom:
email: guillermo.solisfernandez@kuleuven.be
---
Cancer metastasis is the main cause of cancer associated death, the dissemination and spreading of tumoral cells from its original niche makes treatment and eradication of the malignancy almost impossible. We want to gain further insights into colorectal cancer (CRC) metastasis and this way find new diagnostic tools that allow for the early detection of CRC tumours before they have the chance to colonize other tissues. We will evaluate the diagnostic potential of proteins identified as upregulated in CRC metastatic cell lines during my PhD. We will evaluate their diagnostic and screening capacity using sera of control and CRC patients as well as patient tissue microarrays. In parallel, to understand the role of these markers in the progression and onset of CRC we will edit and label them to follow their activity real-time in living cells.
Additionally, we will study the role of the mechanical environment around CRC tumour cells in the progression of the disease and try to understand how cells sense and are affected by mechanical cues. Furthermore, we will also characterize at the proteomic level CRC cells differentiated in 3D to discover new possible markers that might have been overlooked so far because of the usage of 2D culture conditions. Taking advantage of the tuneable and biomimetic properties of synthetic hydrogels, we will investigate how the mechanical and chemical cues of the matrix can influence metastasis.

<h2> Publications </h2>
{% for post in site.publications reversed %}
  {% if post.authors contains 'Solis' %}
    {% include archive-single-pub.html %}
  {% endif %}
{% endfor %}
