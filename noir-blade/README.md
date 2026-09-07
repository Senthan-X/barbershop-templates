# Noir Blade — Luxury Black & Gold Barber Lounge Template

A single-file, dependency-free landing page for a private, appointment-only grooming lounge. Version 3 of 6 in the **Senthan & Co** barbershop template set — moody, editorial, restrained. Bodoni Moda italics, a thin gold hairline motif, and a 4-step "ritual" instead of a service list.

![theme](https://img.shields.io/badge/theme-dark%2Flight-C9A24B) ![languages](https://img.shields.io/badge/languages-7-C9A24B) ![dependencies](https://img.shields.io/badge/dependencies-0-0A0A0A)

## Live sections

- Sticky nav with a circular gold-ring crest, language switcher, dark/light toggle
- Editorial italic hero with a gold-hairline-and-dot divider motif
- Services shown as a clean priced list (no cards) — considered, not busy
- "The Ritual" — a 4-step walkthrough of what a visit actually looks like
- Gallery of moody black-and-gold barbershop photography
- Team shown as thin gold ring-outline monogram avatars
- Client testimonials
- Reservation section with front-end form + contact block

## Tech

Single HTML file, zero build step, base64-embedded WebP photography, CSS custom property theming, 7-language i18n (`data-i18n` + JS dictionary, full Arabic RTL), `IntersectionObserver` scroll reveals, defensive `localStorage` wrapper.

## Customize

| What | Where |
|---|---|
| Brand name | Search "Noir Blade" throughout |
| Colors | `:root[data-theme="dark"]` / `"light"` — `--gold` and `--gold-bright` are the signature accents |
| Fonts | Google Fonts link in `<head>` — Bodoni Moda (display) / Jost (body) / Space Mono (utility) |
| Copy & translations | `translations` object near the bottom `<script>` |
| Images | Swap the base64 `data:image/webp;base64,...` strings on the relevant `<img>` tags |
| Pricing | `.service-price` spans in the Services section |
| Booking form | Wire `#bookForm` to Formspree, EmailJS, or your own backend |

## Credits

Built by **Senthan & Co**. 📞 +256 754 069 314 · ✉️ jonathanrivers0414@gmail.com

## License

Portfolio/demo copy — the licensed resale version ships via Codester with its own `README.txt`.
