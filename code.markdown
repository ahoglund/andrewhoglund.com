---
layout: page
title: Code
permalink: /code/
---
<h3>Posts on {{ page.title }}</h3>
{% for post in site.categories.code %}
  <a href="{{ post.url }}">{{ post.title }}</a>
{% endfor %}
