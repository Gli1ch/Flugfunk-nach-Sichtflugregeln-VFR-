# VFR Funktrainer

Kostenlose Lernplattform für den Flugfunk nach Sichtflugregeln (VFR). Privatpiloten und Flugschüler üben realistische Funkdialoge Schritt für Schritt, rein textbasiert und mit dem eigenen Kennzeichen.

**Live-Version:** _Link folgt_

> **Hinweis:** Nur zu Übungszwecken. Verfahren, Frequenzen und Meldepunkte sind vereinfacht dargestellt. Maßgeblich sind AIP, NfL und die aktuelle Sichtanflugkarte.

## Funktionen

- **Eigenes Kennzeichen:** Alle Dialoge verwenden dein Rufzeichen, vollständig, abgekürzt (z. B. D-EABC wird zu D-BC) und auf Wunsch buchstabiert.
- **Kurs:** Lektionen in sinnvoller Reihenfolge, jeweils mit kurzem Wissenscheck.
- **Funkbeispiele:** Komplette Funkverkehre zu typischen Situationen, Meldung für Meldung mit Erklärung und schematischer Lagekarte.
- **Übungsmodus:** Pilotenmeldungen bleiben verdeckt, bis du sie aufdeckst. So überlegst du dir die Meldung zuerst selbst.
- **Kein Konto, kein Tracking:** Kennzeichen und Fortschritt werden nur lokal im Browser gespeichert.

## Inhalte

| Bereich | Inhalt | Status |
|---|---|---|
| Kurs | Modul 1, Lektion „Dein Rufzeichen“ | verfügbar |
| Funkbeispiel | Durchflug einer Kontrollzone (CTR Nürnberg) | verfügbar |
| Kurs | Module 2 bis 5 | in Vorbereitung |
| Funkbeispiele | Platzrunde, TMZ, RMZ, FIS, Notfall | in Vorbereitung |

## Technik

Eine statische Web-App ohne Server und ohne Datenbank: eine einzige `index.html` mit HTML, CSS und JavaScript. Sie läuft in jedem modernen Browser und kann kostenlos gehostet werden, z. B. bei Netlify, Cloudflare Pages oder GitHub Pages.

Farben und Schriften sind zentral als CSS-Variablen ganz oben in der Datei definiert und lassen sich dort anpassen.

## Lokal ansehen

Repository herunterladen und `index.html` im Browser öffnen. Eine Installation ist nicht nötig.

## Mitmachen

Fehler in einer Phraseologie entdeckt oder eine Idee für ein neues Szenario? Eröffne gerne ein [Issue](../../issues). Besonders willkommen ist fachliches Feedback von Fluglehrern und Prüfern.

## Lizenz

Code: MIT-Lizenz. Inhalte (Texte und Dialoge): CC BY-NC-SA 4.0.
