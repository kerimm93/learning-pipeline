# Codex Context

## Source of Truth
Die aktive App ist: /index.html

Diese Datei darf NICHT komplett neu geschrieben werden.
Nur minimal-invasive Änderungen sind erlaubt.

---

## Ziel der Weiterentwicklung
Die App soll schrittweise zu einem Zettelkasten-Ingestor umgebaut werden.

---

## Referenz-Dateien (nur zur Orientierung)

- /docs/reference/zettelkasten-ingestor-prototype.html
→ Ziel-UI und Ziel-Workflow

- /docs/reference/zettelkasten-ingestor-systemanalyse.html
→ Ziel-Architektur

- /docs/reference/prototype-info.md
→ zusätzliche Design-Notizen

Diese Dateien sind:
- NICHT implementiert
- NICHT Source of Truth
- KEINE Basis für kompletten Rewrite

---

## Arbeitsweise

Codex soll:

1. Bestehenden Code analysieren
2. Kleine, sichere Änderungen vorschlagen
3. Keine komplette Neuimplementierung machen
4. Bestehende Features nicht zerstören
5. Schrittweise refactoren

---

## Ziel

Transformation von:
ETL Pipeline → Zettelkasten-Ingestor

ohne Rewrite.
