# Kirchdorf Mangei – Eishockey Vereinsmanager

Spielbarer Offline-Web-Prototyp für iPhone, Android und PC.

## Start
`index.html` im Browser öffnen. Für GitHub Pages den Ordnerinhalt in ein Repository hochladen und unter Settings → Pages die Bereitstellung aus dem Hauptbranch aktivieren.

## Funktionen
- Eigene Vereinsgründung mit Startkapital
- Spielersuche, Einzelgespräche, Kaderaufnahme und Trainingsentwicklung
- Sponsorensuche, Vertragsverhandlungen, gestaffelte Zahlungseingänge
- Simulierte Gespräche mit der Gemeinde und Förderanträge
- Eiszeiten, Arena-Konzept und Finanzbuch
- Testspielgegner, Terminvereinbarung, Spielsimulation, Fanentwicklung
- Wochenfortschritt nur auf Knopfdruck
- Automatische lokale Speicherung, JSON-Export und -Import

## Wichtig
Alle Firmen, Personen, Gemeindeantworten und Spiele sind fiktiv. Keine echte Gemeinde oder Firma wird kontaktiert. Der Prototyp simuliert keine vollständige offizielle Liga. Der Aufbau ist als erweiterbare erste Version gedacht.

## Version 0.2
- Mehrstufige Spielergespräche mit unterschiedlichen Antworten und Konsequenzen
- Interaktive Gemeindegespräche mit Vertrauenssystem und Förderberatung
- Sponsorenangebote nachverhandeln
- Sponsoren-Zahlungsfälligkeit beim Vertragsabschluss festgelegt (nicht mehr bei jedem Wochenwechsel neu gewürfelt)

## Version 0.3
- Fiktive Tiroler Hobbyliga mit 8 Vereinen, 14 Spieltagen, Hin- und Rückrunde
- Ligaanmeldung gegen Gebühr, eigener Spielplan und laufende Tabelle
- Heimspiele benötigen ausdrücklich gebuchte Eiszeiten; sonst 0:5-Wertung
- Gegner spielen parallel, Ergebnisse wirken auf die Tabelle
- Tore und Torjägerliste, Spielberichte, Fitness und gelegentliche Blessuren
- Fehlerkorrektur: Sponsoren-Zahlungstermin bleibt stabil

## Version 0.4
- Personalverwaltung: Cheftrainer, Co-Trainer, Physiotherapie, Materialwart
- Individuelle Bewerbungsgespräche und Lohnverhandlungen
- Laufende wöchentliche Personalkosten und Kassenkontrolle
- Nachwuchsgründung, Talentsichtung und Nachwuchstraining
- Spielermarkt mit Transferverhandlungen
- Verbesserbare Trainings- und Medizinausstattung
- Bestehende Spielstände werden um neue Felder ergänzt

## Version 0.5
- Taktik- und Aufstellungsbereich: bis zu drei Sturmreihen und Verteidigungspaare
- Starter-Torhüter wählen, Spielstil, Forechecking und Überzahlstrategie festlegen
- Spielsimulation mit drei Dritteln, Torereignissen und Strafzeiten
- Detaillierte Spielberichte und Torschützen
- JavaScript-Syntaxfehler aus der vorigen Personalverwaltung korrigiert

## Version 0.6
- Vereinswelt mit Medienmeldungen und offenen Entscheidungen
- Spielerunzufriedenheit, Sponsorenerwartungen, Fanwünsche und Finanzwarnungen
- Beziehungen zu Fans, Mannschaft, Sponsoren und Gemeinde
- Fanabende und Pressegespräche mit auswählbaren Antworten
- Offene Konflikte werden nur durch Spielerentscheidungen gelöst

## Version 0.7 – Eigene Eisarena
- Drei fiktive Grundstücksoptionen mit unterschiedlichen Kosten und Risiken
- Standortwahl, Machbarkeitsstudie und Kapazitätsplanung
- Unverbindliche Gespräche mit Bank, Gemeinde und Investoren
- Baukalkulation mit Mindestanzahlung und expliziter Bau-Freigabe
- Projektfortschritt, Finanzierungswarnungen und Projektprotokoll
- Keine automatische Grundstücks- oder Bauverpflichtung
- Hinweis: Der Arenabau ist noch nicht bis zur Fertigstellung simuliert; weitere Bauphasen folgen.

## Version 0.8 – Arena und Spieltagswirtschaft
- Bauabschnitte müssen einzeln genehmigt und vollständig bezahlt werden
- Arenaeröffnung nach vollständiger Finanzierung der Baukosten
- Eintrittspreise von 5 bis 20 € pro Person einstellbar
- Gastronomie als optionale Investition
- Eigener Heimspielbetrieb mit expliziter Freigabe von 450 € pro Spiel
- Tatsächliche Zuschauereinnahmen und Wareneinsatz werden nur bei ausgetragenen Heimspielen gebucht
- Finanzbuch dokumentiert alle Ein- und Auszahlungen
- Fiktive Kalkulation; kein reales Bauprojekt oder echter Behördenkontakt

## Version 0.9 – Spielerkarrieren
- 26-Wochen-Spielerverträge, Verlängerungen nur nach Zustimmung
- Vertragsablauf und Warnungen vor auslaufenden Verträgen
- Verletzungsausfälle und Rückkehr nach Genesung
- Individuelle Karriereziele, Potenzial und altersabhängige Entwicklung
- Nachwuchsspieler ab 17 Jahren in die Kampfmannschaft übernehmen
- Spieler ausdrücklich freigeben
- Bestehende Spielstände erhalten Standardwerte für neue Karrierefelder

## Version 1.0 – Stabilisierung und Bedienung
- Alle elf Hauptbereiche durch einen automatisierten JavaScript-Rendertest geprüft
- Zusätzliche Vorstandswarnungen für Liquidität, Kader, Torhüter, Verträge und fehlende Heimspieleiszeit
- Ältere Speicherstände werden beim Laden/Import mit fehlenden Datenfeldern ergänzt
- Eindeutige Spieler- und Objekt-IDs werden nach Import auch aus Personal, Transfermarkt und Spielplan ermittelt
- Arenabau- und Stadionbetriebsbereich ist jetzt tatsächlich im Arena-Menü erreichbar
- Verbessertes mobiles Navigationsverhalten und größere Touch-Flächen
- Neustart aktualisiert die Oberfläche sofort

### Tests und Grenzen
JavaScript-Syntaxprüfung und automatisierte Render-Smoketests aller elf Bereiche erfolgreich.
Ein echter End-to-End-Test mit Browserinteraktionen war in der Testumgebung nicht möglich.
Langzeit-Saisonwechsel, Kredite und Stadionfinanzierung bleiben unvollständig; Version 1.0 bezeichnet den
Stabilisierungsstand, nicht die vollständige Fertigstellung aller geplanten Managerfunktionen.
