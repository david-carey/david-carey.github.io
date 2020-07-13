---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

You can find all of my research papers on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>

In most cases I will reply to full text requests sent via <u><a href="{{author.researchgate}}">Researchgate</a> (or other channels).</u>

<script type='text/javascript' src='https://d1bxh8uas1mnw7.cloudfront.net/assets/embed.js'></script>

<div class='altmetric-embed' data-badge-type='donut' data-doi="10.1249/mss.0000000000001685"></div>

<!-- {% if author.googlescholar %}
  You can find all of my research papers on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %} -->

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
