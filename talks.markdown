---
layout: page
title: Talks
permalink: /talks/
---
<h3>Posts on {{ page.title }}</h3>
{% for post in site.categories.talks %}
  <a href="{{ post.url }}">{{ post.title }}</a>
{% endfor %}

