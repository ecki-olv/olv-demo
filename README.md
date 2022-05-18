## Hinweise

### TODOs
* Die Seite mit den kommenden Wettkämpfen hab ich jetzt nur mit 3 Beispielen gefüllt. Übrige nachtragen.
* Farbschema abstimmen. Auswahl hier: https://mmistakes.github.io/minimal-mistakes/docs/configuration/#skin
* Sponsor-Logo in die Sidebar, damit News auf der Startseite besser zu sehen sind?
* inhaltlich sinnvolle News, wenigstens ein Blogartikel mit "Hey, neuer Webauftritt" und Dummyartikel wegwerfen
* Optik auf Handy checken, wo ist welche Link-Sichtbarkeit sinnvoll?
* doppelte Links in Sidebar und Header - was behalten, was weg?
* Instagram verlinken
* ~~Wettkampfergebnisse neuestes Jahr ganz oben?~~ erstmal ja.
* Umgang mit Jahreswechsel auf der Wettkampfseite
* generell: wie lange sollen alte Infos auf der Webseite sichtbar sein?

# "Was mache ich, wenn..."
## ich einen neuen Eintrag für einen Wettkampf vornehmen will?
* Lade PDFs und andere Anmeldedokumente hoch nach `/assets/wettkaempfe/20XX` in den passenden Jahresordner
* Bearbeite `_data/wettkaempfe.yml` und füge dort einen neuen Eintrag hinzu, dort kannst du auf die Anmeldedokumente verweisen. Wie das geht, kannst du anhand der bereits vorhandenen Einträge sehen.

## ich Wettkampfergebnisse veröffentlichen will?
* Lade die Datei ins Verzeichnis `assets/ergebnisse/20XX` in das passenden Jahresverzeichnis hoch und benenne die Datei nach dem Schema `YYYMMDD-Thema.pdf` also z.B. `20220623-Juni-Wettkampf-Ergebnisse.pdf` - es sind auch andere Dateiendungen wie z.B. `.html`, `.doc` möglich. Nach ein paar Minuten wird der Eintrag automatisch auf der neu generierten Webseite sichtbar sein. Unterstriche im Dateinamen werden auf der Webseite im Dateilink später als Leerzeichen sichtbar sein.

## ein Jahreswechsel ansteht und ich die Wettkampfseite aktualisieren will?
* evtl. neue Wettkampf-Datenseite? Die alte Seite archivieren/umbenennen?? - abklären.

## ich Neuigkeiten (auf der Startseite) veröffentlichen will?
frag Steffi.

# Doku zum verwendeten Theme "Minimal Mistakes" 

* [MMistakes Repo](https://github.com/mmistakes/minimal-mistakes).
* [Konfiguration](https://mmistakes.github.io/minimal-mistakes/docs/configuration/).
