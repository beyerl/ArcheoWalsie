# ArcheoWalsie – Archäologische Fundstellen in Wals-Siezenheim

🇬🇧 [English version](README.md)

Eine interaktive Karte der archäologischen Fundstellen in der Gemeinde Wals-Siezenheim (Salzburg), um sie zu Fuß zu erkunden.

**▶ App öffnen: https://beyerl.github.io/ArcheoWalsie/**

## Funktionen

- 97 Fundstellen von der Steinzeit bis zur Neuzeit, farbig nach Epoche, mit eigenen Symbolen je Fundart (Einzelfund, Siedlung, Grab, Hortfund, Kirche, …)
- **Mein Standort** zeigt die GPS-Position, die nächstgelegenen Fundstellen sowie Entfernung und Richtung zu jeder davon
- **Näherungsalarm** vibriert und zeigt eine Meldung, sobald du weniger als 75 m von einer Fundstelle entfernt bist
- Die Originalkarte lässt sich über Straßen-, Topo- oder Satellitenkarte legen, mit einstellbarer Deckkraft
- Filter nach Epoche: Antippen schaltet eine Epoche ein oder aus, Doppeltippen zeigt nur diese Epoche
- Ungefährer Verlauf der Römerstraße
- Oberfläche auf Deutsch und Englisch: umschalten mit der Schaltfläche **DE | EN**
- Rechtsklick oder langes Drücken auf die Karte simuliert einen Standort, ganz ohne GPS

## Datenquelle und Genauigkeit

Die Fundstellen stammen von der Ausstellungstafel *„Archäologische Fundstellenkarte Gemeinde Wals-Siezenheim – Gesamtübersicht über alle Epochen“* (A. Stollnberger, SAGIS-Daten, 2019). Sie wurden von Hand aus einem Foto der Tafel digitalisiert und anhand von fünf Orientierungspunkten auf reale Koordinaten eingepasst. **Die Positionen sind auf etwa ±50 m genau.**

## Bitte beachten

Viele Fundstellen liegen auf Privatgrund oder sind geschützte Denkmäler. **Schauen, nicht graben:** Metallsuche und Grabungen ohne Genehmigung des Bundesdenkmalamts sind in Österreich verboten.

## Technik

Eine einzelne statische HTML-Datei mit [Leaflet](https://leafletjs.com/), ohne Build-Schritt. Die Kartenkacheln stammen von © OpenStreetMap-Mitwirkenden, OpenTopoMap und Esri. Lokal genügt es, `fundstellen-wals-siezenheim.html` im Browser zu öffnen. GPS benötigt https oder localhost.
