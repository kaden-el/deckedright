# ppl-landing

Working draft landing pages for the Yardline pay-per-lead agency.

**Status:** DRAFT. Pre-launch. Do not link externally.

**Real working dir:** `~/Desktop/Claude-Brain/clients/pay-per-lead-agency/`

## Pages

- `/` — splash / vertical selector (decks live, bath coming)
- `/decks.html` — deck builder landing page (form → Make.com webhook → Google Sheet)

## Deployment

GitHub Pages: `https://kaden-el.github.io/ppl-landing/`

## Pre-launch checklist

- [ ] Pick final agency name. Find-replace `Yardline` across both HTML files.
- [ ] Wire form `action` URL in `decks.html` to the live Make.com webhook (currently placeholder).
- [ ] Install Google Ads gtag + conversion pixel before launching ads.
- [ ] Remove `<meta name="robots" content="noindex" />` from both files at launch.
- [ ] Optionally swap GitHub Pages URL for a custom domain after LLC + name decisions.
