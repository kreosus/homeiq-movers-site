# HomeIQ for Movers — marketing site

Static, dependency-free marketing site for **HomeIQ for Movers** (the B2B moving
app at [kreosus/homeiq-movers](https://github.com/kreosus/homeiq-movers)).

- `index.html` — landing page (hero, features, how-it-works, pricing, CTAs).
- `privacy.html` — privacy policy.
- `icon.png` — app/brand mark.

Just HTML + CSS + a few lines of vanilla JS, so it hosts free anywhere. This repo
publishes via **GitHub Pages** (Settings → Pages → Deploy from `main`).

Pricing mirrors `src/tiers.js` in the app repo: Solo $49 / Crew $99 / Business
$249 per month (annual = 2 months free), 14-day free trial. CTAs currently open
`mailto:sales@homeiqmovers.com`; wire them to a hosted signup / Calendly when
ready, and point a custom domain (homeiqmovers.com) at Pages.

## Local preview

```bash
python3 -m http.server 4500   # then open http://localhost:4500
```
