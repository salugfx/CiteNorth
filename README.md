# CiteNorth

Production-style, SEO-first MVP built as a zero-framework static frontend with Vercel-compatible Node serverless functions.

## Deploy at $0 to start
1. Create a new GitHub repository and upload this folder.
2. Import the repository into Vercel (Hobby tier).
3. Replace every `https://YOUR-DOMAIN.example` occurrence in `sitemap.xml` and `robots.txt` with the real production domain.
5. The Google Search Console verification file is already in the site root as `google696ff18b857810e3.html`.
6. Submit `/sitemap.xml` in Search Console after the production domain is live.

## Contact form
The public contact form submits directly to Formspree. The Gmail address is intentionally not printed in the website source or UI. Confirm the Formspree project and allowed-domain settings in your Formspree dashboard.

## AdSense readiness
- About, Privacy and Terms pages are included.
- Original resource pages are included.
- `ads.txt.example` is a placeholder only. Do not invent an AdSense publisher line; replace it with the exact line Google gives you after/when applicable.
- No ad script is included because no publisher ID was provided.

## Search / branding note
The brand name was screened for obvious category collisions during research, but this is not a trademark or domain-availability clearance. Check your intended domain and trademark jurisdiction before spending on branding.

## Security
The URL-scanning endpoints block obvious private-network targets and enforce short fetch timeouts. Before large-scale public launch, add rate limiting and abuse monitoring at the hosting layer.
