# AGENTS.md

## Overview

Static HTML landing page for a hotel investment opportunity. No build process required.

## Files

- `hotel-en-venta.html` - Main landing page (Spanish)
- `hotel-for-sale.html` - English version (created from english.md)
- `english.md` / `spanish.md` - Marketing content (source for translations)
- `images/` - Hotel photos organized by category

## Repository

Code and images are hosted on GitHub: https://github.com/psabbag/hotelcristal

To push updates:
```bash
git add .
git commit -m "message"
git push origin main
```

## Image URLs

Images use absolute GitHub URLs to work on external platforms (Google Sites, etc.):
```
https://raw.githubusercontent.com/psabbag/hotelcristal/main/images/...
```

**Important:** When editing, use the full URL (not relative paths). The replaceAll trick works but be careful of duplication.

## Editing

Edit directly in the HTML files. Each file is self-contained with embedded CSS. No build step needed - open in browser to preview.

## Images

Photos are in `images/` subdirectories:
- `habitaciones/` - Room photos
- `recepcion/` - Lobby/reception photos
- `desayuno/` - Breakfast area photos
- `frente/` - Building exterior photos
- `ciudad/` - City/landmark photos
- `patios/` - Courtyard photos

## Live Pages

- Spanish: https://psabbag.github.io/hotelcristal/hotel-en-venta.html
- English: https://psabbag.github.io/hotelcristal/hotel-for-sale.html