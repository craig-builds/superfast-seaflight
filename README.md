# Super Fast Seaflight — takeaway website

**Live:** https://superfastseaflight.co.za

A fast, mobile-first website for a fish-and-chips takeaway in Korsten, Gqeberha.

## The problem
Local takeaways win or lose on one question: *what's on the menu, what does it cost, and can I order right now?* The business had its menu on printed boards and its customers on phones, mostly on mobile data. It needed a site that answers that question in seconds and sends people straight to WhatsApp or a phone call.

## What I built
- A single-page site covering the full menu with prices, combos and specials, opening hours, location with an embedded map, and one-tap WhatsApp and call buttons.
- An immersive animated ocean-themed hero that stays light enough for budget phones.
- Search-friendly structure: local-business structured data (menu, hours, address), sitemap and robots, and descriptive titles so the shop appears for "fish and chips Korsten" style searches.
- Privacy and Terms pages written for South African law (POPIA).
- A companion **59-second video ad** (Remotion + 3D ocean scene, AI voice-over) built for social media.

## Stack
HTML, CSS and vanilla JavaScript, with a lightweight 3D scene (three.js). Self-hosted fonts. Hosted on Vercel.

## Security and quality
- Strict Content-Security-Policy, HSTS, `X-Frame-Options: DENY`, `nosniff`, and a locked-down Permissions-Policy.
- No backend, no database and no forms, so there is no customer data to leak. Ordering happens in WhatsApp.
- Reviewed for exposed keys and personal data before this showcase was published.

## About this repository
This is a **showcase repository**. It describes the project; the production source is kept private because it belongs to a client business. © Craig Chadley Johnson. All rights reserved. See [LICENSE](LICENSE).

Built by [Craig Chadley Johnson](https://github.com/craig-builds) — johnsoncraig.dev@gmail.com
