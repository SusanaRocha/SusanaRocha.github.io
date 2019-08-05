---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
{% include base_path %}

You can find the complete publication list on <a href="https://scholar.google.be/citations?user=OsiAwIYAAAAJ&hl=en&citsig=AMstHGQQx0uqfgCvrTEny2ghp98R3FtD5Q">
<span style="color:gray">my Google Scholar profile</span></a>.

<h2> Articles </h2>
{% for post in site.publications reversed %}
  {% if post.authors contains 'Susana Rocha' %}
    {% include archive-single-pub.html %}
  {% endif %}
{% endfor %}

<h2> Bookchapters </h2>
{% for post in site.bookchapters reversed %}
  {% include archive-single-pub.html %}
{% endfor %}
