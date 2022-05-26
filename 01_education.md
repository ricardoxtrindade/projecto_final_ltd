---
layout: page
title: Education
permalink: /Education/
---

<ul class="educationlist">
    {% for item in site.data.educationlist %}
        <li>
            {{ item.year }}
            <h2 class="educationtitle">{{ item.school }}</h2>
            <h3>{{ item.course }}</h3>
            {{ item.activities }}
        </li>
    {% endfor %}
</ul>