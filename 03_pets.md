---
layout: page
title: Pets
permalink: /pets/
---

{% for item in site.pets %}
<h1><a href="{{ item.url | relative_url }}">{{ item.title }}</a></h1>
{% endfor %}