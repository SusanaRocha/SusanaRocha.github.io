---
title: "Bart Thevelein"
collection: team
header:
  teaser: bart.jpg
tags: phd
tagline: co-promotor
date: 2020-10-01
subject: "Novel applications of expansion microscopy"
prom: Prof. Johan Hofkens
email: bart.thevelein@kuleuven.be
---
<p align= "justify">

The field of super-resolution microscopy is quickly expanding, and one of the latest methods in this field is expansion microscopy (ExM). Instead of utilizing complicated imaging schemes such as in PALM, STORM or STED, ExM makes use of the physical enlargement of samples to bypass the resolution limit. Cells or tissues are embedded in a polymer gel which is subsequently expanded isotropically by dialysis with water. This  expansion increases the distances between molecules 4-10 fold. Since fluorophores which are closer to each other than the resolution limit have their distances also increased, this process effectively increases the resolution 4-10 fold. It has a clear advantage compared to other supper-resolution techniques, namely that it does not require any special hardware, software or dyes, which makes it much more approachable for many biological labs.
Since the methods inception in 2015, it has shown its usefulness. We now want to push the boundaries of ExM and find novel applications. We would like to apply ExM to single-cell multi-omics technologies, where it will support the development of high throughput methods. These approaches make use of fluorescent probes that sequentially bind to various biomolecules. By increasing the resolution, the amount of marked biomolecules that can be detected is increased. This project will be done in cooperation with other labs, in order to establish end-to-end state-of-the-art pipelines for in situ multi-omic analysis.
We also want to look into various other applications, such as the expansion of membranes and the small elusive lipid rafts within them. Another application would be the study of focal adhesions. These are structures the cell uses to attach to its surroundings. Although these are easily detected when the cell is attached to a surface, the study of focal adhesions for cells in a 3D environment is much more challenging. Using expansion microscopy to expand the 3D environment may reveal more information about these focal adhesions. ExM is a technique that is very suitable to be combined with other super-resolution techniques. For instance, STED could be used to further increase the resolution of images of expanded samples.
Each of these applications comes with its own challenges, which I will gladly tackle in the coming years of my PhD.

</p>

<p align= "justify">
<h2> Publications </h2>
{% for post in site.publications reversed %}
  {% if post.authors contains "Bart Thevelein" %}
    {% include archive-single-pub.html %}
  {% endif %}
{% endfor %}
