# Changelog

All notable changes to the site are recorded here. Newest first.
Format based on [Keep a Changelog](https://keepachangelog.com/).

## [Unreleased]

### Added
- Interactive district map in the "Giá theo quận" tab (Leaflet 1.9.4, CARTO dark tiles with OpenStreetMap data, no API key).
  - One circle per district, coloured to match the other charts.
  - "Kích thước vòng tròn" dropdown sets circle size by YoY growth, land price or apartment price.
  - Clicking a circle selects the district and updates the bars and metrics; clicking a bar highlights its circle.
  - Every district label is always visible; the selected district also shows its role, land price and growth.
- `lat`, `lng` and `role` fields on each district in `DATA.districts`.

### Changed
- Leaflet CSS/JS loaded from unpkg CDN in `<head>`.

## 2026-05 — Earlier history

- Revised README with project details and observations.
- Initial commit and dashboard (tabs: prices, forecast, mortgage, yield, infrastructure).
