# Liedanzeige für Gottesdienste

Eine einfache Web-Anwendung zur Anzeige von Liednummern und Strophen
auf einem Beamer. Die Steuerung erfolgt über eine separate Seite
(control.html), die Anzeige über display.html.

## Funktionen

- Steuerseite mit Eingabefeldern für Buch, Liednummer und Strophen
- Dropdown mit freier Eingabe (datalist)
- Speichern von Liedern in einer lokalen Liste (localStorage)
- Löschen einzelner gespeicherter Einträge
- Anzeige-Seite mit:
  - großer, dynamisch angepasster Schrift
  - automatischer Zeilenumbruch-Erkennung
  - automatischer vertikaler Zentrierung
  - Ein-/Ausblenden über localStorage
- Funktioniert komplett offline
- Beamer benötigt keinen Browser (nur Spiegelung vom Handy)

## Nutzung

1. `control.html` auf dem Handy öffnen
2. `display.html` in einem zweiten Tab öffnen
3. Nur `display.html` auf den Beamer spiegeln
4. Liednummern und Strophen über die Steuerseite ändern

## Lizenz

MIT-Lizenz (optional)