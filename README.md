# চা-বিলাসী — Cha-Bilashi 🍃

Premium tea-house website for **চা-বিলাসী**, a Sreemangal (Bangladesh) tea brand.
A single-page, fully responsive marketing site with WhatsApp-based ordering.

**Live site:** <https://sikdershakib.github.io/beta-tea/>

## Highlights

- 🎨 Premium brand design — deep tea-green & antique-gold palette, Bengali web typography (Hind Siliguri + Noto Serif Bengali)
- ️ Self-hosted, optimized imagery (hero, products, story)
- 🛒 Product showcase with per-product WhatsApp order links
- 📖 Sections: hero, features, products, brand story, brewing guide, FAQ, contact
- 🔍 SEO-ready: meta/Open Graph tags, JSON-LD `Store` schema, semantic & accessible markup
- 📱 Fully responsive with mobile navigation, scroll-reveal motion (respects `prefers-reduced-motion`)

## Structure

```
├── index.html            # Single-page site
├── assets/
│   ├── css/styles.css    # Design system & styles
│   ├── js/main.js        # Nav, accordion, reveal, back-to-top
│   ├── favicon.svg       # Brand mark
│   └── img/              # Optimized photography (hero, products, story)
└── .github/workflows/static.yml  # GitHub Pages deploy
```

## Local development

No build step — plain HTML/CSS/JS:

```bash
python3 -m http.server 8000
# open http://localhost:8000
```

## Publishing

Pushes to `main` automatically build & deploy via GitHub Actions
(`.github/workflows/static.yml`) to GitHub Pages.
