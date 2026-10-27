# ArcheoWalsie – Archaeological Find Spots in Wals-Siezenheim

🇩🇪 [Deutsche Version](README.de.md)

An interactive map of the archaeological find spots in the municipality of Wals-Siezenheim (Salzburg, Austria), for exploring them on foot.

**▶ Open the app: https://beyerl.github.io/ArcheoWalsie/**

## Features

- 97 find spots from the Stone Age to the modern era, colour-coded by epoch, with symbols for each find type (single find, settlement, grave, hoard, church, …)
- **Locate me** shows your GPS position, the nearest finds and the distance and direction to each one
- **Proximity alert** vibrates and shows a message when you come within 75 m of a find
- The original find map can be shown on top of the street, topographic or satellite map, with adjustable opacity
- Filter by epoch: tap a chip to toggle it, double-tap to show only that epoch
- Approximate course of the Roman road
- German and English interface: switch with the **DE | EN** button
- Right-click or long-press the map to test from any spot without GPS

## Data source and accuracy

The find spots come from the exhibition board *“Archäologische Fundstellenkarte Gemeinde Wals-Siezenheim – Gesamtübersicht über alle Epochen”* (A. Stollnberger, SAGIS data, 2019). They were digitised by hand from a photo of the board and fitted to real coordinates using five landmarks. **Positions are accurate to about ±50 m.**

## Please note

Many sites are on private land or are protected monuments. **Look, don't dig:** metal detecting and digging without a permit from the Bundesdenkmalamt are illegal in Austria.

## Technology

A single static HTML file using [Leaflet](https://leafletjs.com/), with no build step. Map tiles come from © OpenStreetMap contributors, OpenTopoMap and Esri. To run it locally, open `fundstellen-wals-siezenheim.html` in a browser. GPS needs https or localhost.
