---
permalink: /wettkaempfe/
title: "OLV-Wettkämpfe aktuell"
toc: true
toc_label: "Übersicht Wettkämpfe"
toc_icon: "running"  # corresponding Font Awesome icon name (without fa prefix)
---

Hier finden Sie Informationen über die Wettkämpfe des OLV im Jahr 2022.

**[Ergebnisse bereits durchgeführter Wettkämpfe liegen im Ergebnis-Archiv.]({{ site.url }}/ergebnisse/)**


TODO: >>> Alle Ausschreibungen des OLV für das Wettkampfjahr 2022 in einer pdf <<< 


{% for file in site.static_files |  where: "doctype" , "wettkampf"  %}
  * <a href="{{ file.path | relative_url }}">{{ file.name }} </a>
{% endfor %}
