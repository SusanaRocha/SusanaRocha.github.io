---
layout: archive
title: "Research Team"
permalink: /team/
author_profile: true
---

We are always looking for talented and enthusiastic masters, PhD students and post-doctoral researchers. <br> Please contact Prof. Rocha (<a href="mailto:{{ author.email }}"><span style="color:gray">email</span>) for inquiries.
<br>
<hr-bold>
<h2>Principal Investigator</h2>
<hr><br>
<div class="grid">
<div class="wrapper">
  {% for post in site.team %}
    {% if post.tags contains 'PI' %}
      {% include archive-single-proj.html type="grid" %}
    {% endif %}
  {% endfor %}
</div>
</div>


<hr-bold>
<h2>Post-doctoral researchers</h2>
<hr><br>

<div class="grid">
<div class="wrapper">
  {% for post in site.team reversed %}
    {% if post.tags contains 'post-doc' %}
    {% if post.date < site.time %}
      {% include archive-single-proj.html type="grid" %}
    {% endif %}
    {% endif %}
  {% endfor %}
</div>
</div>

<hr-bold>
<h2>PhD students</h2>
<hr><br>
<div class="grid">
<div class="wrapper">
  {% for post in site.team reversed  %}
    {% if post.tags contains 'phd' %}
    {% if post.date < site.time %}
      {% include archive-single-proj.html type="grid" %}
    {% endif %}
    {% endif %}
  {% endfor %}
</div>
</div>

<hr-bold>
<h2>Master students</h2>
<hr><br>
<div class="grid">
<div class="wrapper">
  {% for post in site.team reversed %}
    {% if post.tags contains 'master' %}
      {% include archive-single-proj.html type="grid" %}
    {% endif %}
  {% endfor %}
</div>
</div>

<hr-bold>
<h2>Internship & Exchange students</h2>
<hr><br>
<div class="grid">
<div class="wrapper">
  {% for post in site.team reversed %}
    {% if post.tags contains 'inter' %}
      {% include archive-single-proj.html type="grid" %}
    {% endif %}
  {% endfor %}
</div>
</div>


<hr-bold>
<h2>Honorary members of the team</h2>
<hr><br>
<div class="grid">
<div class="wrapper">
  {% for post in site.team reversed %}
    {% if post.tags contains 'Honorary' %}
      {% include archive-single-proj.html type="grid" %}
    {% endif %}
  {% endfor %}
</div>
</div>

