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

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

Journal Papers
=========

1- A bandit-learning approach to multifidelity approximation, Yiming Xu, Vahid Keshavarzzadeh, Robert M. Kirby, Akil Narayan
