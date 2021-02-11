---
layout: page
title: Music
permalink: /music/
---
<h3>{{ page.title }}</h3>
{% for post in site.categories.music %}
  <a href="{{ post.url }}">{{ post.title }}</a>
{% endfor %}
