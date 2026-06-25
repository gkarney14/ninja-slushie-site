# Ninja Slushi Recipes

A small site for scalable slushi-machine recipes — four batches, each treated as a working formula rather than a static ingredient list.

**Live site:** see GitHub Pages URL once deployed (Settings → Pages on this repo).

## What's here

- **Coconut-Lime Rum** (21+, SPIKED SLUSH) — Malibu-based, live ABV gauge
- **Hurricane** (21+, SPIKED SLUSH) — classic two-rum tiki build, live ABV gauge
- **Piña Colada — Kids** (alcohol-free, SLUSH) — live sugar-floor gauge
- **Red Slushie — Kids** (alcohol-free, SLUSH) — live sugar-floor gauge

Each card has a batch-size slider. Ingredient amounts rescale proportionally, and the relevant constraint — ABV for the rum drinks, sugar-floor percentage for the kids' drinks — recalculates live so you can see at a glance whether a batch is in a safe/working range before you load the machine.

## Structure

Single self-contained `index.html` — no build step, no dependencies beyond Google Fonts (Space Grotesk / Inter / IBM Plex Mono). Deployable as-is via GitHub Pages.

## Local preview

Just open `index.html` in a browser, or serve it:

```
python3 -m http.server 8000
```
