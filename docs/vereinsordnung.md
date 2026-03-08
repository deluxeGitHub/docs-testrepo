---
title: "Vereinsordnung"
subtitle: "des Meinverein e.V."
date: "{{ site.time | date: '%d.%m.%Y' }}"
template: meinverein
section_numbering: paragraph
pdf: /assets/pdf/vereinsordnung.pdf
---

* TOC
{:toc}

# Allgemeine Bestimmungen

Dieses Dokument demonstriert das custom Theme `meinverein` mit eigenem
Farbschema (Dunkelgrün), eigenem Logo und eigenem Favicon.

## Zweck

1. Dieses Dokument dient als Beispiel für ein custom Theme.
1. Das Theme liegt im Docs-Repo unter `templates/meinverein/`.
1. Es überschreibt kein bestehendes Framework-Theme, sondern ergänzt es.

## Geltungsbereich

1. Das Custom-Theme gilt nur für dieses Docs-Repo.
1. Andere Repos bleiben davon unberührt.

# Theme-Konfiguration

## Voraussetzungen

Folgende Dateien müssen im Docs-Repo vorhanden sein:

- `templates/meinverein/web.css` – CSS-Variablen und Overrides
- `templates/meinverein/pdf-header.tex` – LaTeX-Header für PDFs
- `templates/meinverein/images/logo.png` – Logo (Header und Titelseite)
- `templates/meinverein/images/favicon.png` – Favicon

## Registrierung

In `_config.yml` des Docs-Repos eintragen:

```yaml
custom_templates:
  - meinverein
```

Danach kann jedes Dokument `template: meinverein` im Front Matter verwenden.

# Schlussbestimmungen

1. Das Custom-Theme wird bei jedem Build automatisch verwendet.
1. Logo und Favicon können jederzeit durch eigene Grafiken ersetzt werden.
