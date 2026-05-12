# CLAUDE.md

Diese Datei enthält Hinweise für Claude Code (claude.ai/code) beim Arbeiten mit diesem Repository.

## Was dieses Repository ist

Eine persönliche, deutschsprachige Rezeptsammlung als Markdown-Dateien. Jedes Rezept ist eine eigenständige `.md`-Datei im Hauptverzeichnis. Zugehörige Fotos liegen in `pictures/`.

## Format-Konventionen für Rezepte

Rezepte folgen einer einheitlichen deutschsprachigen Markdown-Struktur:

- `# Titel` — Rezeptname (deutsch, ggf. mit Originalsprach-Untertitel in Klammern)
- `## Abschnitt` — Hauptbestandteile (z. B. `## Zutaten`, `## Zubereitung`, oder benannte Komponenten wie `## Hefeteig`)
- `### Zutaten:` / `### Zubereitung:` — Zutatenlisten und nummerierte Schritte innerhalb einer Komponente
- Mengenangaben in metrischen Einheiten (g, mL, °C); `EL` (Esslöffel) und `TL` (Teelöffel) sind für Löffelmaße zulässig
- Optionaler `## Danksagung`-Block, um die Rezeptquelle zu würdigen; ganz weglassen, wenn niemand zu nennen ist
- Bilder ganz am Ende (nach der Danksagung): `![Alt-Text](pictures/dateiname.jpg)` — `<img src="..." width="...">` nur verwenden, wenn eine Größenanpassung nötig ist; Richtmaß für die Breite ist 700 px

## Stilkonventionen

- Jeder nummerierte Schritt endet mit einem Punkt
- Tipps und Hinweise als Blockzitat mit fettem Label: `> **Tipp:** ...`
- Zahlenbereiche mit Halbgeviertstrich `–` statt Bindestrich (z. B. `14–16 Törtchen`, `20–25 Minuten`)
- `z. B.` mit Leerzeichen nach dem Punkt
- Leerzeichen vor Einheiten mit Gradzeichen: `180 °C`, nicht `180°C`
- Keine Trailing-Whitespaces am Zeilenende
