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

Your site will be live at `https://LERUO-M.github.io/portfolio-website/`

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

*Built by [Leruo Motlhamme](https://github.com/LERUO-M) · Blockchain / Web3 Developer*