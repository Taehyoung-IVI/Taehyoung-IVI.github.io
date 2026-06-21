# Italia Travel 2026 v3

Static GitHub Pages site for the Northern Italy trip.

## Deploy

Copy this folder as `italia_travel_2026` inside `Taehyoung-IVI.github.io`, then commit and push.

The page will be available at:

https://Taehyoung-IVI.github.io/italia_travel_2026/

## v3 changes

- Korean/English toggle now changes the full UI, itinerary summaries, notes, checklist labels, weather text, and map button labels.
- Checklist is interactive and saves completion state in the browser using localStorage.
- Address privacy toggle remains available.


## v4 note

The reservation checklist is intentionally read-only on the public page. It does not use browser localStorage and does not save per-person changes, so everyone sees the same status from the deployed file. To update an item, edit the `CHECKLIST` data in `index.html` and redeploy.
