# almira-portfolio

Personal portfolio for **Almira Hanafiah**, AI Product Designer at Brim, London.

Hand-coded HTML, CSS, and JavaScript. No framework, no build step. Deploys to any static host.

## Run locally

Open `index.html` in a browser. That's it. There's no install step.

For a slightly nicer dev loop with live reload, you can run a local server:

```bash
python3 -m http.server 8000
# then open http://localhost:8000
```

## Deploy

The site is designed to deploy as the root of a GitHub Pages repo. Pushing this folder to a `main` branch and enabling Pages on `main / root` should be enough. Netlify or Vercel drag-and-drop also works.

## Pages

| Path | What it is |
|---|---|
| `index.html` | Homepage with the hero, the work index, and the colophon footer |
| `about.html` | About page, three labelled blocks plus a horizontal-scroll photo gallery |
| `play.html` | Gallery of traditional art, masonry layout, data-array pattern (edit one list to add a piece) |
| `work/ai-workflows.html` | Case Study 01, AI-native workflows at Brim, with sticky table of contents |
| `case-study-template.html` | A duplicatable template for Cases 02 and 03 |

## Structure

```
.
├── CLAUDE.md                    Project briefing for Claude Code (read first)
├── README.md                    This file
├── index.html                   Homepage
├── about.html                   About
├── play.html                    Play gallery
├── work/
│   └── ai-workflows.html        Case study 01
├── case-study-template.html     Case study template
├── assets/
│   ├── play/                    Photos for the play gallery
│   ├── about/                   Photos for the about gallery
│   ├── case-01/                 Assets for case study 01
│   └── cv/                      CV PDF goes here
└── docs/
    ├── portfolio-spec.md        Overall portfolio spec
    ├── case-studies-plan.md     Case study writing plan
    └── voice-guide.md           Voice and writing rules
```

## What's done, what's not

**Done:** Homepage, About, Play gallery, Case Study 01 in full.
**To do:** Wire up navigation links across pages, build `cv.html`, write Case Studies 02 and 03, drop in real images, push to GitHub Pages.

## Visual system

Inter at weight 200, warm near-white background, dusty rose pink accent. Full token list in `docs/portfolio-spec.md`.

## Voice rules

No em-dashes. No "X, not Y" rhetorical parallelism. Longer flowing sentences. Process-narration style. Full guide in `docs/voice-guide.md`.

---

Set in Inter. Built by hand, 2026.
