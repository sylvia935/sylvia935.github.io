---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

Xiaoyi Tian, Jing Li, Qin Yu. Online Educational Information Quality Modeling and Perceived Difference Comparison, Journal of Hefei Normal University[J]. 2016, 34(5).

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
