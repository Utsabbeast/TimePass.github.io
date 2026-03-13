# TimePass Drawing 

> *A classical ink-and-brush drawing canvas wrapped in black-and-white anime samurai artwork.*

---

## Live Demo

Hosted on GitHub Pages:
```
https://utsabbeast.github.io/TimePass.github.io/
```

---

## About

TimePass Drawing is a browser-based digital canvas inspired by classic black-and-white anime — Vagabond, Lone Wolf and Cub, and Berserk. Two hand-drawn ronin samurai characters flank the canvas: The Wanderer on the left, The Warrior mid-slash on the right. The entire UI is built in a single self-contained HTML file — no frameworks, no dependencies, no build step.

The canvas renders a procedurally generated rice-paper texture on load, giving every drawing an ink-on-parchment feel.

---

## Features

| Feature | Details |
|---|---|
| **Pen tool** | Smooth continuous ink strokes at exact user-set size |
| **Marker tool** | Semi-transparent square-tip brush, same size as set |
| **Eraser tool** | Paints back the rice-paper colour, exact size as set |
| **Size slider** | 1–50 px, applies directly to all tools with no multiplier |
| **Opacity slider** | 5–100%, controls pen and marker transparency |
| **Colour picker** | Full colour wheel for pen and marker |
| **Undo / Redo** | Up to 40 steps stored in memory |
| **Rice paper canvas** | Procedural pixel-noise + fibre texture on every load and clear |
| **Touch support** | Works on mobile and tablet with `touchstart` / `touchmove` |
| **Keyboard shortcuts** | See table below |

### Keyboard Shortcuts

| Key | Action |
|---|---|
| `P` | Switch to Pen |
| `M` | Switch to Marker |
| `E` | Switch to Eraser |
| `Ctrl + Z` | Undo |
| `Ctrl + Y` | Redo |

---

## Design

- **Palette** — Strictly monochrome. The only colour on the page is a single deep crimson (`#7a0000`) hanko seal stamp reading **कला** (Art).
- **Typography** — `Cinzel` (display, headers) + `Tiro Devanagari Hindi` (subtext, captions, watermarks).
- **Characters** — Two fully hand-crafted SVG samurai rendered with manga screen-tone dot patterns, cross-hatch shading, motion blur trails, radial speed lines, and proper anatomical detail (hakama pleats, geta sandals, tsuba guard, cloth-wrapped hilt, topknot).
- **Animations** — Subtle character sway, ink-drop rainfall in the background, pulsing hanko seal.
- **Canvas mount** — Styled as a traditional scroll with dark wood rod borders and brass endcaps.

### Hindi text reference

| Text | Meaning |
|---|---|
| स्याही और कूची | Ink and Brush |
| कला | Art |
| योद्धा | Warrior |
| भटकता योद्धा | The Wandering Warrior |
| मार्ग | The Path |
| एकाकी योद्धा | The Lone Warrior |
| स्याही | Ink |

---

## File Structure

```
timepass-drawing/
├── index.html      ← entire app (HTML + CSS + JS + SVG, self-contained)
└── README.md
```

No external assets. No npm. No bundler. Everything is inline.

---

## Deploying to GitHub Pages

1. Create a new **public** repository on GitHub
2. Upload `timepass-ronin.html` renamed as **`index.html`**
3. Go to **Settings → Pages → Branch: main → Save**
4. Your site is live at `https://utsabbeast.github.io/TimePass.github.io/` within ~60 seconds

To update: edit `index.html` directly in GitHub's web editor and commit. The site redeploys automatically.

---

## Browser Support

Works in all modern browsers — Chrome, Firefox, Safari, Edge. Uses standard Canvas 2D API with no polyfills required.

---

## License

Free to use, modify, and share.

---

*Draw anything · Be free · Conquer the time*
