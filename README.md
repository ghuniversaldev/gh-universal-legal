# gh-universal-legal

Öffentliches Hosting der rechtlichen Dokumente der **G+H universal GmbH** via GitHub Pages.
Hier liegen Dokumente, die öffentlich abrufbar sein müssen (Datenschutzerklärungen, später
z.&nbsp;B. AGB, Auftragsdatenbearbeitungsverträge).

- `index.html` — Landing-Page mit Verzeichnis aller Dokumente.
- `datenschutz.html` — Datenschutzerklärung der G+H universal GmbH, **massgebliche Fassung**,
  inklusive Anhang A für die App Loquere!.
- `datenschutz_gh-universal.pdf` — derselbe Text als herunterladbare Kopie.

## Feste Links (GitHub Pages)

- Verzeichnis: `https://ghuniversaldev.github.io/gh-universal-legal/`
- Datenschutzerklärung (HTML): `https://ghuniversaldev.github.io/gh-universal-legal/datenschutz.html`
- Dieselbe Fassung als PDF: `https://ghuniversaldev.github.io/gh-universal-legal/datenschutz_gh-universal.pdf`

**Der HTML-Link ist der Verweis, der im Google-Play-Store-Eintrag hinterlegt ist**, nicht
das PDF. Im Store-Eintrag von Loquere! nachgeprüft am 28.08.2026.

## Woher der Inhalt kommt

Geändert wird **immer zuerst** in der Unternehmensablage (OneDrive,
`01 - Unternehmen/20-QM/Datenschutz/`): `datenschutz_gh-universal.docm` als
Quelldokument, daraus Webtext und PDF. Erst danach wird hierher repliziert. Nie
umgekehrt, und nie nur eines von beiden: Die Seite verweist auf das PDF als «gleiche
Fassung», das muss stimmen.

## Neues Dokument ablegen

Datei mit sprechendem Namen (`<produkt>-<art>.pdf`, z.&nbsp;B. `loquere-agb.pdf`) ins Repo
legen, in `index.html` verlinken, committen und pushen. Der jeweilige Link bleibt stabil.
