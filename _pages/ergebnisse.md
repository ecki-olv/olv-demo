---
permalink: /ergebnisse/
title: "Ergebnisse aller OLV-Wettkämpfe ab 2010"
---

### 2011

{% assign files = site.static_files  | where: "doctype", "ergebnis" | where_exp:"item", "item.path contains '/2011/'" %}
{% for file in files %}
  {% assign filedate = file.basename | split: '_' | first %}
  * <a href="{{ file.path | relative_url }}">{{ filedate | date: "$d.%m.%Y" }} - {{ filedate }} - {{ file.name }} </a>
{% endfor %}
