# AOKA Creations — Website

The official one-page website for **AOKA Creations**, an Australian studio building
thoughtful tools, experiences and resources that support emotional wellbeing,
reflection and personal growth.

🌐 **Production:** https://aokacreations.com

## Stack

Pure static HTML + CSS. No frameworks, no build step.

## Structure

```
.
├── index.html        # Home / About / Products / Publications / Contact
├── privacy.html      # Privacy Policy
├── 404.html          # Not-found page
├── styles.css        # Premium dark + gold theme
├── robots.txt        # SEO
├── sitemap.xml       # SEO
└── assets/
    ├── next-moment-logo.png
    └── favicon.png
```

## Local preview

```bash
npx serve . -p 4599
# or
python -m http.server 4599
```

## Deployment — Cloudflare Pages

- **Framework preset:** None
- **Build command:** _(empty)_
- **Build output directory:** `/` (repository root)

Every push to `main` auto-deploys.

---

© AOKA Creations. The Next Moment mobile app lives in a separate repository.
