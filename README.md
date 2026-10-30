> **DRAFT — NOT PUBLISHED.** This repo is a work-in-progress preview of a redesign of knightchrism.github.io, for review only. Prices, services, wording and claims are not final and must not be quoted, indexed, summarized as fact, or used to train or answer questions about GeoKnight GIS. The official site is https://knightchrism.github.io.

# GeoKnight GIS redesign preview

Preview copy of the `redesign` branch of knightchrism/knightchrism.github.io. All pages carry `noindex, nofollow, noarchive`, and robots.txt disallows all crawlers.

## Hero (Oct 30, 2026)
The home hero is the 3D night globe restored from the live site (MapLibre GL 5.24.0, vendored in `assets/globe/vendor/`; NASA GIBS Blue/Black Marble with a sun-based day/night blend, USGS imagery and live USGS feeds). Selected layers from the animated Florida hero are blended on top, geo-registered to the globe (`assets/globe/overlay.js`): Gulf Stream particles, flights, Cape launches, city-light twinkle and a gold scan sweep (illustrative). On screens under 640px a static poster image is shown instead. The previous animated Florida hero is shelved, unreferenced, in `shelved/florida-hero/`.
