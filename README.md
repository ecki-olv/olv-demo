## Hinweise

### TODOs
* Die Seite mit den kommenden Wettkämpfen hab ich jetzt nur mit 3 Beispielen gefüllt.
* Doku hier ins Readme

### sonstige Hinweise
- Die Seite mit den Ergebnissen aktualisiert sich von alleine, sobald man ein Ergebnis-PDF (oder HTML....) ins richtige Verzeichnis hochlädt (Datei muss YYMMDD-irgendwas.pdf heißen, jede Dateiendung möglich)
- News sind auf der Startseite unten mit dran. Da sind jetzt auch nur Dummybeispiele zu sehen. Ließe sich auch voneinander trennen. Oder vlt. das Sponsor-Logo in kleinerem Format auf jeder Seite einblenden und dafür die News-Startseite übersichtlicher gestalten.

## "Was mache ich, wenn..."
### ich einen neuen Eintrag für einen Wettkampf vornehmen will?
* Lade PDFs und andere Anmeldedokumente hoch nach `/assets/wettkaempfe/20XX` in den passenden Jahresordner
* Bearbeite `_data/wettkaempfe.yml` und füge dort einen neuen Eintrag hinzu, dort kannst du auf die Anmeldedokumente verweisen. Wie das geht, kannst du anhand der bereits vorhandenen Einträge sehen.

### Wettkampfergebnisse veröffentlichen will?
* Lade die Datei ins Verzeichnis `assets/ergebnisse/20XX` in das passenden Jahresverzeichnis hoch und benenne die Datei nach dem Schema `YYYMMDD-Thema.pdf` also z.B. `20220623-Juni-Wettkampf-Ergebnisse.pdf` - es sind auch andere Dateiendungen wie z.B. html, doc möglich. Nach ein paar Minuten wird der Eintrag automatisch auf der neu generierten Webseite sichtbar sein.

### bei Jahreswechsel
* evtl. neue Wettkampf-Datenseite? Die alte Seite archivieren/umbenennen?? - abklären.

## Doku zum verwendeten Theme "Minimal Mistakes" 

* [MMistakes Repo](https://github.com/mmistakes/minimal-mistakes).
* [Konfiguration](https://mmistakes.github.io/minimal-mistakes/docs/configuration/).
