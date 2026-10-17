# Taj Web Studio: tajwebstudio.com

The website for my web studio: planned, built and hosted by me.
**Live:** https://tajwebstudio.com

## What it is

A fast, plain static site: 8 pages of hand-written HTML and CSS with a small
amount of JavaScript. There's no framework and no build step, so pages load
quickly, nothing needs patching, and hosting costs nothing.

## How it's built

| Area | What I did |
| --- | --- |
| Front end | Semantic HTML, one shared stylesheet, responsive layout with a phone menu |
| Search & AI visibility | Per-page titles and descriptions, JSON-LD structured data (ProfessionalService, Service, Person, FAQPage), `sitemap.xml` with last-changed dates, `robots.txt`, `llms.txt` |
| Hosting | Cloudflare Pages. Every push to `main` builds and publishes the site |
| DNS | Moved from the registrar to Cloudflare; web and Zoho email records copied and checked before the switch |
| Redirects | `_redirects` sends retired pages to their replacements with permanent (301) redirects |

## Run it locally

No install needed. Open `index.html` in a browser, or serve the folder:

```
python -m http.server 8000
```

then visit http://localhost:8000.

---
Leonardo De Leon · San Diego, CA · [tajwebstudio.com](https://tajwebstudio.com)
