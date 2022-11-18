---
title: "Sarah Vorsselmans"
collection: team
header:
  teaser: sarah.png
tags: phd
tagline: FLOF grant <br>promotor
date: 2022-10-01
subject: "Smart hydrogels for optically mapping forces in 3D cancer models"
email: sarah.vorsselmans@kuleuven.be
---

<p align= "justify">
Cerebral Cavernous Malformations (CCM) are stacks of malformed blood vessels in the brain. One inevery 200 persons worldwide can carry them and half are symptomatic (seizures, hemorrhage andneurological deficits). There is no treatment yet and surgical resection is the only possible cure.A vital but still understudied aspect of the disease is its connection with cell mechanics. Cells areknown to probe their environment by applying force to it. At the same time, internal and externalmechanical stimuli also affect cell behavior through mechanotransduction. In CCM, themechanosignaling pathways in the cells lining the vessel lumen are disturbed.CCM seems to be associated with low blood flow and high matrix stiffness. However, it is not knownhow these conditions interact with cellular force exertion and mechanotransduction, which ultimatelycontribute to the disease. To a large extent, this lack of knowledge is caused by the completeabsence of any force data under mechanical conditions relevant to CCM. To study this, thedevelopment of in vitro models mimicking the CMM environment is paramount.The main goal of this project is two-fold: to improve current in vitro microfluidic and hydrogel modelsin their ability to simulate the in vivo extrinsic mechanical environment and to use such models tosystematically investigate the role of intra- and intercellular forces, with the ultimate goal to identifynew targets for CCM therapy.

<h2> Publications </h2>
{% for post in site.publications reversed %}
  {% if post.authors contains 'Sarah Vorsselmans' %}
    {% include archive-single-pub.html %}
  {% endif %}
{% endfor %}
