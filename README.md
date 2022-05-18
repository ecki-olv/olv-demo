## Hinweise

### TODOs
* Die Seite mit den kommenden Wettkämpfen hab ich jetzt nur mit 3 Beispielen gefüllt. Übrige nachtragen.
* Farbschema abstimmen. Auswahl hier: https://mmistakes.github.io/minimal-mistakes/docs/configuration/#skin
* Sponsor-Logo in die Sidebar, damit News auf der Startseite besser zu sehen sind?
* inhaltlich sinnvolle News, wenigstens ein Blogartikel mit "Hey, neuer Webauftritt" und Dummyartikel wegwerfen
* Optik auf Handy checken, wo ist welche Link-Sichtbarkeit sinnvoll?
* doppelte Links in Sidebar und Header - was behalten, was weg?
* Instagram verlinken
* Wettkampfergebnisse neuestes Jahr ganz oben?

### sonstige Hinweise
- Die Seite mit den Ergebnissen aktualisiert sich von alleine, sobald man ein Ergebnis-PDF (oder HTML....) ins richtige Verzeichnis hochlädt (Datei muss YYMMDD-irgendwas.pdf heißen, jede Dateiendung möglich)
- News sind auf der Startseite unten mit dran. Da sind jetzt auch nur Dummybeispiele zu sehen. Ließe sich auch voneinander trennen. Oder vlt. das Sponsor-Logo in kleinerem Format auf jeder Seite einblenden und dafür die News-Startseite übersichtlicher gestalten.

## "Was mache ich, wenn..."
### ich einen neuen Eintrag für einen Wettkampf vornehmen will?
* Lade PDFs und andere Anmeldedokumente hoch nach `/assets/wettkaempfe/20XX` in den passenden Jahresordner
* Bearbeite `_data/wettkaempfe.yml` und füge dort einen neuen Eintrag hinzu, dort kannst du auf die Anmeldedokumente verweisen. Wie das geht, kannst du anhand der bereits vorhandenen Einträge sehen.

### ich Wettkampfergebnisse veröffentlichen will?
* Lade die Datei ins Verzeichnis `assets/ergebnisse/20XX` in das passenden Jahresverzeichnis hoch und benenne die Datei nach dem Schema `YYYMMDD-Thema.pdf` also z.B. `20220623-Juni-Wettkampf-Ergebnisse.pdf` - es sind auch andere Dateiendungen wie z.B. `.html`, `.doc` möglich. Nach ein paar Minuten wird der Eintrag automatisch auf der neu generierten Webseite sichtbar sein.

### ein Jahreswechsel ansteht und ich die Wettkampfseite aktualisieren will?
* evtl. neue Wettkampf-Datenseite? Die alte Seite archivieren/umbenennen?? - abklären.

### ich Neuigkeiten (auf der Startseite) veröffentlichen will?
frag Steffi.


## Doku zum verwendeten Theme "Minimal Mistakes" 

* [MMistakes Repo](https://github.com/mmistakes/minimal-mistakes).
* [Konfiguration](https://mmistakes.github.io/minimal-mistakes/docs/configuration/).
