# Modern Gentleman — Contemporary Barbering Template

A self-contained premium barbershop landing page and Version 2 of the **Senthan & Co** barbershop collection. Modern Gentleman pairs restrained editorial typography, warm brass detailing, and carefully selected grooming imagery with a conversion-focused booking journey.

## Experience

- Full-background responsive hero with independently tuned desktop and mobile crops
- Four service rituals with purposeful animated icon badges
- Curated journal gallery sourced from the full 63-image barbershop catalog
- Trust metrics, barber profiles, testimonials, and booking/contact sections
- System-aware light/dark theme with a remembered visitor override
- Seven embedded languages: English, Spanish, French, German, Portuguese, Arabic with RTL, and Chinese
- IntersectionObserver reveals, reduced-motion support, and animated Back-to-Top Button
- Defensive localStorage and browser-language detection

## Architecture

One zero-dependency HTML file with Base64-embedded WebP imagery, CSS custom properties, semantic markup, inline SVG icons, and `window.I18N` translations. No external fonts, scripts, or CDN requests are required.

## Customization

| Item | Location |
|---|---|
| Brand and content | Semantic HTML plus the `I18N` object |
| Theme palette | `:root[data-theme="dark"]` and `:root[data-theme="light"]` |
| Photography | Embedded `data:image/webp;base64,...` sources |
| Booking handler | `#bookForm` submit listener |
| Contact number | Booking contact link |

## Credits

Crafted by **Senthan & Co**. 📞 +256 754 069 314

## License

Portfolio/demo copy — the licensed resale version ships via Codester with its own `README.txt`.
