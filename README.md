# Ninja Slushi Recipes

A single-page site with nine scalable slushi-machine recipes — each built as a working formula with live-updating ingredient amounts, ABV or sugar gauges, and a fun meter.

**Live site:** https://gkarney14.github.io/ninja-slushie-site/

## Recipes

### Spiked (21+ · SPIKED SLUSH preset)

| Recipe | ABV | Drunk-O-Meter |
|---|---|---|
| Coconut-Lime Rum | 7.0% | Basically Juice |
| Hurricane | 13.3% | Someone's Problem |
| Margarita | 12.8% | Someone's Problem |
| Painkiller — Soggy Dollar | 7.8% | Feeling Yourself |
| Blue Hawaiian | 9.2% | Dance Floor Threat |
| Frozen Espresso Martini | 11.7% | Texting Exes |

### Alcohol-Free (SLUSH preset)

| Recipe | Sugar | Sugar Rush-O-Meter |
|---|---|---|
| Blue Raspberry Lemonade | ~19% | Wall Climbing |
| Piña Colada — Kids | 14.1% | Circus Mode |
| Red Slushie — Kids | 21.4% | God Help You |

## Features

- **Batch-size slider** — 16 oz to 72 oz. Every ingredient amount rescales proportionally.
- **Live ABV gauge** — SVG arc tracks final ABV against the machine's 2.8%–16% safe window. Status badge flips between within range / below minimum / over limit.
- **Live sugar gauge** — percentage readout for alcohol-free builds, confirming the mix clears the machine's ~4% sugar floor.
- **Drunk-O-Meter™** — 5-level color bar with emoji verdict for spiked recipes.
- **Sugar Rush-O-Meter™** — 5-level color bar with emoji verdict for kids recipes.

## Structure

Single self-contained `index.html` — no build step, no dependencies beyond Google Fonts (Space Grotesk / Inter / IBM Plex Mono). Deployable as-is via GitHub Pages.

## Local preview

```
python3 -m http.server 8000
```
