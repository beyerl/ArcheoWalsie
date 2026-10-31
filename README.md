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
- Scholarly literature in the info boxes: links to freely accessible papers, plus printed works to look up in a library
- German and English interface: switch with the **DE | EN** button
- Right-click or long-press the map to test from any spot without GPS
- **AR view** (in the menu): shows the camera image with low-poly 3D models of all finds within 2 km, placed on the terrain using elevation data, with the map as a minimap. To calibrate, drag the overlay until the red hut sits on the Zeppezauerhaus on the Untersberg; pinch to adjust the field of view

## Data source and accuracy

The find spots come from the exhibition board *“Archäologische Fundstellenkarte Gemeinde Wals-Siezenheim – Gesamtübersicht über alle Epochen”* (A. Stollnberger, SAGIS data, 2019). They were digitised by hand from a photo of the board and fitted to real coordinates using five landmarks. **Positions are accurate to about ±50 m.**

## Please note

**Please respect landowners' rights.** Most sites lie in private fields, meadows or gardens. Do not enter private land without permission; stay on public paths and view the sites from there. Some sites are also protected monuments. **Look, don't dig:** metal detecting and digging without a permit from the Bundesdenkmalamt are illegal in Austria.

## Technology

A single static HTML file using [Leaflet](https://leafletjs.com/), with no build step. The AR view loads [three.js](https://threejs.org/) on demand; terrain heights are EU-DEM 25 m data via [OpenTopoData](https://www.opentopodata.org/). Map tiles come from © OpenStreetMap contributors, OpenTopoMap and Esri. To run it locally, open `fundstellen-wals-siezenheim.html` in a browser. GPS, camera and motion sensors need https or localhost.
