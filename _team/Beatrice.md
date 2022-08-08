---
title: "Beatrice Fortuni"
collection: team
header:
  teaser: bea.png
tags: post-doc
tagline: FWO Fellowship
date: 2022-10-01
subject: "Engineering of nanomaterials for cancer phototherapies in 3D cell models"
prom: FWO Fellowship
---
<p align= "justify">
Despite significant advances in cancer therapy, cancer remains a major cause of death worldwide. In the last years there has been increasing interest in the development of new treatment modalities with reduced side effects for difficult-to-cure cancers. Prominent examples are Photothermal (PTT) and Photodynamic (PDT) therapy, designed to selectively kill cancerous tissue either through localized, light-induced thermal stress or generation of active radical species (singlet oxygen), respectively. The development of nanomaterials marks a significant step forward in these therapies. However, only few nanomaterial-mediated PTT and PDT have reached clinical trials and knowledge concerning the efficiency, mechanism and toxicity of these therapies remains limited. Ideal platforms for these studies are multicellular tumor spheroids. Nevertheless, in these 3D models, nanoparticle internalization and penetration are drastically reduced compared to the 2D cellular monolayer, impeding consistent investigation. Here, we propose an alternative strategy to perform fundamental studies of phototherapies in spheroids by using our innovative silver nanowire-based endoscopy technique. The probe will be modified to locally generate hyperthermia and singlet oxygen inside solid tumors. The cell response and the therapeutic efficiency will be carefully monitored. The information obtained thereby will be crucial for the rational design of next-generation nanomaterials towards cancer phototherapies.

<h2> Publications </h2>

<i>Bellow are some representative publications. For a complete list visit Dr. Fortuni's profile on <a href="https://orcid.org/0000-0003-4634-9518"><span style="color:gray">Orcid</span></a>.<i/>
<br><br>
{% for post in site.publications reversed %}
  {% if post.authors contains 'Beatrice Fortuni' %}
    {% include archive-single-pub.html %}
  {% endif %}
{% endfor %}
