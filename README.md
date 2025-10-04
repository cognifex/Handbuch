# Handbuch

Dieses Repository enthält das Organisationshandbuch der VHS Lahnstein. Die Kapitel wurden in einzelne Markdown-Dateien aufgeteilt, damit Inhalte gezielt gepflegt und erweitert werden können.

## Struktur

- [00 – Inhaltsverzeichnis](kapitel/00-inhaltsverzeichnis/index.md)
- [01 – Einleitung & Geltungsbereich](kapitel/01-einleitung-und-geltungsbereich/index.md)
- [02 – Rollen und Verantwortlichkeiten](kapitel/02-rollen-und-verantwortlichkeiten/index.md)
- [03 – Prozesse](kapitel/03-prozesse/index.md)
- [04 – Infrastruktur](kapitel/04-infrastruktur/index.md)
- [05 – Dokumentenmanagement & Ablage](kapitel/05-dokumentenmanagement-und-ablage/index.md)
- [06 – Kommunikation](kapitel/06-kommunikation/index.md)
- [07 – Themen & Fazit](kapitel/07-themen-und-fazit/index.md)
- [08 – Glossar](kapitel/08-glossar/index.md)
- [09 – Anhang](kapitel/09-anhang/index.md)

Jedes Kapitel liegt in einem eigenen Unterordner innerhalb von `kapitel/` und enthält eine `index.md` mit allen bisherigen Inhalten des Abschnitts.

## Veröffentlichung auf GitHub Pages

Für die Veröffentlichung der Dokumentation als zusammenhängendes DIN-A4-Dokument wurde unter `docs/` eine eigenständige Website hinterlegt. GitHub Pages kann so konfiguriert werden, dass der Ordner `docs/` als Quelle dient.

1. Öffne die Repository-Einstellungen auf GitHub und aktiviere **Pages**.
2. Wähle als Quelle `main`/`work` (je nach Standardbranch) und den Ordner **/docs**.
3. Nach der Veröffentlichung ist die Dokumentation unter `https://<username>.github.io/<repository>/` abrufbar.

Der Einstiegspunkt `docs/index.html` lädt alle Kapitel aus `docs/content/` und stellt sie als einzelne Seiten im DIN-A4-Layout dar. Die Layout-Vorgaben sind in `docs/assets/styles.css` hinterlegt. Die Markdown-Kapitel wurden mit dem Repository synchronisiert, so dass Aktualisierungen durch Kopieren in den `docs/content/` Ordner auf der Website sichtbar werden.
