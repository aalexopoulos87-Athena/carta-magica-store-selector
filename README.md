# Carta Magica — store selector / choix de boutique

Static bilingual (French first, English toggle) page that lets visitors choose a Carta Magica store:

- **Montréal** — 6360 St-Hubert → https://1p9p08-ym.myshopify.com/ (French storefront, `hreflang="fr-CA"`)
- **Ottawa** — 1179 St-Laurent → https://y0mnsf-rp.myshopify.com/ (English storefront, `hreflang="en-CA"`)

Root URLs on purpose: each store's default language is served at `/` (no `/fr` or `/en` subpath).

No default store, no auto-redirect. The last choice and language are kept in `localStorage` on the visitor's device only
(no cookies, no analytics). A "Changer de boutique / Change store" link forgets it. `noindex` while the stores are pre-launch.

Hosted with GitHub Pages from `main` (root). To use a custom domain later (e.g. `choose.cartamagica.com`), add a `CNAME`
file and a DNS CNAME record pointing to `aalexopoulos87-athena.github.io` — not done yet.
