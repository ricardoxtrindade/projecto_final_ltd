---
layout: page
title: Pets
permalink: /pets/
---

{% for item in site.pets %}
    <h1>{{ site.pets.title }}</h1>
{% endfor %}