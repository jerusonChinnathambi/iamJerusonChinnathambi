# Jeruson Paul Chinnathambi — Portfolio Website

A complete, self-contained portfolio website built as a single HTML page with linked research papers.

## What's inside

```
portfolio/
├── index.html                                       ← The website (open this)
├── assets/
│   └── headshot.png                                 ← Your portrait
└── papers/
    ├── redbull-marketing-ml-analytics.pdf           ← Red Bull marketing ML paper
    ├── fintech-financial-inclusion-ieee.pdf         ← IEEE FinTech paper
    ├── ev-market-assessment-strategic-paper.pdf     ← EV market paper
    ├── apple-arm-chip-operations-logistics.pdf      ← Apple chip case study
    └── agricultural-drones-global-business-plan.pdf ← Drones business plan
```

## IMPORTANT — uploading to GitHub Pages

GitHub Pages serves from a case-sensitive Linux server. For the image and
papers to load, you MUST upload BOTH folders, not just index.html:

1. On your repo page, click "Add file" → "Upload files"
2. Drag the ENTIRE `assets` folder AND the ENTIRE `papers` folder onto GitHub
   (drag the folders themselves so the structure is preserved)
3. Commit the changes
4. Wait ~1 minute, then hard-refresh your site (Cmd + Shift + R)

Your repo should show: index.html, assets/, papers/ — all at the top level.

## How to view it locally

Just double-click `index.html` — it opens in any modern browser.

## How to edit content later

Everything is in `index.html`. Open it in a text editor, search for the text
you want to change, and edit directly. Sections are commented
(<!-- HERO -->, <!-- RESEARCH -->, etc).

To add a new research paper:
1. Drop the PDF into the `papers/` folder
2. Find the <!-- RESEARCH --> section in index.html
3. Copy an existing <a class="paper"> block, update the filename + title + text

## Design notes

- Fonts: Fraunces (display serif) + Manrope (body) + JetBrains Mono (accents)
- Editorial / warm cream palette with copper accents
- Fully responsive; no build step; pure HTML/CSS/JS
