# Avishekh Bharati — Portfolio

> **Live site → [avishekhbharati.vercel.app](https://avishekhbharati.vercel.app/)**

Personal portfolio for Avishekh Bharati — Backend Software Engineer based in Melbourne. Single-page, no framework, no build step.

---

## Quick start

```bash
# Just open it — no install, no build
open index.html        # macOS
start index.html       # Windows
xdg-open index.html    # Linux
```

---

## What's on the page

| # | Section | What it does |
|---|---------|-------------|
| 01 | **Hero** | Status pill, tagline, portrait, quick-facts ID card |
| 02 | **AI Workflow** | Live terminal demo of an agentic Claude Code session — the differentiator |
| 03 | **Career Timeline** | Switchable **Spine / Index / Rail** layouts · 2013 → present |
| 04 | **Skills** | Categorised stack · AI-integration block visually highlighted |
| 05 | **Projects** | Victoria Crime Atlas — design through deploy with agentic tooling |
| 06 | **Contact** | Email · Phone · LinkedIn · GitHub · résumé download |

### Timeline layouts

The career timeline ships with three switchable views — pick the one you like and it persists in `localStorage`:

- **Spine** — alternating left/right cards around a central vertical line
- **Index** — minimal editorial list (year · type · content)
- **Rail** — horizontal scroll with a year axis

---

## File structure

```
.
├── index.html              # Entire site — styles, markup, and scripts in one file
└── assets/
    ├── portrait.png        # Profile photo (4:5 ratio)
    └── Avishekh_Bharati_CV.pdf
```

---

## Updating content

| What to change | Where |
|----------------|-------|
| Portrait photo | Replace `assets/portrait.png` — keep 4:5 ratio for best crop |
| Résumé PDF | Replace `assets/Avishekh_Bharati_CV.pdf` |
| Hero tagline / lede | `index.html` → `<header class="hero">` |
| Timeline entries | `index.html` → `<div class="career-timeline">` — add/edit `<article class="ev">` blocks |
| Skills | `index.html` → `<section id="skills">` |
| Project card links | `index.html` → `<section id="projects">` — add `href` to the project card |
| Contact details | `index.html` → `<section id="contact">` → `.contact-links` |

---

## Design system

| Token | Value | Usage |
|-------|-------|-------|
| `--bg` | warm off-white | Page background |
| `--ink` | near-black | Body text |
| `--accent` | technical blue | Highlights, active states |
| `--sans` | Geist | All body text |
| `--mono` | Geist Mono | Labels, eyebrows, terminal |

---

## Deployment

Deployed on **Vercel** — push to `main` to redeploy automatically (if Git integration is enabled).

```bash
# Manual deploy via CLI
vercel deploy          # preview
vercel deploy --prod   # production
```

Other static hosts also work:

- **GitHub Pages** — enable Pages from the root of `main`
- **Netlify** — drag the project folder onto [netlify.com/drop](https://app.netlify.com/drop)

---

## Meta / SEO

Open Graph and Twitter card tags are wired up in `<head>` pointing at the live domain. After any content change, verify the preview at [opengraph.xyz](https://www.opengraph.xyz).
