# Website Crawler & Shop Generator

## Übersicht
Das Projekt **Website-Crawler** stellt eine automatisierte Pipeline zur Analyse von Webseitenstrukturen und zur schablonenbasierten Generierung von E-Commerce-Komponenten bereit.

## Projektstruktur & Architektur
- `generator/server.js`: Steuerungsdienst für den Generierungsprozess.
- `components/`: Wiederverwendbare UI-Bausteine.
- `skeletons/`: Grundgerüste für Ziel-Webseiten.
- `src/`: Skripte zur Datenextraktion und Strukturtransformation.

## Hauptfunktionalitäten
- **DOM-Struktur-Analyse**: Extraktion von Design-Mustern aus Zielseiten.
- **Schablonen-Generierung**: Erzeugung strukturierter HTML/CSS-Komponenten.
- **Modulare Pipeline**: Konfigurierbarer Arbeitsablauf für verschiedene Web-Typen.

## Ausführung & Nutzung
Der Start des Generierungsdienstes erfolgt im Ordner `generator/` über `node server.js` oder `npm start`.

## Lizenz
Dieses Projekt steht unter der MIT-Lizenz.
