---
permalink: /cricket/
title: "Cricket"
collection: cricket
excerpt: "Posts related to Cricket."
layout: collection
toc: true
---
{% for cricket in site.cricket %}
  <h2>{{ cricket.title }}</h2>
{% endfor %}