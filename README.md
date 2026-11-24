# Carta Magica — store selector (v2)

Static black-and-gold "choose your store" page: **CHOOSE YOUR STORE** / *Choisissez votre magasin* and two halves:

- **MONTREAL** → https://1p9p08-ym.myshopify.com/fr-ca (`hreflang="fr-CA"`; Canada market, French subfolder)
- **OTTAWA** → https://y0mnsf-rp.myshopify.com/ (`hreflang="en-CA"`)

Each half has an original SVG skyline (Montreal: Olympic Stadium tower, Mount Royal cross, downtown towers, Biosphere;
Ottawa: Peace Tower and Centre Block, East Block, Château Laurier) with a gold heraldic dragon rising behind it.
Drifting embers (small canvas script), slow glow pulse, hover lift/glow; all motion off under `prefers-reduced-motion`.
No libraries, no external requests, no cookies or analytics; `localStorage` only marks the last-visited store. `noindex`.

Rollback to the previous French-first page: tag `v1-french-first`.
Custom domain later (e.g. `choose.cartamagica.com`): add a `CNAME` file + DNS CNAME to `aalexopoulos87-athena.github.io` (not done).
