# mxgao-a.github.io/personal-website

Source of my personal site: **https://mxgao-a.github.io/personal-website/** (Chinese version: **https://mxgao-a.github.io/personal-website/zh/**)

A single static page — plain HTML and CSS, no framework and no build step. GitHub Pages serves the repository root as-is.

| Path | What it is |
|---|---|
| `index.html` | The whole page. The hero chart is an inline SVG of real fitted SPX volatility smiles from [spx-vol-surface](https://github.com/MXGao-A/spx-vol-surface). |
| `zh/index.html` | The Chinese (Simplified) version of the page, same layout and charts. Edit it alongside `index.html`; the two link to each other from the nav. |
| `assets/style.css` | Styles, including light and dark themes and a `html[lang="zh-CN"]` block that adds system Chinese fonts (no CJK webfonts) |
| `assets/fonts/` | Self-hosted Newsreader and IBM Plex (SIL Open Font License) |
| `files/` | Résumé PDF |

To preview locally: `python -m http.server` in this folder, then open http://localhost:8000.
