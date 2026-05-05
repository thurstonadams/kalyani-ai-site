# kalyani.ai — KAI corporate site

Static marketing site for **Kalyani Aftermarket Innovations (KAI)** at https://kalyani.ai.

Patterned on xmotionaxles.com (parent → product brand). Vertically integrated American aftermarket engineering + AI-powered catalog.

## Stack
Plain HTML / CSS — no build step. Deploys directly to Vercel as static files.

## Local preview
```bash
# any static server works:
npx serve .
# or
python3 -m http.server 8080
```
Open http://localhost:8080

## Files
- `index.html` — Home (hero + 4 product cards + stats + pitch)
- `about.html` — About KAI
- `brands.html` — Brand family (xMotion Axles + KAI Platform + future)
- `contact.html` — Contact details
- `styles.css` — All styles (navy + red + white palette)
- `assets/` — `logo.svg`, `favicon.svg`, `flag.svg`
- `vercel.json` — Vercel config (clean URLs, security headers)

## Deploy
GitHub repo: `KAI-LLC-Admin/kalyani-ai-site`
Vercel team: `kai15`
Production domain: `kalyani.ai`

Vercel auto-deploys on push to `main`.

## Editing tips
- Phone & email are in the footer of every page — update in all four if they change.
- Stats (1,800+ / 99% / 24/7) appear on `index.html` and `about.html`.
- The 4 product cards on the homepage link to `/brands.html`.
