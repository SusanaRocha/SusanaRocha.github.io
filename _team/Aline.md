---
title: "Aline Acke"
collection: team
header:
  teaser: aline.jpg
tags: Alumni
tagline: FWO fellowship <br> co-promotor
date: 2017-10-01
subject: "Extending the use of expansion microscopy as a tool to study an array of biological questions at the nanoscale: From proteins to viruses"
prom: Prof. Johan Hofkens
email: aline.acke@kuleuven.be
---
<p align= "justify">

In eukaryotic cells, the organization of chromatin structures is orchestrated by epigenetic mechanisms like chromatin-regulating proteins and play a pivotal role in gene expression and cell development. Aberrations in the system can not only be linked to physical and developmental disorders but can often lead to cancer development due to their active role in gene regulation. Therefore, the study of these proteins and their interaction with epigenetic marks could be of interest for epigenetic drug development and its application in cancer therapeutics. Typically, this information will be obtained through ChIP-Seq studies but spatial information will no longer be retained. Therefore, a different approach is investigated to study these kind of interactions through a combination of super resolution imaging, colocalization analysis and immunostaining of both the chromatin binding protein and an epigenetic mark. Since we aimed for a straightforward method, imaging was performed with expansion microscopy which is a fairly novel technique in the field of fluorescence microscopy. By infusing biological samples with suitable monomers, a super-absorbent polymer can be formed throughout the sample, which can be expanded and produce a perfectly transparent matrix, to which the biomolecules of interest are crosslinked such that their original geometry is preserved. This allows for imaging fundamental biomolecules in samples of various origin, at resolutions exceeding the diffraction limit on diffraction limited microscopes while also retaining spatial information. In the future this method could not only be used for epigenetic studies but also possibly function as a tool for drug discovery when working with small molecule inhibitors or to study interactions between viral pathogens, such as HIV, and host cellular pathways and mechanisms.
</p>

<p align= "justify">
<h2> Publications </h2>
{% for post in site.publications reversed %}
  {% if post.authors contains "Aline Acke" %}
    {% include archive-single-pub.html %}
  {% endif %}
{% endfor %}
