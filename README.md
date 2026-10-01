# Amalphia Sylva website

Static site for Amalphia Sylva belly dance classes in Biscoe, NC.
Live at https://amalphiasylva.com (Cloudflare Workers static assets).

## Files
- `index.html` — the main page (HTML and CSS in one file)
- `season/index.html` — the seasonal page at /season/
- `images/` — photos used on the page
- `wrangler.jsonc` and `.assetsignore` — Cloudflare Workers deployment settings

## Editing
Edit `index.html` and commit. Class times, prices and contact details are in the
"Classes" and "Contact" sections. Images go in `images/`.
Changes pushed to the main branch go live automatically via Cloudflare.
