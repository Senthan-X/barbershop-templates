# Senthan & Co — Barbershop & Salon Templates

Six distinct, self-contained HTML templates for barbershops, grooming lounges, braid studios, and hair salons.

## Templates

| Template | Folder | Direction |
|---|---|---|
| Heritage Barber Co. | [`heritage-barber-co`](./heritage-barber-co/) | Classic vintage barbershop |
| Fade Lab | [`fade-lab`](./fade-lab/) | Modern urban fades and hair art |
| Urban Cut Studio | [`noir-blade`](./noir-blade/) | Street-forward cuts, braids and texture |
| AURELIS Grooming Club | [`luxury-grooming-club`](./luxury-grooming-club/) | Luxury appointment-only grooming club |
| Hue & Curl Studio | [`hue-curl-studio`](./hue-curl-studio/) | Natural hair and color studio |
| The Braid Bar | [`braid-bar`](./braid-bar/) | Community braiding salon |

Open the [collection index](./index.html) to browse live previews rendered from the actual templates.

## Shared architecture

- Single-file HTML per template with no runtime dependencies
- Base64-embedded WebP photography
- Responsive light and dark themes that follow the visitor’s system setting by default
- Manual theme override saved defensively in `localStorage`
- Seven embedded languages: English, Spanish, French, German, Portuguese, Swahili, and Arabic
- Full right-to-left layout for Arabic
- IntersectionObserver scroll reveals with reduced-motion support
- Responsive navigation, booking form demo, skip link, and Back-to-Top Button

The booking forms are front-end demonstrations. Connect them to the buyer’s preferred form handler before production use.

## Deployment

The repository includes a GitHub Pages workflow. Each template can also be deployed independently by copying its folder, or by uploading its `index.html` as a standalone page.

## Credit

Built by **Senthan & Co**.
