# Attributions and third-party inventory: matthewbroyer.com hub

Last reviewed: September 2026 (`index.html`, v5.5.0)

## Third-party code, fonts, images, services
None. The page loads no external scripts, stylesheets, fonts, images, analytics, ads, maps, or APIs.

| Item | Source | License / notes |
|---|---|---|
| Fonts | System fonts only (Segoe UI, system-ui, Roboto, Helvetica, Arial, platform monospace) | Already on the visitor's device; nothing is downloaded or redistributed |
| UI icons (search, arrows, star, mail, sun/moon, menu) | Hand-written inline SVG paths in `index.html` | Original to this project. If any were copied from an icon set (Feather, Lucide, Heroicons, etc.), add that set's license here (those are MIT/ISC, attribution in source is enough) |
| App logos (Money, Meal Prep, Action Plan, Auto, Reading, Gardening, 8 Ball) | Inline SVG copied from the operator's own sites | Operator-owned |
| "MB" favicon | Inline SVG | Operator-owned |

## Hosting
GitHub Pages (deployed by `.github/workflows/static.yml`). GitHub logs visitor IP addresses for security; see the GitHub Privacy Statement. GitHub Pages can't send custom HTTP headers, so framing protection is done by a small script at the top of `index.html`.

## Network requests the page can make
| Destination | When | What is sent |
|---|---|---|
| The seven `*.online` app domains | Only when the visitor presses **Check status** | A plain GET with a cache-busting `_mb_status` timestamp; no cookies, no Referer, no local data |
| Those same domains | When the visitor clicks Open / Launch | Normal navigation in a new tab (`noopener noreferrer`) |
| Visitor's email app | When the visitor clicks the email button | `mailto:` link, nothing is sent by the page itself |

If you add a library, font, image, or service later, list it here with its license.
