# Leruo Motlhamme — Portfolio Website

> Personal portfolio built with HTML, CSS & JavaScript.
---

## Overview

A single-page portfolio animated with [GSAP ScrollTrigger](https://gsap.com/docs/v3/Plugins/ScrollTrigger/). The design follows a dark, minimal aesthetic with gold accents and editorial typography.

**Live:** [leruo.dev](https://leruo.dev) *(update with your actual URL)*

---

## Panels

| # | Panel | Description |
|---|-------|-------------|
| 1 | **Hero** | Name, role & staggered entrance animation |
| 2 | **Get to Know Me** | Pinned section with ghost initials & corner details |
| 3 | **About** | Slides in over panel 2 — bio + what I work on |
| 4 | **CTA** | Contact call-to-action |

---

## Tech Stack

- **HTML / CSS / JavaScript**
- **GSAP 3 + ScrollTrigger** — scroll-driven animations & pinning
- **Cormorant Garamond** — display / editorial typeface
- **DM Mono** — monospace labels & metadata
- **GitHub Pages** — hosting

---

## Project Structure

```
portfolio-website/
├── index.html        # Everything lives here
└── README.md
```

---

## Getting Started

No install or build step required.

**Run locally:**

```bash
# Clone the repo
git clone https://github.com/YOUR_USERNAME/portfolio-website.git
cd portfolio-website

# Open in browser — any of the following work:
open index.html                        # macOS
start index.html                       # Windows
python -m http.server 8000             # Local dev server (recommended)
```

Then visit `http://localhost:8000`.

---

## Deploying to GitHub Pages

```bash
# 1. Push your code
git add .
git commit -m "feat: initial portfolio"
git push origin main

# 2. Enable GitHub Pages
# Go to: Settings → Pages → Source → Deploy from branch → main / root
```

Your site will be live at `https://YOUR_USERNAME.github.io/portfolio-website/`

---

## Customisation

| What | Where in `index.html` |
|------|----------------------|
| Name & role | `#panel-hero` — `.hero-name`, `.hero-role` |
| Bio text | `#panel-about` — `.about-bio` |
| Focus areas | `.focus-item` blocks (×3) |
| Contact email | `#panel-cta` — `href="mailto:..."` |
| Colours | `:root` CSS variables |

### Colour tokens

```css
--gold:      #c9a96e   /* primary accent */
--gold-dim:  #9b7c4e   /* secondary / muted gold */
--bg:        #0a0a0a   /* page background */
--surface:   #111111   /* panel surface */
--white:     #f0ece4   /* body text */
--muted:     #4a4a4a   /* secondary text */
```

---

## Roadmap

- [ ] Add project showcase panel
- [ ] Connect contact form
- [ ] Add case studies / writing section
- [ ] Light mode toggle

---

## License

MIT — feel free to fork and make it your own.

---

*Built by [Leruo Motlhamme](https://github.com/YOUR_USERNAME) · Blockchain / Web3 Developer*