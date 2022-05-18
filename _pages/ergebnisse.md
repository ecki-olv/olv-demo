---
permalink: /ergebnisse/
title: "Ergebnisse aller OLV-Wettkämpfe ab 2010"
---

{% for year in (2010..2022) %}
### {{ year }}

{% assign yearstring = year | prepend: '/' | append: '/' %}
{% assign files = site.static_files  | where: "doctype", "ergebnis" | where_exp:"item", "item.path contains yearstring" %}
{% for file in files %}
  {% assign eventdate = file.basename | split: '_' | first %}
  {% assign eventname = file.basename | split: '_' | shift %}
  * <a href="{{ file.path | relative_url }}">{{ eventdate }} - {{ eventname }} </a>

{% endfor %}

{% endfor %}
