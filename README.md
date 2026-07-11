# Luke Heesun Jung — Portfolio

Personal portfolio website for **Luke Heesun Jung**, graphic designer based in Toronto.

## Live Site

> Deploy via GitHub Pages, Vercel, or Netlify.
> Custom domain: `lukeheesunjung.com` (configure DNS after deployment)

## Structure

```
portfolio_site/
├── index.html              # Main page (hero, about, selected work)
├── work.html               # All Work — filterable project grid
├── case_study_00/          # Art & Design Practice (V-TAG, Music, Ceramics)
├── case_study_01/          # LittleN × Sandeul — Kindergarten App & Brand
├── case_study_02/          # Urban Dive Marketing — Design Leadership
├── case_study_03/          # AZOTO — Liquid Nitrogen Ice Cream Brand
├── case_study_04/          # V-TAG — Brand Identity & Packaging
├── case_study_06/          # Reasonab Design Academy (RDA)
├── favicon.png
├── favicon.ico
└── README.md
```

## Tech Stack

- Pure HTML5 / CSS3 / Vanilla JavaScript
- No build tools, no frameworks — static site, zero dependencies
- Google Fonts: Inter (loaded via CDN)
- WCAG 2.1 AA compliant (skip navigation, focus styles, colour contrast, responsive)

## Deployment (GitHub Pages)

1. Push this repository to GitHub
2. Go to **Settings → Pages**
3. Source: `Deploy from a branch` → `main` → `/ (root)`
4. Site will be live at `https://<username>.github.io/<repo-name>/`

### Custom Domain

1. Purchase domain (Namecheap, Google Domains, etc.)
2. Add a `CNAME` file in the root with your domain:
   ```
   lukeheesunjung.com
   ```
3. Set DNS A records to GitHub Pages IPs:
   ```
   185.199.108.153
   185.199.109.153
   185.199.110.153
   185.199.111.153
   ```

## Accessibility

This site follows WCAG 2.1 Level AA guidelines.
For feedback or issues: **lukeheesunjung@gmail.com**

---

© 2024 Luke Heesun Jung. All rights reserved.
