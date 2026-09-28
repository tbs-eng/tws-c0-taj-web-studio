# tws-c0-taj-web-studio
Taj Web Studio's own website (Client0) — tajwebstudio.com.

Static HTML/CSS, no build step. Deployed via **Cloudflare Pages** (push to GitHub → Cloudflare builds it; since 1 Aug 2026 — see taj-studio-ops `now/LIVE-STATE.md`). *(Corrected 28 Sept; this line used to say GitHub Pages.)*
Structure: 8 pages + `css/styles.css` (design system per the brand kit) + `assets/` (outlined SVG logos).
Visibility layer: per-page meta + JSON-LD schema, `sitemap.xml`, `robots.txt` (AI crawlers allowed), `llms.txt`.

Strategy docs (blueprint, proposal, brand kit) live in the ops repo: `taj-studio-ops/clients/client0-taj-web-studio/`.
