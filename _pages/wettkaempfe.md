---
permalink: /wettkaempfe/
title: "OLV-Wettkämpfe aktuell"
toc: true
toc_label: "Übersicht Wettkämpfe"
toc_icon: "running"  # corresponding Font Awesome icon name (without fa prefix)
---

Hier finden Sie Informationen über die Wettkämpfe des OLV im Jahr 2022.

**[Ergebnisse bereits durchgeführter Wettkämpfe liegen im Ergebnis-Archiv.]({{ "/ergebnisse/" | relative_url }})**



[Alle Ausschreibungen des OLV für das Wettkampfjahr 2022 in einer pdf](http://ohrdrufer-lv.de/inhalt/wettkaempfe/2022/Wettkampfausschreibungen%20OLV%202022%20-%20Stand_12.03.2022.pdf)

{% for wk  in site.data.wettkaempfe %}
### {{ wk.datum | date: "%d.%m.%Y" }} {{ wk.name }}

{{ wk.info }}

<ul>
{% for file in wk.dateien %}
  <li>
    <a href="{{ file.pfad | prepend: '/assets' | relative_url }}">
      {{ file.text }}
    </a>
  </li>
{% endfor %}
</ul>
{% endfor %}

