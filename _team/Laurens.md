---
title: "Laurens D'Huys"
collection: team
header:
  teaser: Laurens.png
tags: phd
tagline: co-promotor
date: 2017-09-08
subject: "Fluorocode: towards super-resolved mapping of the gut microbiome"
prom: Prof. Johan Hofkens
email: laurens.dhuys@kuleuven.be
---
<p align= "justify">

Animalia, bacteria and viruses have been part of a delicately balanced system for about as long as they have co-existed, long before the advent of mankind. The gut of our ancient ancestors offered protected, nutrient-rich habitats for bacteria. In return, animals could take an evolutionary short-cut to developing new capabilities by ‘borrowing’ bacterial genes. As gut bacteria assist with the processing of e.g. host-indigestible carbohydrates or the production of vitamins, they will exert significant influence on the host immune system through intricate networks of host molecular pathways or by preventing colonization of the gut by pathogens. As such, commensal bacteria have been implicated in the function and homeostasis of the immune system. Gut bacteria, in addition to host genetics, constitute a major factor in the etiology of complex disorders. They are implicated in obesity, cardiovascular disease, autoimmune diseases like multiple sclerosis, rheumatoid arthrosis and inflammation conditions such as inflammatory bowel disease (IBD) Crohn’s (CD) or even neurological conditions such as Alzheimer’s (AD). <br>
With this work, an approach for enterotype analysis via enzyme-mediated, super-resolution optical genome mapping (Fluorocode) is presented (Figure 1). This methodology will be applied to obtain a diagnostic platform for studying the role of the bacterial and viral (bacteriophage) enterotype in human health and disease. The long range genomic information unlocked through Fluorocode will allow the envisioned platform to complement widely used NGS approaches by providing a more cost-effective alternative in diagnostic applications where base level resolution is not required. In addition, reducing cost and time expense per experimental run will allow for monitoring microbiome changes over time after administration of microbiome modulators (e.g. probiotics), thus also allowing for theragnostic use of the method.

<br>
<p align="center">
<img src='/images/fluorcode.png' style='width: 90%'>
<br><br>

<span style="font-size:0.8em"><i> Figure 1. Fluorocode workflow (Mtase = Methyltransferase)</i></span>
</p>

<p align= "justify">
<h2> Publications </h2>
{% for post in site.publications reversed %}
  {% if post.authors contains "Laurens D'Huys" %}
    {% include archive-single-pub.html %}
  {% endif %}
{% endfor %}
