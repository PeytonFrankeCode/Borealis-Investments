# Borealis Investments

Informational site for Borealis Investments — an independent investor in
**upstream oil & gas** producing assets across North American basins. Built as a
single, self-contained `index.html` (no build step) using Google Fonts, inline
CSS/JS, and Leaflet for the investments map.

## Map

The "current investments" map uses [Leaflet](https://leafletjs.com/) with CARTO
dark tiles. Basin markers are defined in the inline `<script>` at the bottom of
`index.html` (the `assets` array) — edit that to change locations.

## Notes

The site makes no regulatory claims: Borealis is **not** a registered investment
adviser, and the footer disclaimer reflects that.

The logo is `assets/borealis-logo.png`. The site is deployed to GitHub Pages
via `.github/workflows/pages.yml` on every push to the default branch.

Placeholder to confirm: the actual basin positions shown on the map. Before
soliciting any investment, consult a securities attorney about registration
requirements.
