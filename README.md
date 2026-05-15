# Asuka Tiny Home

A tiny-world home for Asuka Langley Soryu, built from Jason Kneen's Tiny World Builder.

- `index.html` / `asuka-tiny-home.html`: the live web page
- `asuka-status.json`: live resident state consumed by the page
- `asuka-tiny-home.world.json`: exported world layout

The public page is static. A local Hermes cron job updates `asuka-status.json` and pushes changes to GitHub Pages.
