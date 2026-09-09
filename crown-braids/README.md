# Crown Braids — Men's Braid Specialist Studio Template

A single-file, dependency-free landing page for a precision braid studio. Version 4 of 6 in the **Senthan & Co** barbershop template set — regal, geometric, built around the idea that every braid pattern is a crown.

![theme](https://img.shields.io/badge/theme-dark%2Flight-D98C4A) ![languages](https://img.shields.io/badge/languages-7-D98C4A) ![dependencies](https://img.shields.io/badge/dependencies-0-120E1A)

## Live sections

- Sticky nav with a CSS crown icon, language switcher, dark/light toggle
- Cinzel display type for a regal, engraved feel
- Pure-CSS "braid weave" herringbone divider (no image/svg file)
- "The Styles" — cornrows, feed-ins, tribal patterns, braided bun finish, each with a duration
- Gallery of geometric cornrow and braid pattern photography
- "The Braiders" — team cards with copper/violet gradient crown badges
- Client testimonials
- Booking section with front-end form + WhatsApp-ready contact block

## Tech

Single HTML file, zero build step, base64-embedded WebP photography, CSS custom property theming, 7-language i18n (`data-i18n` + JS dictionary, full Arabic RTL), `IntersectionObserver` scroll reveals, defensive `localStorage` wrapper.

## Customize

| What | Where |
|---|---|
| Brand name | Search "Crown Braids" throughout |
| Colors | `:root[data-theme="dark"]` / `"light"` — `--copper` and `--violet` are the signature accents |
| Fonts | Font-family declarations in the main `<style>` block; the templates use dependency-free system fallbacks |
| Copy & translations | `translations` object near the bottom `<script>` |
| Images | Swap the base64 `data:image/webp;base64,...` strings on the relevant `<img>` tags |
| Braid weave divider | `.braid-divider` in the CSS — pure gradient, no external asset |
| Booking form | Wire `#bookForm` to Formspree, EmailJS, or your own backend |

## Credits

Built by **Senthan & Co**. 📞 +256 754 069 314

## License

Portfolio/demo copy — the licensed resale version ships via Codester with its own `README.txt`.
