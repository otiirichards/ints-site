# Ints website

AI that works for the expert, not instead of them.

A single-page static site. Everything lives in `index.html` (styles, scripts, animations). It loads two things from the internet: Google Fonts and Lenis (smooth scrolling) from jsDelivr. If either fails to load, the page still works.

## Before going live
Open `index.html`, scroll to the bottom `<script>` and set:
- `CONTACT_EMAIL = ""` → your address, e.g. `"hello@yourdomain.com"`
- `BRAND = "Ints"` → only if the name changes

## Publish with GitHub Pages
1. Create a new **public** repository (e.g. `ints-site`).
2. Upload `index.html`, `.nojekyll` and this README to the root.
3. Settings → Pages → Source: "Deploy from a branch" → Branch: `main`, folder `/ (root)` → Save.
4. Your site appears at `https://<your-username>.github.io/ints-site/` within a minute or two.

## Custom domain (optional)
Settings → Pages → Custom domain → enter your domain, then add the DNS records GitHub shows you at your domain registrar.

Confidential product details (prototype, concept paper, deck) do not belong in this public repository.

© Ints. All rights reserved.
