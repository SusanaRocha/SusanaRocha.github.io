---
title: "Yana Heyvaert"
collection: team
header:
  teaser: Yana.jpg
tags: phd
subject: "Nano-Enhanced Hydrogels for Probing Cellular Mechanotransduction"
prom: Global PhD Partnership (Melbourne University)
tagline: Global PhD Partnerships <br> promotor
date: 2025-02-14
email: yana.heyvaert@kuleuven.be
sidebar:
  nav: "Team"
author_profile: false
---
<p align= "justify">

Cells continuously interact with their microenvironment, the extracellular matrix (ECM), by sensing and responding to its mechanical properties. Through a process called mechanotransduction, cells can translate physical forces exerted by the ECM into biochemical signals. This interaction not only influences cellular behaviour, but also plays a pivotal role in regulating various biological processes and maintaining normal cellular function. This relationship is bidirectional; while cells can perceive mechanical signals from the ECM, they also actively remodel this matrix, adjusting the biomechanical environment by densifying and reorganising its fibrous components. This dynamic feedback loop between cells and the ECM is crucial in both physiological and pathological processes. While mechanotransduction is important in preserving tissue homeostasis, abnormal ECM remodelling can lead to tissue dysfunction, altered gene expression, and is associated with a variety of diseases like fibrosis and cancer. Despite its importance in tissue engineering, disease modelling, and regenerative medicine, the cell-ECM interplay remains poorly understood. This knowledge gap is largely attributed to the lack of precise tools to measure dynamic mechanical changes in the ECM at the micron and nanoscale. Therefore, a nanotechnology-based approach that recognises these changes is desired. <br>
This project aims to address this challenge by using both passive and active microrheology to investigate the mechanical changes cells induce in the ECM and vice versa. Our approach includes utilizing biomimetic materials designed to replicate various ECM properties, which will allow us to create controlled experimental environments. Moreover, we will leverage advanced nanoparticle technologies and cutting-edge microscopy techniques to study this phenomenon. We will focus on developing a colorectal cancer (CRC) model to quantify the mechanical modifications those cancer cells induce in the ECM, as CRC significantly alters the mechanical properties of its microenvironment. By examining how matrix remodelling reflects intrinsic cellular properties and how tumour progression influences topological constraints, we aim to uncover the interplay between cancer cell behaviour and ECM mechanics. This research is expected to elucidate the underlying mechanisms of CRC and provide critical insights that could benefit therapeutic strategies. Furthermore, these findings will contribute to a broader understanding of cell-ECM interactions, offering valuable information relevant to other diseases characterised by ECM dysregulation. <br>


<h2> Publications </h2>
{% for post in site.publications reversed %}
  {% if post.authors contains 'Yana Heyvaert' %}
    {% include archive-single-pub.html %}
  {% endif %}
{% endfor %}
