# Heritage Barber Co. — Vintage Barbershop Template

A single-file, dependency-free landing page for a classic, old-world barbershop. Part of the **Senthan & Co** barbershop template set — this is Version 1 of 6, built around a "family trade since 1962" identity: leather chairs, straight razors, ledger typography, and a hand-coded CSS barber pole.

![theme](https://img.shields.io/badge/theme-dark%2Flight-8A6B3E) ![languages](https://img.shields.io/badge/languages-7-C7A06C) ![dependencies](https://img.shields.io/badge/dependencies-0-2F4B5E)

## Live sections

- Sticky nav with language switcher + dark/light toggle
- Hero with a pure-CSS animated barber pole (no image/gif)
- "The Craft" — services styled as ticket stubs, mono-spaced pricing
- "Heritage" — a real chronological timeline (1962 → today)
- Gallery of tool photography
- "Meet the Barbers" — wax-seal monogram avatars (no stock headshots needed)
- Testimonials
- Booking section with a front-end contact form + WhatsApp-ready contact block

## Tech

- Pure HTML/CSS/JS, single file, **zero build step**
- All photography embedded as base64 WebP — no `/assets` folder to lose on upload
- CSS custom properties power the dark/light theme (`data-theme` attribute)
- 7-language i18n (English, Spanish, French, German, Portuguese, Swahili, Arabic) via `data-i18n` attributes + a JS dictionary — Arabic ships with full RTL mirroring
- `IntersectionObserver` scroll reveals, respects `prefers-reduced-motion`
- Defensive `localStorage` wrapper (falls back to in-memory state if storage is blocked, e.g. in sandboxed previews)

## Customize

| What | Where |
|---|---|
| Brand name, tagline, est. year | Search `Heritage Barber Co.` and `1962` in `index.html` |
| Colors | `:root[data-theme="dark"]` / `:root[data-theme="light"]` custom properties near the top of `<style>` |
| Fonts | Font-family declarations in the main `<style>` block; the template uses dependency-free system fallbacks |
| Copy & translations | `translations` object near the bottom `<script>` — one object per language code |
| Images | Replace the base64 `data:image/webp;base64,...` strings on the relevant `<img>` tags |
| Contact details | `.book-contacts` block (fictional Uganda address, phone, and email) |
| Booking form | Wire `#bookForm`'s submit handler to Formspree, EmailJS, or your own backend |

## Adding a language

1. Duplicate any language block inside the `translations` object.
2. Translate each value (keep the keys identical).
3. Add an `<option>` to `#langSelect` in the nav.
4. If the language reads right-to-left, add its code to the `lang === 'ar'` check in `applyLanguage()`.

## Browser support

Modern evergreen browsers (Chrome, Firefox, Safari, Edge). Uses `IntersectionObserver`, CSS custom properties, and `backdrop-filter` — all widely supported; the page degrades gracefully (reveals just show immediately) if `IntersectionObserver` is unavailable.

## Credits

Built by **Senthan & Co** — HTML/web templates for Codester & ThemeForest.

All business contact and location details shown in this template are fictional demo data.

## License

This repository is a portfolio/demo copy. The licensed, resale version is distributed via Codester — see `codester/README.txt` for the buyer-facing license terms.
