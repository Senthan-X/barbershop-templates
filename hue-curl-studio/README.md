# Hue & Curl Studio — Natural Hair & Color Studio Template

A single-file, dependency-free landing page for a natural hair and color studio. Version 5 of 6 in the **Senthan & Co** barbershop/salon template set — warm, vibrant, and visually expressive.

![theme](https://img.shields.io/badge/theme-light%2Fdark-E85D4E) ![languages](https://img.shields.io/badge/languages-7-E85D4E) ![dependencies](https://img.shields.io/badge/dependencies-0-FFF6EF)

## Live sections

- Sticky nav, language switcher, dark/light toggle
- Hero with a soft morphing organic "color blob" behind the photo (pure CSS, no image/svg)
- Services built around curl type and color, not a generic cut menu
- "The Color Menu" — a visual swatch-dot row (Cherry Red, Rose Gold, Honey Blonde, Natural Black, Copper, Lavender)
- Gallery of natural hair and color photography
- Stylist team cards with gradient monogram avatars
- Client testimonials
- Booking section with front-end form + WhatsApp-ready contact block

## Tech

Single HTML file, zero build step, base64-embedded WebP photography, CSS custom property theming, 7-language i18n (`data-i18n` + JS dictionary, full Arabic RTL), `IntersectionObserver` scroll reveals, defensive `localStorage` wrapper.

## Customize

| What | Where |
|---|---|
| Brand name | Search "Hue & Curl Studio" throughout |
| Colors | `:root[data-theme="light"]` / `"dark"` — `--coral`, `--berry`, `--gold` are the signature accents |
| Fonts | Font-family declarations in the main `<style>` block; the templates use dependency-free system fallbacks |
| Copy & translations | `translations` object near the bottom `<script>` |
| Images | Swap the base64 `data:image/webp;base64,...` strings on the relevant `<img>` tags |
| Color swatches | `.swatch-dot` inline styles in the Color Menu section |
| Booking form | Wire `#bookForm` to Formspree, EmailJS, or your own backend |

## Credits

Built by **Senthan & Co**. 📞 +256 754 069 314

## License

Portfolio/demo copy — the licensed resale version ships via Codester with its own `README.txt`.
