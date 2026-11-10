# SVG Studio PRO

**From a sentence to a symbol.** Descriptive SVG Studio PRO turns plain-language
descriptions in English or Persian into clean, scalable vector logos, wordmarks and
icon sets. It runs entirely in the browser , no account, no upload, no server.

## Smart parser (v2)

`studio.html` scores the brand + tagline + description against a keyword
registry (`ICON_KEYWORDS`, EN + FA) and picks the best icon, showing the
Top-3 suggestions with scores so you can tap to switch. A phrase match
scores 6, a long word 4, a short word 3. No match falls back to a neutral
Star instead of a random icon. The set now has **34 vector icons + Custom
SVG** (20 original + 8 Web3: Blockchain Chain, Crypto Coin, Crypto Wallet,
Decentralized Network, Metaverse Cube, Smart Contract, DeFi Chart, NFT Token;
6 product/lifestyle: Store, Shopping Bag, Food, Car, Home, Music).

To add icon #35: add its SVG to `ICONS`, one `<option>` to the `#icon`
select, and one keyword line to `ICON_KEYWORDS` — the parser needs no
other change.

## Palettes & Flat 2D

15 palettes: 9 gradient/neon originals + 6 matte ones (Slate, Sage, Clay,
Sand, Navy, Teal — muted, low-saturation accents). Words like `matte`,
`flat`, `ساده`, `مات` or `تخت` in the description auto-pick Matte Slate.

**Flat 2D** (`Design Style` in the Icon & Palette card) works with any
palette: the `#g` gradient collapses to a solid accent colour, the
background gradient becomes solid, the ambient glow and drop shadows are
removed, and the 3D typography styles fall back to solid text — a true
flat, two-dimensional mark with no depth effects.

## Files

- `index.html` — landing page (product, slogan, engine vocabulary, creator)
- `studio.html` — the studio app
- `assets/` — logo, favicon, creator avatar

## Run locally

Open `index.html` directly, or serve the folder:

```bash
python3 -m http.server 8000
```

Then open <http://localhost:8000>.

## Deploy to GitHub Pages

1. Create the `Nassami1/svg-studio` repository on GitHub.
2. Push this folder's `main` branch.
3. Repository **Settings → Pages → Deploy from a branch → `main` / root → Save**.
4. The site is published at <https://nassami1.github.io/svg-studio/>.

## Made by

Hassan Samimi — [X](https://x.com/hassan_samimi) ·
[LinkedIn](https://www.linkedin.com/in/hassan-samimi) ·
[GitHub](https://github.com/Nassami1)
