---
layout: page
title: "HOME-PAGE"
permalink: /
---

Hi! I’m Chad Merrill. Here are some of my projects:

{% for project in site.projects %}
- [{{ project.title }}]({{ project.url }})
{% endfor %}
