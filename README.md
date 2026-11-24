# Carta Magica — store selector (v3)

Static black-and-gold "choose your store" page: **CHOOSE YOUR STORE** / *Choisissez votre magasin* and two clickable logos:

- **MONTREAL** logo → https://1p9p08-ym.myshopify.com/fr-ca (`hreflang="fr-CA"`)
- **OTTAWA** logo → https://y0mnsf-rp.myshopify.com/ (`hreflang="en-CA"`)

The logos are edits of the official Carta Magica dragon logo (`assets/logo-carta-magica.png`, kept unchanged): the dragon,
claws and jaw are the original pixels; only the "CARTA MAGICA" wordmark band was redrawn with MONTREAL / OTTAWA in the
same gold two-tone / black / white outline style. Lettering font: Bungee (SIL OFL), the closest open match to the custom
wordmark. Builder script lives outside this repo (`/workspace/carta-magica-store-logos/build_logos.py` on the build box).

Side by side on desktop, stacked on mobile. No libraries, no external requests, no cookies or analytics; `localStorage`
only marks the last-visited store. `noindex`.

Rollback: tag `v2-skylines` (skylines + dragons design), tag `v1-french-first` (first version).
