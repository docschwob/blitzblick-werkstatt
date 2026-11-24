# Blitzblick-Werkstatt

Digitales Arbeitsmittel zum schnellen Sehen von Anzahlen (simultane und quasi-simultane Zahlerfassung) für den Mathematikunterricht der Grundschule und für die Lehrerbildung.

**App öffnen:** https://docschwob.github.io/blitzblick-werkstatt/

## Zweck

Die App bildet die bekannten Blitzblick-Übungen digital ab: Eine Zahldarstellung wird kurz gezeigt und dann abgedeckt. Die Kinder nennen die Anzahl und beschreiben, *wie* sie sie gesehen haben („Ich sehe 5 und 2“). Digital kommen genau einstellbare Zeigedauern, dosierbare Hilfen, das Einkreisen von Teilmengen und ein Schrittprotokoll mit Wiedergabe hinzu.

## Funktionen

- Darstellungen: Würfelbilder, Punkte in Gruppen, Zehnerfeld, Zehnerstreifen, Zwanzigerfeld (Kraft der Fünf), Hunderterfeld mit Abdeckwinkel
- Schwierigkeitsleiter in sechs Stufen: Ansehen · Kurz zeigen · Blitz · Ohne Linien · Nur in Worten (nachlegen) · Selbst erfinden (und blitzen lassen)
- Antworten: Zahl tippen, nachlegen (Plättchen rot/blau), einkreisen, wie man die Anzahl gesehen hat
- Hilfen (werden protokolliert): noch einmal zeigen, länger zeigen, mit Linien zeigen, Bild 3 Sekunden zeigen, eine Reihe/Gruppe vorlegen, Satzanfänge
- Prüfen nur auf Anfrage: erst „passt / passt noch nicht“, auf Wunsch „Wo hakt es?“ mit Markierung. Abschaltbar, auch per Link `#ohne-pruefen`
- Schrittprotokoll mit Zeitstempeln, Rückgängig, Wiedergabe; Export als Tabelle (CSV) oder JSON
- Präsentationsmodus für den Beamer (Leertaste = zeigen, A = aufdecken, Pfeiltasten = Karte)
- Helles und dunkles Design, Touch und Tastatur, Tablet und Laptop
- Direktlinks: `#satz=zwanzigerfeld&stufe=3&karte=4` (Sätze: `wuerfel`, `punkte`, `zehnerfeld`, `zehnerstreifen`, `zwanzigerfeld`, `hunderterfeld`)

Aufgaben liegen als Datenstruktur (`CARDS`) im Code; ein Lehrkraft-Editor ist für Version 2 vorgesehen.

## Didaktische Grundlagen

Übungsformate nach: Das Zahlenbuch 1–3 (Blitzrechnen „Wie viele?“, Zehnerfelder, Kraft der Fünf, Hunderterfeld), PIKAS / Mathe inklusiv „Schnelles Sehen“, PIKAS „Arithmetische Kompetenzen am Schulanfang“, Mahiko „Blitzgucken“ und „Blitzblick-Übungen ZR 100“. Zahlbilder und Texte sind eigene Gestaltungen.

## Urheber

Dr. Simeon Schwob (GIMB, Universität Münster). Privates Angebot, kein offizielles Angebot der Universität Münster.

[Impressum](https://docschwob.github.io/impressum.html)

## Datenschutz

Die App erhebt keine Daten: Eingaben werden nicht an einen Server gesendet. Nur Einstellungen (z. B. Zeigedauer, Design) werden im eigenen Browser gespeichert (localStorage). Das Protokoll existiert nur im geöffneten Fenster und wird nur gespeichert, wenn man es selbst als Datei sichert. Die Seite wird über GitHub Pages bereitgestellt; GitHub verarbeitet dabei technisch notwendige Zugriffsdaten wie die IP-Adresse ([Datenschutzerklärung von GitHub](https://docs.github.com/de/site-policy/privacy-policies/github-general-privacy-statement)). Schriften liegen im Repository, Dienste Dritter sind nicht eingebunden.

## Lizenz

- Programmcode: MIT-Lizenz (siehe `LICENSE`)
- Aufgaben, Texte und Abbildungen: [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/deed.de)
- Schriften Atkinson Hyperlegible und Baloo 2: SIL Open Font License 1.1 (siehe `fonts/`)
