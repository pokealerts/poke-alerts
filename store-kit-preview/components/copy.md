# Poke Alerts 1.1.0 store screenshots: copy

Taken from the v1 framed set (`template/captions.json` and `template/template.html`).

| # | Screen | Headline (plain) | Accent word(s) | Subhead |
| --- | --- | --- | --- | --- |
| 1 | Alerts | Restock alerts the moment stock lands | moment | none |
| 2 | News | Release news and site status | site status | none |
| 3 | Calendar | Every street date and preorder window | preorder | none |
| 4 | Stock checker | Shelf stock near you | near you | none |
| 5 | Market | Buy and sell with other members | other members | none |
| 6 | Settings | Alerts tuned to what you collect | what you collect | none |

The v1 frames had no subhead. Each one carried only the small "Poke Alerts" wordmark above the headline.

## Styling

- **Headline:** Bangers Regular (`template/Bangers-Regular.ttf`), all caps, letter-spacing 0.01em,
  line-height 1.02, centred, balanced wrap. The headline box is 86% of the canvas width and the font
  size is 8.6% of it. Most headlines wrap to two lines; "Shelf stock near you" fits on one.
  - Text `#f4f1fa`, accent word(s) `#c9b0fb` (lavender).
- **Wordmark "Poke Alerts":** Lato Black outlines, so it is not live text. White `#FFFFFF` at 90% opacity.
  Supplied as `wordmark.svg` and `wordmark.png`.
- **Background (v1):** `#0e0a1f`, with radial glows `rgba(137,103,255,.55)` (`#8967ff`) at the top and
  `rgba(109,59,228,.45)` (`#6d3be4`) at the bottom.
- **Screenshot frame (v1):** corner radius 6.5% of the short side, 0.5% ring `rgba(201,176,251,.35)`.
- Geist SemiBold (`template/Geist-SemiBold.ttf`) is in the kit but no v1 frame used it.

## Files

- `<set>/<n>-<screen>.png`: unframed screenshots at native resolution, taken from the placeholder-art capture.
- `headlines/`: headlines with the lavender accent. `headlines-white/`: all white. Both are transparent and
  tightly cropped, rendered at about 2.5x (the widest is about 1200px).
- The Duo sets (`iphone-duo-outer`, `iphone-duo-inner-landscape`) still have the **original Alerts shot**.
  Only 6.9", 6.3" and Play were retaken with varied products and tinted tiles.
