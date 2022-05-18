---
permalink: /ergebnisse/
title: "Ergebnisse aller OLV-Wettkämpfe ab 2010"
---

### 2011
{% for file in site.static_files  | where: "doctype", "ergebnis" | where_exp:"item",
"item.path contains '/2011/'" %}
  * <a href="{{ file.path | relative_url }}">{{ file.name }} </a>
{% endfor %}
