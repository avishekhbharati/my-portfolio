# Avishekh Bharati — Portfolio

Personal portfolio site for Avishekh Bharati, Backend Software Engineer based in Melbourne.

## Structure

```
.
├── index.html          # Single-page portfolio
└── assets/
    ├── portrait.png            # Profile photo
    └── Avishekh_Bharati_CV.pdf # Résumé (linked from nav + contact section)
```

## Sections

- **Hero** — status pill, tagline, portrait, ID card
- **AI Workflow** — terminal demo of an agentic Claude Code session
- **Career Timeline** — switchable Spine / Index / Rail layouts; covers education and work from 2013 to present
- **Skills** — categorised tech stack with AI-integration block highlighted
- **Projects** — Victoria Crime Atlas
- **Contact** — email, phone, LinkedIn, GitHub, résumé download

## Local development

Open `index.html` directly in a browser — no build step required. All styles and scripts are self-contained in the HTML file.

## Deployment

Static site — deploy to any host that serves HTML:

```bash
# Vercel
vercel deploy

# GitHub Pages
# Push to a repo and enable Pages from the root of the main branch

# Netlify drag-and-drop
# Drop the project folder onto netlify.com/drop
```

## Assets

To update the portrait, replace `assets/portrait.png` with a 4:5 ratio image.

To update the résumé, replace `assets/Avishekh_Bharati_CV.pdf`.
