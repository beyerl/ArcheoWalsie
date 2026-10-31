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
- Fachliteratur in den Infoboxen: Links zu frei zugänglichen Aufsätzen sowie gedruckte Werke zum Nachschlagen in der Bibliothek
- Oberfläche auf Deutsch und Englisch: umschalten mit der Schaltfläche **DE | EN**
- Rechtsklick oder langes Drücken auf die Karte simuliert einen Standort, ganz ohne GPS
- **AR-Ansicht** (im Menü): zeigt das Kamerabild mit Low-Poly-3D-Modellen aller Fundstellen im Umkreis von 2 km, anhand von Höhendaten ins Gelände gesetzt, dazu die Karte als Minikarte. Zum Kalibrieren die Einblendung ziehen, bis die rote Hütte auf dem Zeppezauerhaus am Untersberg sitzt; mit zwei Fingern den Bildwinkel anpassen

## Datenquelle und Genauigkeit

Die Fundstellen stammen von der Ausstellungstafel *„Archäologische Fundstellenkarte Gemeinde Wals-Siezenheim – Gesamtübersicht über alle Epochen“* (A. Stollnberger, SAGIS-Daten, 2019). Sie wurden von Hand aus einem Foto der Tafel digitalisiert und anhand von fünf Orientierungspunkten auf reale Koordinaten eingepasst. **Die Positionen sind auf etwa ±50 m genau.**

## Bitte beachten

**Bitte respektiere die Rechte der Grundeigentümer.** Die meisten Fundstellen liegen auf privaten Feldern, Wiesen oder Gärten. Betritt kein Privatgrund ohne Erlaubnis, bleib auf öffentlichen Wegen und betrachte die Stellen von dort aus. Manche Fundstellen sind zudem geschützte Denkmäler. **Schauen, nicht graben:** Metallsuche und Grabungen ohne Genehmigung des Bundesdenkmalamts sind in Österreich verboten.

## Technik

Eine einzelne statische HTML-Datei mit [Leaflet](https://leafletjs.com/), ohne Build-Schritt. Die AR-Ansicht lädt bei Bedarf [three.js](https://threejs.org/); die Geländehöhen sind EU-DEM-25-m-Daten über [OpenTopoData](https://www.opentopodata.org/). Die Kartenkacheln stammen von © OpenStreetMap-Mitwirkenden, OpenTopoMap und Esri. Lokal genügt es, `fundstellen-wals-siezenheim.html` im Browser zu öffnen. GPS, Kamera und Lagesensoren benötigen https oder localhost.
