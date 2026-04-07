# Fadhl M. Alakwaa, PhD — Academic Website

Personal academic website for Fadhl M. Alakwaa, Assistant Research Scientist in the Department of Internal Medicine — Nephrology at the University of Michigan, Ann Arbor.

🌐 **Live site:** https://fadhlyemen.github.io

## About

Single-file static site (`index.html`) showcasing research, publications, software tools, training, and contact information. Built with vanilla HTML/CSS — no build step, no dependencies, zero maintenance.

## Files

| File | Purpose |
|---|---|
| `index.html` | The entire website (HTML + CSS in one file) |
| `headshot.jpg` | Profile photo (optional — site degrades gracefully if missing) |
| `README.md` | This file |

## Deployment (GitHub Pages)

1. Create a GitHub repository named exactly `fadhlyemen.github.io`
2. Upload `index.html`, `headshot.jpg`, and `README.md` to the repo
3. Go to **Settings → Pages**, select the `main` branch as source, and click **Save**
4. Wait 1–2 minutes — your site will be live at https://fadhlyemen.github.io

## Updating content

All content lives in `index.html`. To update:

- **Publications** — edit the publications section directly in the HTML
- **Stats** (paper counts, grants) — update the `.stat-card` numbers in the hero
- **Headshot** — replace `headshot.jpg` with a new square image (≥400×400 px recommended)
- **Links** — Google Scholar, GitHub, ORCID, and PubMed links are in the hero `.hero-links` block

Commit and push — GitHub Pages will rebuild automatically within a minute.

## Design

- **Colors:** University of Michigan brand (Navy `#00274C` + Maize `#FFCB05`)
- **Typography:** Serif headings, sans-serif body
- **Layout:** Responsive grid, mobile-friendly down to 360px width
- **Performance:** Single file, no external JS, no tracking, no cookies

## Contact

- 📧 Email: fadlawaa [at] med.umich.edu
- 🎓 [Google Scholar](https://scholar.google.com/citations?user=0_wKueAAAAAJ&hl=en)
- 📚 [PubMed](https://pubmed.ncbi.nlm.nih.gov/?term=fadhl+alakwaa)
- 💻 [GitHub](https://github.com/fadhlyemen)
- 🆔 [ORCID](https://orcid.org/0000-0001-5349-7960)
