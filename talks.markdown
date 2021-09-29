---
layout: page
title: Talks
permalink: /talks/
---
{% for post in site.categories.talks %}
  <a href="{{ post.url }}">{{ post.title }}</a>
{% endfor %}