<hr-bold>
<h2>Alumni</h2>
<hr><br>
<b>Dr. Johannes Vandaele</b>, <i> PhD student </i><br>
Johannes finished his PhD entitled <i> Structural and thermo-mechanical characterization of new biomimetic materials </i> in January 2023 (co-promotor, <a href="{{site.github.url}}/team/Johannes"><span style="color:gray">link to archived page</span></a>)<br><br>
<b>Dr. Guillermo Solis</b>, <i> PhD student </i><br>
Guillermofinished his PhD entitled <i> Imaging and proteomics-based analysis of colorectal cancer metastasis </i> in September 2022 (co-promotor, <a href="{{site.github.url}}/team/Guillermo"><span style="color:gray">link to archived page</span></a>)<br><br>
<b>Astha Tiwari</b>, <i> Master student </i><br>
Astha finished her master thesis on <i>'Investigation of clathrin- mediated endocytosis in cancer metastasis using confocal and super-resolution microscopy'</i> in June 2022 (promotor). <br><br>
<b>Lars Fever</b>, <i> Master student </i><br>
Lars finished his internship on <i>'Effect of substrate stiffness on the cellular uptake of nanoparticles'</i> in June 2022 (promotor). <br><br>
<b>Fábio Gonçalves</b>, <i> Master student </i><br>
Fábio finished his Erasmus + internship on <i>'Investigating the Hofmeister Effect on Polyisocyanopeptide Gels'</i> in June 2022 (co-promotor). <br><br>
<b>Dr. Indra Van Zundert</b>, <i> PhD student </i><br>
Indra finished her PhD entitled <i> Bringing Drug Delivery Systems into the Third Dimension </i> in June 2022 (co-promotor, <a href="{{site.github.url}}/team/Indra"><span style="color:gray">link to archived page</span></a>)<br><br><b>
Dr. Aline Acke</b>, <i> PhD student </i><br>
Aline finished her PhD entitled <i> Studying an Array of Biological Questions at the Nanoscale with Expansion Microscopy:
From cells to viruses </i> in February 2022 (co-promotor, <a href="{{site.github.url}}/team/Aline"><span style="color:gray">link to archived page</span></a>)<br><br>
<b>Dr. Marisa Vanheusden</b>, <i> PhD student </i><br>
Marisa finished her PhD entitled <i> Multiplexing spatially resolved omics with increased resolution: Development of an expansion microscopy platform </i> in December 2021 (co-promotor, <a href="{{site.github.url}}/team/marisa"><span style="color:gray">link to archived page</span></a>)<br><br>
<b>Dr. Laurens D'Huys</b>, <i> PhD student </i><br>
Laurens finished his PhD entitled <i> Optical DNA Mapping: The Super-Resolved Genomic Barcode</i> in September 2021(co-promotor, <a href="{{site.github.url}}/team/Laurens"><span style="color:gray">link to archived page</span></a>)<br><br>
<b>Dr. Danai Laskaratou</b>, <i> PhD student </i><br>
Danai finished her PhD entitled <i> Development of fluorescent protein-based strategies and microscopy techniques for cell signaling studies</i> in July 2021(co-promotor, <a href="{{site.github.url}}/team/Danai"><span style="color:gray">link to archived page</span></a>)<br><br>
<b>Dr. Monica Ricci</b>, <i> PhD student </i><br>
Monica finished her PhD entitled <i> Hands and Eyes on Single-cells: Silver Nanowire Endoscopy for Intracellular Delivery and Sensing</i> in January 2021(co-promotor, <a href="{{site.github.url}}/team/Monica"><span style="color:gray">link to archived page</span></a>)<br><br>
<b>Dr. Kaizheng Liu (Max)</b>, <i> Post-doctoral researcher Jan-Nov 2020 </i><br>
After a short research stay, Max join us to continue his work on the effect of non-linear mechanics on cell behaviour (<a href="{{site.github.url}}/team/Max"><span style="color:gray">link to archived page</span></a>)<br><br>
<b>Stéphanie Geerts</b>, <i> Master student </i><br>
Stéphanie finished her master thesis on <i>'The influence of the ECM on Cancer Associated Fibroblasts and cancer cell interplay'</i> in June 2021 (promotor). <br><br>
<b>Nele Philippens</b>, <i> Master student </i><br>
Nele finished her master thesis on <i>'Imaging and manipulation of the immunological synapse with polyisocyanopeptide polymers'</i> in June 2021 (promotor). <br><br>
<b>Laurens Kimps</b>, <i> Master student </i><br>
Laurens finished his master thesis on <i>'Quantifying the Förster resonance energy transfer of intracellular tension sensors for investigating mechanotransduction'</i> in June 2021 (co-promotor). <br><br>
<b>Maria Bravo</b>, <i> internship student Feb-Aug 2020 </i><br>
Maria joined our group as an Erasmus+ exchange student to work on the functionalization of nanoparticles for drug delivery. <br><br>
<b>Elfriede Heerwegh</b>, <i> Master student </i><br>
Elfriede finished her master thesis on <i>'The role of cancer associated fibroblasts in tumor invasion'</i> in June 2019 (promotor). <br><br>
<b>Dr. Herlinde Dekeersmaecker</b>, <i> PhD student </i><br>
Herlinde finished her PhD on <i>'Superresolution fluorescence microscopy based techniques for the study of signal transduction'</i> in February 2017 (co-promotor). <br><br>
