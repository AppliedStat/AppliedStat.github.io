---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

Recent Publications
======

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}



[Full Publication list](https://sites.google.com/view/appliedstat/publication)
======



