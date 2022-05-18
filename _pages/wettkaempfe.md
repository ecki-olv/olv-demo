---
permalink: /wettkaempfe/
title: "OLV-Wettkämpfe aktuell"
---

Hier finden Sie Informationen über die Wettkämpfe des OLV im Jahr 2022.

**[Ergebnisse bereits durchgeführter Wettkämpfe liegen im Ergebnis-Archiv.](/ergebisse)**


TODO: >>> Alle Ausschreibungen des OLV für das Wettkampfjahr 2022 in einer pdf <<< 


{% for file in site.static_files %}
  * <a href="{{ file.path }}">{{ file.name }} </a>
{% endfor %}