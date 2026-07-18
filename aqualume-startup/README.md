# AquaLume — Startup-Projekt

Studienprojekt für die Aufgabe „Startup-Gründung“. Die Website enthält genau
die in der Aufgabenstellung geforderten Inhalte:

- Produkt (AquaLume UV Flask) mit Beschreibung
- USP der Produkte
- Name für Produkt und Startup
- Tabelle mit Produkt-Eigenschaften
- Produktfotos
- Logo und Firmen-Motto
- Verlinkung der persönlichen Seiten beider Teammitglieder

## Team

| Rolle | Name |
|---|---|
| Driver | [Name Teilnehmer 1] — schreibt und committet den HTML/CSS-Code |
| Navigator | [Name Teilnehmer 2] — berät, prüft den Code, plant das Design |
| Vertretung für Teilnehmer 1 | [Name Teilnehmer 3] |

> Teilnehmer 3 vertritt Teilnehmer 1 an einem Tag, an dem dieser nicht
> anwesend ist. Das Team besteht weiterhin aus 2 aktiven Rollen
> (Driver/Navigator) gemäß Aufgabenstellung.

## Verwendete Technologien

- HTML5 (semantisch aufgebaut)
- reines CSS3 (kein Framework) — mit CSS-Variablen für Farben und Abstände
- **kein JavaScript** — das mobile Menü funktioniert über eine versteckte
  Checkbox rein mit CSS ("Checkbox-Hack")

## Projektstruktur

```
aqualume/
├── index.html            Hauptseite der Website
├── css/
│   └── style.css         Alle Styles, inkl. Farb- und Typografie-Variablen
├── images/
│   ├── logo-icon.svg      Logo (nur Icon), für Navbar & Footer
│   ├── logo-full.svg      Logo mit Schriftzug, z. B. für Präsentationen
│   ├── bottle-hero.svg    Produktabbildung im Produkt-Bereich
│   └── bottle-*.svg       Produktfotos in den 4 Farbvarianten
└── README.md
```

Alle Bilder sind selbst gestaltete SVG-Illustrationen (kein echtes Produktfoto
vorhanden, da AquaLume ein fiktives Produkt ist).

## Ausführen

Einfach die Datei `index.html` im Browser öffnen — keine Installation
oder Build-Schritte nötig.

## Offene Punkte

- Die Links bei „Persönliche Seite“ (im Team-Bereich) müssen noch durch die
  echten Links zu euren persönlichen Seiten ersetzt werden.
- Namen der Teilnehmer im Team-Bereich eintragen.
