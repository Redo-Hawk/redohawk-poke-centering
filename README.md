# Pokémon Card Centering Tool

Free, open-source, single-file web app to measure trading card **centering** from a photo — the same metric PSA, BGS, CGC and PCA use for grading.

**[→ Try it live](https://redo-hawk.github.io/redohawk-poke-centering/)** — no install, no account, no server. Everything runs in your browser; your photos never leave your device.

![status](https://img.shields.io/badge/status-active-brightgreen) ![license](https://img.shields.io/badge/license-MIT-blue)

## What it does

1. Drop a photo of your card (front or back).
2. Click the 4 **outer corners** (physical card edge) — rounded-corner guide included, since Pokémon cards aren't sharp-cornered rectangles.
3. Click the 4 **inner corners** (printed frame).
4. Get instant **L/R** and **T/B** centering percentages, plus a predicted grade for **PSA, BGS, CGC and PCA** side by side — their tolerances are all different, so the same card can be a PSA 10 and a BGS 8.5 at once.
5. Optional "Worth grading?" calculator (fees, shipping, raw vs. graded value → net/ROI).
6. Download a shareable PNG report + a simulated slab preview.

## Why

Centering is one of the most punishing and most misunderstood grading criteria. Most people don't realize the big grading companies use *different* tolerance tables — this tool makes that visible before you pay to submit a card.

## Tech

Single `index.html`. No build step, no dependencies, no backend. Pure HTML/CSS/JS + Canvas + SVG. Works offline once loaded.

## Contributing

PRs welcome — this is for the Pokémon/TCG community, not a product.

Ideas that would help:
- Auto-detect card corners (edge detection) to reduce manual clicking
- More grading companies / updated tolerance tables if you have sourced data
- Better rounded-corner guide UX
- Localization / i18n support
- Mobile touch refinements

To contribute: fork, edit `index.html` directly (it's the whole app), open a PR describing what changed and why. Keep it dependency-free if possible — that's the whole point of a single portable file.

## Disclaimer

This is a **centering-only** estimate to help you decide whether a card is worth submitting. It is not affiliated with PSA, Beckett/BGS, CGC or PCA, and does not replace an official grade — final grades also depend on corners, edges and surface, assessed by the grading company under their own equipment and lighting.

## License

MIT — do whatever you want with it, see [LICENSE](LICENSE).
