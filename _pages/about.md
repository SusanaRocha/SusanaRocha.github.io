---
permalink: /
title: Watching Life at the Nanometer Scale!
excerpt: "About me"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---
<h2> Welcome! </h2>
<p align= "justify">
This website contains information about research ongoing in the NanoCenter, KULeuven.
For more details check our <a href="{{site.github.url}}/projects">Projects</a>.

If you are not a scentist but are still interested in what we do, check out the <a href="{{site.github.url}}/outreach">Science Outreach</a> section.
<br>

<div style="background-color:rgba(0, 0, 0, 0.0470588); text-align:center; vertical-align: middle border-left: 500px">
<h3><br><a href="{{site.github.url}}/news">Latest news:</a></h3>
{% assign sorted = (site.news | sort: 'date') | reverse %}
{% for item in sorted limit:5%}
{{ item.title }}<br>
{% endfor %}
<br>
</div>
<br>
