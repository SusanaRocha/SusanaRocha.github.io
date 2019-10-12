---
layout: archive
title: "News"
permalink: /news/
author_profile: true
---

{% include base_path %}


{% for post in site.news reversed %}
  {% include archive-single-news.html %}
{% endfor %}
