# Italia Travel 2026

A small static GitHub Pages webpage for the northern Italy trip itinerary, with daily/hourly weather fetched client-side from Open-Meteo.

## Files

- `index.html` — the whole webpage: itinerary, styling, and JavaScript weather integration.
- `robots.txt` — discourages search engines from crawling the page.
- `.nojekyll` — tells GitHub Pages not to process this as a Jekyll site.

## How to publish at `/italia_travel_2026/`

### Option A: User site repository

1. Open or create your `YOUR_GITHUB_USERNAME.github.io` repository.
2. Upload the entire `italia_travel_2026` folder to the repository root.
3. Enable GitHub Pages for the repository root.
4. Visit:

```text
https://YOUR_GITHUB_USERNAME.github.io/italia_travel_2026/
```

### Option B: Project site repository

1. Create a public repository named `italia_travel_2026`.
2. Upload `index.html`, `robots.txt`, and `.nojekyll` to that repository root.
3. Enable GitHub Pages from the root of the main branch.
4. Visit:

```text
https://YOUR_GITHUB_USERNAME.github.io/italia_travel_2026/
```

## Privacy note

This is a hidden-by-URL page, not a secure private page. The HTML includes `noindex,nofollow` and `robots.txt`, but anyone with the URL may be able to open it once it is published on GitHub Pages. Do not add passport numbers, booking codes, phone numbers, or other sensitive data.

## Weather note

The page uses the Open-Meteo Forecast API directly from the visitor's browser. Open-Meteo's forecast horizon is limited, so later trip dates may show a “check closer to the day” message until they come into range.
