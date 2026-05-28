# Selina & Gino's Home

Shareable idealista-style listing page for the apartment at Carrer d'Astúries 23, Gràcia, 08012 Barcelona.

## What this is
The idealista listing (inmueble/111501398) was recreated as a single self-contained HTML page so it can be shared with friends and family after the original listing is taken down.

## Files
- `index.html` — Single HTML file with all CSS/JS inline. Photos referenced from `photos/` directory.
- `photos/` — 30 listing photos as `.webp` files (plus 3 duplicate `-1` suffix files from the original download).
- `page-source.html` + `page-source/` — Original saved idealista page source, kept for reference.

## Features
- Photo gallery with fullscreen lightbox (click header image to open, Escape to close)
- Keyboard arrows + touch/swipe navigation
- **Price toggle**: append `?price=true` to the URL to show the listing price (620,000 €). Hidden by default.
- Property description, specs, energy certificate, Google Maps embed
- Responsive/mobile-friendly

## Hosting
Designed for GitHub Pages or any static file host. Just serve the root directory.

## Price param examples
- Without price: `https://yourdomain.com/`
- With price: `https://yourdomain.com/?price=true`
