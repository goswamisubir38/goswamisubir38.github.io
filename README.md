# Subir Goswami — Personal Portfolio

> *Certified AI-Driven Professional · Growth Marketing Strategist · Co-Founder · Author · Kolkata*

[![Live Site](https://img.shields.io/badge/Live%20Site-subirgoswami.github.io-c9a84c?style=flat-square&logo=github)](https://subirgoswami.github.io)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-subir--goswami-0077B5?style=flat-square&logo=linkedin)](https://www.linkedin.com/in/subir-goswami/)
[![Journal](https://img.shields.io/badge/Journal-Read%20Articles-c9a84c?style=flat-square)](https://subirgoswami.github.io/blog.html)

---

## About This Site

This is the source code for my personal portfolio website — **[subirgoswami.github.io](https://subirgoswami.github.io)** — built entirely in vanilla HTML, CSS, and JavaScript. No frameworks, no dependencies, no build tools. Just clean, fast, hand-crafted code.

The design follows a **warm dark editorial aesthetic** — charcoal backgrounds, gold typography, Playfair Display headings, and Crimson Pro body text. Every section was written, designed, and refined to reflect my professional identity: 14 years of growth marketing, AI strategy, and brand storytelling.

---

## What's Inside

```
subirgoswami.github.io/
│
├── index.html          → Main portfolio (Hero, About, Ventures, Books, Credentials, Skills, Contact)
├── blog.html           → Journal / article listing page
├── resume.html         → Resume gate with lead capture form
│
└── blog/
    └── my-first-post.html   → First journal entry (post template)
```

---

## Pages

| Page | Description |
|------|-------------|
| `index.html` | Full portfolio — hero with photo, experience timeline, ventures, books, certifications, skills, contact |
| `blog.html` | Journal listing — filterable articles by category (AI, Storytelling, Kolkata, Life & Work) |
| `resume.html` | Lead-capture resume gate — visitors submit name, email, company and intent before downloading |
| `blog/my-first-post.html` | First journal post — template for all future articles |

---

## Features

- **Zero dependencies** — pure HTML, CSS, JavaScript
- **Fully responsive** — tested at 380px, 640px, 900px, 1024px, and 1440px
- **Accessible** — skip link, focus styles, ARIA labels, semantic HTML, `aria-hidden` on decorative elements
- **SEO optimised** — Schema.org structured data (Person, WebSite, BlogPosting, BreadcrumbList), canonical URLs, Open Graph, geo meta tags
- **Performance** — author photo compressed from 836KB to 34KB, Google Fonts preloaded, `decoding="async"` on images
- **Lead capture** — resume gate collects name, email, company, intent and phone; leads stored in localStorage; admin view at `resume.html?admin=1`; CSV export built in
- **Reading progress bar** — gold bar fills across the top of each blog post as you scroll
- **Print stylesheet** — all pages print cleanly with white background and readable typography
- **Back to top** button, smooth scroll with `scroll-padding-top` offset for fixed nav

---

## Tech Stack

| Layer | Choice | Why |
|-------|--------|-----|
| Structure | HTML5 (semantic) | Accessibility + SEO |
| Styling | CSS3 (custom properties, Grid, Flexbox, clamp()) | No framework overhead |
| Fonts | Playfair Display · Crimson Pro · DM Mono | Editorial, warm, distinctive |
| Motion | CSS animations + IntersectionObserver | No JS animation library needed |
| Hosting | GitHub Pages | Free, fast, zero config |

---

## Design System

```css
--bg0:   #080603   /* Deepest background */
--bg1:   #0e0b07   /* Section background */
--bg2:   #14100a   /* Card background */
--bg3:   #1a150e   /* Hover state */
--gold:  #c9a84c   /* Primary accent */
--gold2: #e2c063   /* Hover gold */
--paper: #ede5d4   /* Body text */
```

**Fonts:** `Playfair Display` (headings) · `Crimson Pro` (body) · `DM Mono` (labels, tags, UI)

---

## Ventures

**[KaliNova AI](https://kalinova.ai)** — AI-powered digital marketing platform. Named after Kali, goddess of transformation.

**[Upnova Institute](https://upnova.in)** — AI upskilling institute helping professionals step into the AI era.

---

## Books on Amazon

- [When the Hooghly Whispered Your Name](https://www.amazon.in) — Literary fiction
- [Branding Yourself and Your Brand](https://www.amazon.in/Branding-Yourself-Business-Subir-Goswami/dp/1637818297/) — Brand strategy
- [Clickbank Blogging](https://www.amazon.in/Clickbank-Blogging-Successful-Responsive/dp/1649191111/) — Digital marketing

---

## Contact

| Channel | Link |
|---------|------|
| Email | [goswamisubir38@gmail.com](mailto:goswamisubir38@gmail.com) |
| LinkedIn | [linkedin.com/in/subir-goswami](https://www.linkedin.com/in/subir-goswami/) |
| WhatsApp | [Message me](https://wa.me/919330593753?text=Hi%20Subir%2C%20I%20came%20across%20your%20portfolio%20and%20would%20love%20to%20connect.) |
| Portfolio | [subirgoswami.github.io](https://subirgoswami.github.io) |

---

## Deploying Changes

This site deploys automatically via **GitHub Pages** from the `main` branch. Any commit to `main` goes live within 1–2 minutes.

To update a page:
1. Open the file on GitHub
2. Click the **pencil (Edit)** icon
3. Make your changes
4. Click **"Commit changes"** → **"Commit directly to main"**

---

## Adding a New Blog Post

1. Go to the `blog/` folder in this repo
2. Click **"Add file"** → **"Create new file"**
3. Name it `blog/your-post-title.html`
4. Copy the contents of `blog/my-first-post.html` as your template
5. Update the title, category, date, body content, and tags
6. Commit to `main`
7. Add a matching `<article class="post-card">` entry in `blog.html`

---

*Built with intention. Designed from Kolkata.*

---

© 2026 Subir Goswami · All rights reserved
