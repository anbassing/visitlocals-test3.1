# VISIT LOCAL Indonesia — GitHub / Hostinger Ready

Static, multi-page website prepared from the Stitch export.

## Structure
- `/index.html` — Home
- `/experiences/` — Authentic Indonesia Experiences & Local Tours
- `/destinations/` — Yogyakarta destination guide
- `/destinations/yogyakarta/` — Yogyakarta route alias
- `/business/` — Business in Indonesia / market entry / sourcing
- `/about/`, `/partner/`, `/contact/`, `/faq/`, `/inquiries/`, `/journal/`
- `/legal/privacy/`, `/legal/terms/`
- `/assets/visit-local-logo.svg`
- `/.htaccess`, `/404.html`, `/robots.txt`

## GitHub
Upload the **contents of this folder** to the repository root (not the ZIP folder itself).

## Hostinger
For normal Apache hosting, point the domain/subdomain document root to this project and make sure the files are inside `public_html`. If using Hostinger's Git deployment, connect the GitHub repository and set the deployment directory/document root to the repository root.

No Node.js, npm, build command, or framework is required. This is a static HTML site.

## Important
The visual pages still use the remote image URLs supplied by the original Stitch export and Google Fonts/Tailwind CDN. For a production launch, download/host those images locally and pin production assets rather than relying on temporary Stitch-generated image URLs.

WhatsApp CTAs currently point to +62 811 8899 710 as supplied in the source design.
