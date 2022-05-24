---
layout: page
title: Contacts
permalink: /contacts/
---
<ul class="contact-list">
{%- if site.author -%}
  {{ site.author | escape }}
{%- else -%}
  {{ site.title | escape }}
{%- endif -%}
{%- if site.email -%}
  <li><a href="mailto:{{ site.email }}">{{ site.email }}</a></li>
{%- endif -%}
{%- if site.phone -%}
  <li><a href="tel:{{ site.phone }}">{{ site.phone }}</a></li>
{%- endif -%}
</ul>