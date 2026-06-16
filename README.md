# Local AI Money

**AI follow-up, lead capture, review, scheduling, and sales systems for local businesses.**

We install AI systems that help local businesses respond faster, follow up automatically, and close more leads — more booked appointments, faster lead follow-up, fewer missed calls, more Google reviews, better reactivation, less admin work, and more sales.

This repo is the marketing website + newsletter ("The Local AI Money Brief"). It's a static site — pure HTML/CSS/JS, no build step — so it runs anywhere and deploys free on GitHub Pages.

## Pages

| File | Purpose |
|------|---------|
| `index.html` | Home / landing page (hero, benefits, services, how it works, audit CTA, newsletter signup) |
| `services.html` | Full service list with the buyer + "why it sells" table |
| `pricing.html` | Three offers: Audit ($297), Installation ($2,500–$5,000), Maintenance ($497–$1,500/mo) |
| `newsletter.html` | "The Local AI Money Brief" hub + signup + issue archive |
| `issue-1.html` | "Most local businesses lose leads in the first 5 minutes" |
| `issue-2.html` | "The missed-call AI system every mechanic should have" |
| `issue-3.html` | "Realtors: use AI to revive old buyer and seller leads" |
| `styles.css` | Shared dark/gradient theme |
| `script.js` | Mobile nav, scroll reveal, newsletter form demo |

## Run locally

Just open `index.html` in a browser. Or serve it:

```bash
# Python
python3 -m http.server 8000
# then open http://localhost:8000
```

## Deploy free with GitHub Pages

1. Push this repo to GitHub (see `DEPLOY.md`).
2. In the repo: **Settings → Pages**.
3. Under **Build and deployment**, set **Source** = *Deploy from a branch*, **Branch** = `main` / `root`.
4. Save. Your site goes live at `https://<your-username>.github.io/local-ai-money/` in a minute or two.

## Customize

- **Email / CTAs:** search the project for `600589mbm@gmail.com` and swap in your booking link or email.
- **Newsletter form:** `script.js` handles the form as a front-end demo. Connect it to your email tool (Mailchimp, ConvertKit, Beehiiv, etc.) by pointing the `<form>` `action` at your provider.
- **Brand name / colors:** edit the CSS variables at the top of `styles.css`.

## License

MIT — see `LICENSE`.
