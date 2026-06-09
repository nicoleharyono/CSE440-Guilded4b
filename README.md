# Guilded

**Find the makers behind the things you love.**

Guilded is a mobile app concept for discovering authentic local artisans at
markets and staying connected with the makers you love. This repository hosts
the project's case-study website: the story of how the app was researched,
designed, tested, and revised.

**Live site:** <https://cse-440-guilded4b-1n8c.vercel.app/>

The site walks through the problem (markets are full of makers, but finding them
again is hard), the proposed solution (discover, verify, follow, and navigate to
real artisans), the design process from paper sketches to a clickable prototype,
and what the team learned along the way.

## Viewing the site

No build step or dependencies are required. It's a static website.

- **Live (deployed):** <https://cse-440-guilded4b-1n8c.vercel.app/>
- **Quickest way:** open [`GUILDED Website/index.html`](GUILDED%20Website/index.html)
  directly in any modern web browser.
- **Or serve it locally** (recommended, so relative paths resolve cleanly):

  ```bash
  cd "GUILDED Website"
  python -m http.server 8000
  ```

  Then visit <http://localhost:8000> in your browser.

## Project structure

```
.
└── GUILDED Website/
    ├── index.html        # Page markup and content
    ├── css/
    │   └── style.css     # All styling
    └── js/
        └── script.js     # Interactivity (toggles, scroll reveals, video clips)
```

The site was originally a single large `index.html`; the styles and scripts have
since been split into `css/style.css` and `js/script.js` for readability. The
markup, styling, and behavior are otherwise unchanged.

## About the project

This is a course project for **CSE 440 (Introduction to Human–Computer
Interaction)**, presented as a design case study covering user research,
ideation, prototyping, usability testing, and design iteration.

## Team

- Nicole Haryono
- Fiony Mulia
- Kyna Develle
- Camaryn Garcia
