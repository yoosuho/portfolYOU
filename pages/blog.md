---
layout: page
title: Blog
permalink: /blog/
weight: 4
---

# 📝 Latest Blog Posts

{% for post in site.posts %}
  <div style="margin-bottom: 2rem;">
    <h3><a href="{{ post.url }}">{{ post.title }}</a></h3>
    <p><small>{{ post.date | date: "%B %d, %Y" }}</small></p>
    <p>{{ post.excerpt }}</p>
    <a href="{{ post.url }}">Read more →</a>
  </div>
  <hr>
{% endfor %}
