# Hugo Upload Instructions

This zip contains a minimal structure to drop into an existing **Hugo** site.

## Option A — Quick (no theme)
1. Unzip into your Hugo project root.
2. This provides `static/index.html` which Hugo will serve at `/` unchanged.
3. Put your headshot image at `static/headshot.jpg` (same name), and your CV at `static/cv.pdf`.
4. Run: `hugo server -D`

## Option B — Use as content template
If you prefer using Hugo layouts/partials, move `static/index.html` into
`layouts/index.html` and split into partials as needed. You can also convert sections to Markdown under `content/` and reference them from a layout.

---
Made to match the canvas version you approved.
