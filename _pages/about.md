---
permalink: /
excerpt: "About me"
author_profile: true
redirect_from:
  - /about/
  - /about.html
image_sliders:
  - home
---
<h1><span style="color:gray">Welcome to </span>Susana Rocha's Lab<span style="color:gray"> at KU Leuven</span></h1>
<br>

{% include slider.html selector="home" %}

<br>
<p align= "justify">
This website contains information about research ongoing in the NanoCenter, KULeuven.
For more details check our <a href="{{site.github.url}}/projects"><span style="color:gray">Projects</span></a>.

If you are not a scentist but are still interested in what we do, check out the <a href="{{site.github.url}}/outreach"><span style="color:gray">Science Outreach</span></a> section.
<br>
<br>
<hr-bold>


<div style="text-align:left; vertical-align: middle border-left: 500px">
<h3><br><a href="{{site.github.url}}/news"><span style="color:black">Latest news:</span></a></h3>
{% assign sorted = site.news | sort: 'date' | reverse %}
{% for item in sorted limit:5%}
<li><a href="{{ item.url }}">{{ item.title }}</a></li>
{% endfor %}
<br>
</div>
<br>
