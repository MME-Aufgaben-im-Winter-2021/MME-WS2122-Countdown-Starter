# Erste Übungsaufgabe: Countdown

Entwickeln Sie eine einfache, browser-basierte Implementierung der *letter round* aus der britischen TV-Show [Countdown](https://en.wikipedia.org/wiki/Countdown_(game_show)).

Die Anleitung zur Aufgabe (*Handout*) finden Sie [hier](https://multimedia-engineering.git-pages.uni-regensburg.de/mme-online/#/Aufgaben/WS2122/WS2122-Countdown).

## Pairing-Sitzungen

Für die Implementierung der Aufgabe sollten Sie mindestens zwei _Pair Programming_-Sitzungen an unterschiedlichen Tagen einplanen. Legen Sie im Vorfeld fest, an welchen Teilen der Aufgabe Sie arbeiten wollen. Bereiten Sie sich jeweils konkret auf die Umsetzung dieser geplanten _Features_ vor. Natürlich können Sie auch in weiteren Sitzungen am gemeinsamen Lösungsvorschlag arbeiten. Bitte dokumentieren Sie im Anschluss an jede Sitzung kurz, an welchen Teilen der Aufgaben Sie gearbeitet haben und welche Ziele Sie in der Sitzung erreicht haben. Sie können sich dabei an diesem Beispiel orientieren.

### Sitzung 01, 1. Januar 1970, 13:37 Uhr

(Wechsel zwischen Driver und Navigator nach jeweils ca. 30 Minuten)

#### Geplant war die Bearbeitung dieser Features

- Buchstabenauswahl durch die Nutzer\*innen \[**abgeschlosse**\]
- Start der Raterunde, Freigabe des Eingabefelds und Animation der Uhr \[**abgeschlossen**\]
- Abfangen des Rundenendes und Sperren des Eingabefelds \[**abgeschlossen**\]
- Auslesen der Nutzer\*innen-Eingabe \[**unvollstädnig**\]

**Erreichter Zustand**: Nutzer\*innen können vor dem Start der Spielrunde unter Berücksichtigung aller relevanten Spielregeln eine Auswahl an Vokalen und Konsonanten erstellen. Wenn der letzte Buchstabe ausgewählt wurde startet die Raterunde, was durch die Animation der Uhr visualisiert wird. Während der Raterunde können Eingaben in dem entsprechenden Eingabefeld getätigt werden. Nach 30 Sekunden wir das Ende der Raterunde erkannt. Die Animation wird gestoppt und es sind keine weiteren Änderungen am Eingabefeld möglich.
