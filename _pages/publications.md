---
layout: archive
title: <img align="left" width="10" height="10" src="https://jesse-orange.github.io/images/star.png" alt="aaaaaa">"Publicationsddd"
permalink: /publications/
author_profile: true
header: 
  og_image: "/images/star.png"
---


{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
