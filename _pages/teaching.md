---
title: "Teaching"
permalink: /teaching/
author_profile: true
redirect_from: 
  - /md/
  - /markdown.html
---
{% include base_path %}

{% for post in site.teaching reversed %}
  {% include archive-single.html %}
{% endfor %}