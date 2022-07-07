---
layout: page
title: Events
permalink: /events/
graph: true
---

<ul>
{% for post in site.categories.events %}
  <li>
  <a href="{{ post.url | absolute_url}}">{{ post.title }}</a>
  {{ post.excerpt }}
  </li>
{% endfor %}
</ul>