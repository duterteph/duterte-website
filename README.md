# Duterte.ph — Rodrigo Duterte Profile Website

A fast, standalone, single-page website profiling **Rodrigo Roa Duterte** — longtime Mayor of Davao City, 16th President of the Philippines (2016–2022), and the first Filipino president from Mindanao. Includes his biography, a 13-milestone career timeline, key policies of his presidency, and the current status of his ICC case (verified as of September 2026).

## Run locally

No build step, no dependencies — just open `index.html` in any browser.

```bash
# or serve it (optional, for a local URL):
npx serve .
```

## Deploy for free

Because the site is fully static, it can be hosted for $0 on any of these:

**Netlify**
- Drag & drop this folder onto https://app.netlify.com/drop
- Or: `npx netlify-cli deploy --prod --dir .`

**GitHub Pages**
1. Create a repo and push this folder.
2. Settings → Pages → Source: deploy from branch (`main`, root).
3. Live at `https://<user>.github.io/<repo>/`.

**Vercel**
- Import the repo, framework preset: *Other*, output directory: `.`

## Structure

```
duterte-website/
├── index.html        # All markup (semantic, accessible, SEO/OG meta)
├── css/styles.css    # Design system + responsive layout
├── js/script.js      # Nav, scroll reveals, counters, active-link highlight
├── assets/
│   └── duterte-portrait.jpg   # Official presidential portrait (public domain)
└── README.md
```

- The hero uses the **official presidential portrait** (work of the Philippine government — public domain), sourced from Wikimedia Commons and bundled locally, with a credit caption.
- Google Fonts (Playfair Display + Inter) with system fallbacks.
- Honors `prefers-reduced-motion` for accessibility.

## Content notes

Facts were verified against the Official Gazette, Wikipedia, the ICC (icc-cpi.int), and contemporaneous reporting as of **September 22, 2026**. Key dated facts: ICC arrest March 11, 2025; charges confirmed April 23, 2026; trial scheduled to open November 30, 2026.

This is an **unofficial, non-partisan educational project** — not affiliated with Rodrigo Duterte, his family, or the Government of the Philippines.