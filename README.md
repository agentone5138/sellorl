# Florida Cash Offers

A single-page cash-offer lead-generation site for an Orlando-area home-buying business (serving Orange, Seminole, Osceola, Lake, and Volusia counties).

Structurally inspired by renovateorlando.com's proven layout (hero, benefits, 3-step process, situations-we-buy grid, comparison table, areas served, testimonials, FAQ, closing CTA), rebuilt with original copy, and styled to match that site's actual color palette and typeface (Inter; navy `#10243F`, green `#1F9D55`, gold `#F4B35E`).

## Status: template — not launch-ready yet

Several things are still placeholders and need to be replaced with real business details before this goes live:

- **Phone number** — currently `(855) 555-0182`
- **Email** — currently `offers@floridacashoffers.example`
- **License number** — currently `FL-000000`
- **Testimonials** — currently marked as sample/placeholder quotes with bracketed names
- **Lead form** — front-end only right now; on submit it shows a confirmation message but is not wired to a real CRM or lead router. Connect the two `<form>` elements in `index.html` (`#offer-form` and `#offer-form-2`) to your backend of choice (a lead-routing API, Zapier webhook, or your CRM's form endpoint) before launch.

## Structure

Everything lives in a single file, `index.html` — HTML, CSS, and JS inline, no build step required.

## Local preview

Just open `index.html` in a browser, or serve the folder with any static file server, e.g.:

```bash
python3 -m http.server 8000
```

## Deploying

This repo is set up to be served directly via **GitHub Pages** from the repo root on the `main` branch — enable it under Settings → Pages, or it may already be enabled if this repo was created with Pages pre-configured. Once enabled, the site is live at `https://<username>.github.io/<repo-name>/`.
