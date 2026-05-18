# Jeruson Paul Chinnathambi — Portfolio Website

A complete, self-contained portfolio website built as a single HTML page with linked research papers.

## What's inside

```
portfolio/
├── index.html                                    ← The website (open this)
├── assets/
│   └── headshot.png                              ← Your portrait
└── papers/
    ├── fintech-financial-inclusion-ieee.pdf      ← IEEE FinTech paper
    ├── ev-market-assessment-strategic-paper.pdf  ← EV market paper
    ├── apple-arm-chip-operations-logistics.pdf   ← Apple chip case study
    └── agricultural-drones-global-business-plan.pdf  ← Drones business plan
```

## How to view it locally

Just double-click `index.html` — it opens in any modern browser.

## How to publish it for free

The easiest way to put this online so recruiters can visit it:

### Option 1 — Netlify Drop (no signup needed for first deploy)
1. Go to https://app.netlify.com/drop
2. Drag the entire `portfolio` folder onto the page
3. You get a public URL in ~10 seconds (e.g. `something-random.netlify.app`)
4. (Optional) sign in to claim it permanently and customize the URL

### Option 2 — GitHub Pages
1. Create a new public repo on GitHub (e.g. `jeruson-portfolio`)
2. Upload the contents of the `portfolio` folder
3. In repo Settings → Pages → set source to `main` branch, `/` root
4. Your site lives at `https://<your-username>.github.io/jeruson-portfolio/`

### Option 3 — Vercel
1. Push the folder to GitHub, then import the repo at https://vercel.com/new
2. Click deploy. Free for personal projects.

## How to edit content later

Everything is in **`index.html`** — open it in any text editor (VS Code, Notepad, TextEdit). Search for text you want to change and edit it directly. The structure is commented (`<!-- HERO -->`, `<!-- ABOUT -->`, etc.) so it's easy to find sections.

To add a new research paper:
1. Drop the PDF into the `papers/` folder
2. Find the `<!-- RESEARCH -->` section in `index.html`
3. Copy one of the existing `<a class="paper">` blocks and update the filename, title, and description

## Design notes

- **Fonts:** Fraunces (display serif) + Manrope (body) + JetBrains Mono (accents) — loaded from Google Fonts
- **Theme:** Editorial / warm cream palette with copper accents — designed to feel polished and professional, not like a typical tech-bro template
- **Fully responsive:** works on phone, tablet, and desktop
- **No build step:** pure HTML/CSS/JS, no frameworks, no compilation
