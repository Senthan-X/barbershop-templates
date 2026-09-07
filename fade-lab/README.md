# Fade Lab — Modern Urban Fade & Hair-Art Template

A single-file, dependency-free landing page for a modern fade/hair-art barbershop. Version 2 of 6 in the **Senthan & Co** barbershop template set — bold, high-contrast, streetwear-adjacent, built around the idea that "your head is the canvas."

![theme](https://img.shields.io/badge/theme-dark%2Flight-CBFF3D) ![languages](https://img.shields.io/badge/languages-7-CBFF3D) ![dependencies](https://img.shields.io/badge/dependencies-0-0B0B0C)

## Live sections

- Sticky nav, language switcher, dark/light toggle
- Hero with bold Anton display type and a lightning-fade photo
- Pure-CSS zigzag dividers (no image/svg file) echoing the hair-tattoo line art in the gallery
- "The Menu" — services shown as rotated grade badges (barber guard numbers as a design motif)
- "The Wall" — a hover-desaturated photo gallery of fade and design work
- "By the Numbers" — stat counters
- "The Artists" — team cards
- "Word on the Street" — testimonials
- Booking section with front-end form + WhatsApp-ready contact block

## Tech

Same architecture as the rest of the set: single HTML file, zero build step, base64-embedded WebP photography, CSS custom property theming, 7-language i18n (`data-i18n` + JS dictionary, Arabic RTL included), `IntersectionObserver` scroll reveals, defensive `localStorage` wrapper.

## Customize

| What | Where |
|---|---|
| Brand name / tagline | Search `FADE` / `LAB` and "Your head is the canvas" |
| Colors | `:root[data-theme="dark"]` / `light"` blocks — `--lime` and `--coral` are the signature accents |
| Fonts | Google Fonts link in `<head>` — Anton (display) / Inter (body) / IBM Plex Mono (utility) |
| Copy & translations | `translations` object near the bottom `<script>` |
| Images | Swap the base64 `data:image/webp;base64,...` strings on the relevant `<img>` tags |
| Grade badges | `.grade-badge` elements in the Menu section — edit the rotated sticker text |
| Booking form | Wire `#bookForm` to Formspree, EmailJS, or your own backend |

## Credits

Built by **Senthan & Co**. 📞 +256 754 069 314 · ✉️ jonathanrivers0414@gmail.com

## License

Portfolio/demo copy — the licensed resale version ships via Codester with its own `README.txt`.
