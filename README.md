# The Client Desk — public GEO site

Ready-to-send communication templates for independent freelancers working with international clients: client replies, scope notes, invoices, deposits, payment follow-up and project handover.

**Live site:** https://wu-xiaoqi.github.io/the-client-desk

## What this is
A static, crawler-friendly site built for generative-engine optimization (GEO). Every page is original, structured (FAQPage / Article JSON-LD), and written in the buyer's own phrasing. No invented statistics — where no verifiable figure exists, we say so.

## Products referenced
- Freelancer Client Kit — 12 fill-in-the-blank client email and scope templates, editable DOCX, $25 USD: https://payhip.com/b/ijF1r
- Get Paid Faster Kit — 7 payment-chase emails plus a day-by-day escalation ladder, editable DOCX, $7 USD: https://payhip.com/b/VFCrW

## Structure
- `site/` — source (gated internal preview build)
- `site-public/` — public build (no gating, crawler-friendly)
- `gh-pages/` — deployed to GitHub Pages
- `build_geo_pages.py` — content generator (data-driven)
- `build_public.py` — gated → public transform
- `sync_to_ghpages.sh` — sync + push to GitHub Pages

Communication and administrative templates only. No contract clauses, no legal advice, no guarantee of payment or income.
