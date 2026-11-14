# OBA Farm OS

A premium, mobile-first, offline-first poultry farm management application by OBA AgroTech.

## Product direction

- Dark forest interface with emerald, lime and turquoise accents.
- Mobile-first navigation for Home, Flocks, Records, Tools and Alerts.
- Local-first farm data using IndexedDB.
- Installable Progressive Web App foundation.
- JSON backup and restore.
- No paid API or cloud backend required for the initial foundation.

## Current foundation (0.1.0)

- Responsive application shell and navigation.
- Farm profile setup.
- Flock registration.
- Basic feed, water, mortality, weight, egg, expense and health record entry.
- Dashboard metrics and recent activity.
- Mortality, feed, water, egg production and broiler profit estimate calculators.
- JSON backup and restore.
- Service worker app-shell caching.

## Run locally

Serve this folder from a local web server. IndexedDB and service workers require a secure context (localhost is supported). Opening `index.html` directly as a file is not a supported test.

## Publish with GitHub Pages

1. Open repository **Settings → Pages**.
2. Under Build and deployment, choose **Deploy from a branch**.
3. Select branch **main** and folder **/(root)**, then Save.
4. Wait for GitHub Pages to publish the site.

## Important data note

Farm data is stored in this browser on this device. Clearing browser site data or changing devices can remove access to local records. Download and safely keep JSON backups. The restore function replaces the current local dataset after confirmation.

## Development status

This is an early foundation, not a production-ready farm management system. Migration from the legacy OBA AgroTech V1/V2 storage formats has not yet been implemented. Do not use it as the sole record keeper until backup/restore, calculations, offline behaviour and migration have been fully tested.

The existing `genzchamp/oba-agrotech` repository is separate and has not been modified by this project.
