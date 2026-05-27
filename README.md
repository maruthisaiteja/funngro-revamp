# Funngro Website Revamp

A complete dark-themed redesign of the [Funngro](https://funngro.com) platform — India's youth income platform. Built as a modern, high-performance static landing page with cinematic dark aesthetics, smooth scroll animations, and interactive UI components.

![Funngro Revamp Preview](https://img.shields.io/badge/Status-Live-brightgreen?style=flat-square) ![HTML](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white) ![CSS](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black) ![Vercel](https://img.shields.io/badge/Deployed_on-Vercel-000000?style=flat-square&logo=vercel&logoColor=white)

---

## Live Demo

🔗 [View Live Site →](https://funngro-revamp-lime.vercel.app/)

---

## Overview

This project is a UI/UX redesign exercise for Funngro — taking their existing dark-green editorial aesthetic and rebuilding it into a more dynamic, high-contrast dark interface with interactive elements and a stronger visual hierarchy.

The redesign focuses on:
- Converting visitors faster with a bold above-the-fold hero
- Communicating the income ladder more clearly with structured cards
- Making the "How it works" flow interactive rather than static
- SEO-friendly semantic HTML structure throughout

---

## Features

- **Custom cursor** — lime dot with trailing ring for premium feel
- **Animated hero** — CSS grid background, radial glow, staggered reveal on load
- **Live brand ticker** — infinite marquee of 18+ partner brand names
- **Count-up stats** — numbers animate in using IntersectionObserver on scroll
- **Interactive steps panel** — hovering each step updates the visual preview live
- **Income ladder** — 3-tier grid with accent highlight on the featured card
- **Work type cards** — animated rotating arrow CTA on hover
- **Scroll reveal** — all sections fade + slide in as they enter viewport
- **Zero dependencies** — pure HTML, CSS, vanilla JS. No frameworks, no npm

---

## Design System

| Token | Value |
|-------|-------|
| Background | `#060606` (near black) |
| Surface | `#0e0e0e` / `#161616` |
| Accent | `#C8FF00` (electric lime) |
| Secondary accent | `#FF5C1A` (electric orange) |
| Text | `#F2EDE6` (warm white) |
| Muted | `#6a6a6a` |
| Display font | Syne 700/800 |
| Mono font | Space Mono 700 |
| Body font | DM Sans 300/400/500 |

---

## Tech Stack

- **HTML5** — semantic structure, SEO-optimized meta tags
- **CSS3** — custom properties, grid, flexbox, keyframe animations, IntersectionObserver-triggered transitions
- **Vanilla JavaScript** — custom cursor, count-up animation, interactive step panel, scroll reveal
- **Google Fonts** — Syne, DM Sans, Space Mono (loaded via CDN)

---

## Getting Started

No build step required. Just clone and open.

```bash
git clone https://github.com/YOUR_USERNAME/funngro-revamp.git
cd funngro-revamp
open index.html
```

Or deploy instantly to Vercel:

```bash
npx vercel
```

---

## Project Structure

```
funngro-revamp/
├── index.html       # Complete single-file site
├── vercel.json      # Vercel deployment config
├── .gitignore
└── README.md
```

---

## Deployment

This site is deployed on [Vercel](https://vercel.com) via GitHub integration.

Every push to `main` triggers an automatic redeploy.

---

## SEO Highlights

- Semantic HTML5 landmarks (`<nav>`, `<section>`, `<footer>`)
- Descriptive `alt` text patterns
- Logical heading hierarchy (h1 → h2 → h3)
- Mobile-responsive via `clamp()` fluid typography
- Fast load — single HTML file, no render-blocking resources beyond fonts

---

## Screenshots

| Hero | Income Ladder | Work Types |
|------|--------------|------------|
| Dark hero with animated grid bg | 3-tier earning ladder | 4-column work type grid |

---

## Author

**Maruthi Sai Teja**
- GitHub: [@maruthisaiteja](https://github.com/maruthisaiteja)
- LinkedIn: [maruthi sai teja](https://www.linkedin.com/in/maruthi-sai-teja-16a899179)

---

## License

This project is open source and available under the [MIT License](LICENSE).

---

> Built as a UI redesign evaluation project for Funngro's internal talent program.
