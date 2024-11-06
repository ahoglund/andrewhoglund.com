---
layout: page
title: Writing
permalink: /writing/
---
{% for post in site.categories.writing %}
  <a href="{{ post.url }}">{{ post.title }}</a>
{% endfor %}

