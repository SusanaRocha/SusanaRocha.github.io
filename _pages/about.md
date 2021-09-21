---
permalink: /
layout: archive
excerpt: "About me"
author_profile: true
redirect_from:
  - /about/
  - /about.html
image_sliders:
  - home
---
<body align="left">
<img src='/images/lettericon.png' style='width: 40%'>

{% include slider.html selector="home" %}
<br>
<h1>Welcome!</h1>

<p align= "justify">
This website contains information about research ongoing in the NanoCenter, KULeuven.
For more details check our <a href="{{site.github.url}}/projects"><span style="color:gray">Projects</span></a>.

If you are not a scientist but are still interested in what we do, check out the <a href="{{site.github.url}}/outreach"><span style="color:gray">Science Outreach</span></a> section.
<br>
<hr-bold>
<br>

<div style="text-align:left; vertical-align: middle border-left: 500px">
<h2><a href="{{site.github.url}}/news"><span style="color:gray">Latest news:</span></a></h2>
{% assign sorted = site.news | sort: 'date' | reverse %}
{% for item in sorted limit:5%}
<li><a href="{{ item.url }}">{{ item.title }}</a></li>
{% endfor %}
<br>
</div>
<br>
