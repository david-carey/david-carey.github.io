---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

Check if this works

{% if author.googlescholar %}
  You can find all of my research papers on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
