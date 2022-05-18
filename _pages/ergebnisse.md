---
permalink: /ergebnisse/
title: "Ergebnisse aller OLV-Wettkämpfe ab 2010"
---

### 2011
{% assign files = site.static_files  | where: "doctype", "ergebnis" | where_exp:"item", "item.path contains '/2011/'" %}
{% for file in files %}
  * <a href="{{ file.path | relative_url }}">{{ file.name }} </a>
{% endfor %}
