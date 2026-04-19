# crossfit-barbell-republic

Website upgrade mockups for CrossFit Barbell Republic (Denison, TX) — a visual pitch for ownership showing coach credentials, community social proof, and free first class conversion flow.

**Live:** https://baecht.github.io/crossfit-barbell-republic/

## Pages

- `index.html` — Homepage (copy of `cbr_mockup_homepage.html`)
- `cbr_mockup_homepage.html` — Homepage with hero, coach previews, stats, schedule, CTAs
- `cbr_mockup_coaches.html` — Meet Our Coaches with real credentials from the CrossFit Trainer Directory
- `cbr_mockup_social.html` — Community & social proof (Instagram feed, testimonials)
- `cbr_mockup_freetrial.html` — Free First Class landing page with sign-up form, schedule, FAQ

## Assets

- `logo.jpg` — CBR logo referenced by all pages
- `.nojekyll` — tells GitHub Pages to skip Jekyll processing (plain static site)

## Local preview

```bash
# Python built-in server
python -m http.server 8000
# then open http://localhost:8000
```

Or just open `index.html` directly in a browser.

## Deploy

Pushing to `main` triggers GitHub Pages to rebuild from repo root.
