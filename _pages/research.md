---
layout: archive
title: "Research Projects"
permalink: /research/
author_profile: true
redirect_from:
  - /research-project/
  - /research-prokects
---

{% include base_path %}

{% for post in site.research reversed %}
  {% include archive-single.html %}
{% endfor %}
