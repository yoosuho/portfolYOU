---
layout: page
title: Projects
permalink: /projects/
---

# 🚀 Projects

Here are some of the key projects I've worked on:

{% for project in site.projects %}
## [{{ project.title }}]({{ project.url | relative_url }})

{{ project.description }}

{% endfor %}
