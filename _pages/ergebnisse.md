---
permalink: /ergebnisse/
title: "Ergebnisse aller OLV-Wettkämpfe ab 2010"
---

{% for file in site.static_files  | where: "doctype", "ergebnis" %}
  * <a href="{{ file.path }}">{{ file.name }} </a>
{% endfor %}