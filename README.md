# Date Night Roulette — web edition

Free date-night adventures based on budget, setting, energy and available time.

This repository contains the public browser app for GitHub Pages. It uses plain HTML, CSS and JavaScript, with no build step, backend account, paid API, ads, or subscription. The Android development project is maintained separately.

## Publishing and updates

In repository Settings → Pages, publish from `main` and `/(root)`. `.nojekyll` disables Jekyll processing. Each committed update to these website files automatically republishes through GitHub Pages.

Keep `index.html`, `style.css`, `app.mjs`, and `ideas.mjs` together at the repository root. When updating from the development project, copy its `dist/` contents here and commit the result. The two repositories do not synchronize automatically.

## Data and privacy

Date generation runs locally using a built-in library. Favorites and preferences use browser localStorage. No GPS, analytics or advertising SDK is installed. Clicking a nearby-place link sends a search and optional city to Google Maps. Styles may request Google Fonts; GitHub and external providers handle network requests under their own policies.

Favorites saved on a different website address do not automatically carry over. At-home free ideas assume existing supplies. Costs are illustrative USD estimates for two, excluding transport; verify venue prices, hours and suitability.

Free to use does not grant a source-code license; no open-source license has been selected.
