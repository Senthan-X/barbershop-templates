# The Braid Bar — Community Braiding Salon Template

A single-file, dependency-free landing page for a joyful, walk-in-friendly braiding salon. Version 6 of 6 in the **Senthan & Co** barbershop/salon template set — colorful, social, "bar" energy rather than clinical service listing.

![theme](https://img.shields.io/badge/theme-light%2Fdark-F2622E) ![languages](https://img.shields.io/badge/languages-7-F2622E) ![dependencies](https://img.shields.io/badge/dependencies-0-FFFFFF)

## Live sections

- Sticky nav, language switcher, dark/light toggle
- Warm, rounded Fredoka display type for a friendly, communal feel
- Pure-CSS "bead divider" — alternating orange/teal/pink dots echoing braiding beads
- "The Menu" — a chalkboard-style service list (Box Braids, Knotless, Kids Braids, Removal & Treatment)
- Gallery of real salon-community photography (laughing clients, backstage prep, street braiding)
- "The Braiders" — team cards with solid-color monogram avatars
- "The Regulars" — testimonials
- Booking section with front-end form + WhatsApp-ready contact block

## Tech

Single HTML file, zero build step, base64-embedded WebP photography, CSS custom property theming, 7-language i18n (`data-i18n` + JS dictionary, full Arabic RTL), `IntersectionObserver` scroll reveals, defensive `localStorage` wrapper.

## Customize

| What | Where |
|---|---|
| Brand name | Search "The Braid Bar" throughout |
| Colors | `:root[data-theme="light"]` / `"dark"` — `--orange`, `--teal`, `--pink` are the signature accents |
| Fonts | Font-family declarations in the main `<style>` block; the templates use dependency-free system fallbacks |
| Copy & translations | `translations` object near the bottom `<script>` |
| Images | Swap the base64 `data:image/webp;base64,...` strings on the relevant `<img>` tags |
| Bead divider | `.bead-divider` in the CSS — pure gradient dots, no external asset |
| Booking form | Wire `#bookForm` to Formspree, EmailJS, or your own backend |

## Credits

Built by **Senthan & Co**. 📞 +256 754 069 314

## License

Portfolio/demo copy — the licensed resale version ships via Codester with its own `README.txt`.
