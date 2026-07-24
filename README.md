# Interaktive Unterrichts-Widgets

Self-contained HTML-Widgets (inline CSS/JS, keine externen Abhängigkeiten) als digitale
Enaktivität. Öffnen im Browser, keine Anmeldung.

Live: <https://nychts.github.io/widgets/>

## Struktur

```
/                      Fächer-Startseite
  style.css            geteiltes Stylesheet (Flexbox, mobilfreundlich)
  mathematik/          TOC + aufklappbar (Klasse -> Reihe -> Widgets)
    achsentrick_explorer.html    Kl. 10 · Manipulierte Grafiken
    zufallslabor.html            Kl. 10 · Kleine Stichproben
    basisraten_explorer.html     Kl. 10 · Medizinische Tests
  informatik/          gleiche Struktur, noch ohne Widgets
```

## Neues Widget hinzufügen

1. HTML-Datei in `mathematik/` bzw. `informatik/` ablegen.
2. Im jeweiligen `index.html` den `KLASSEN`-Datensatz um einen Widget-Eintrag ergänzen
   (Titel, Stunde, Beschreibung, `href`).

Frei nutzbar für den Unterricht.
