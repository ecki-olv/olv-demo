---
permalink: /ergebnisse/
title: "Ergebnisse aller OLV-Wettkämpfe ab 2010"
---

{% for jahr in (2010..2022) %}
### {{ jahr }}

{% assign yearstring = jahr | prepend: '/' | append: '/' %}
{% assign files = site.static_files  | where: "doctype", "ergebnis" | where_exp:"item", "item.path contains yearstring" %}
{% for file in files %}
  {% assign eventdate = file.basename | split: '_' | first %}
  {% assign monat = eventdate | slice: 4, 2 %}
  {% assign tag = eventdate | slice: 6, 2 %}
  
  {% assign eventname = file.basename | split: '_' | join: " " %}
  * {{ tag }}.{{ monat }}.{{ jahr }}: <a href="{{ file.path | relative_url }}">{{ eventname }} </a>

{% endfor %}

{% endfor %}
