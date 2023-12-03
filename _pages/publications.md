---
layout: archive
title: "Publicationsddd"
permalink: /publications/
author_profile: true
header: 
  og_image: "/star.png"
---
<img align="left" width="80" height="80" src="https://jesse-orange.github.io/images/star.png" alt="Resume application project app icon">
{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
