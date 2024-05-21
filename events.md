---
layout: page
title: Events
permalink: /events/
---

 {% for post in site.posts %}
<li>
  <a href="{{ post.url }}">{{ post.title }}</a>
</li>
{% endfor %}
