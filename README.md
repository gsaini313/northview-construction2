# Northview Construction Co. — Demo Website (v2)

A second, visually distinct demo website concept for **Northview Construction Co.**, a contractor based in Vaughan, Ontario.

## Design concept

**Dark luxury / editorial** — warm charcoal canvas with champagne-gold accents and a premium serif (Fraunces) paired with a clean sans (Manrope):

- Cinematic full-screen hero with oversized serif headline
- Gold hairline dividers, elegant services marquee
- Numbered services index with hover states, large editorial project gallery
- Rotating client pull-quotes, stat band, CTA-first contact (call / WhatsApp / email)
- Giant outlined wordmark footer

## Structure

Single `index.html` (no build step, no dependencies beyond Google Fonts):

| Sheet | Section |
|-------|---------|
| — | Cover / hero with tap-to-call CTAs |
| A-01 | Firm profile + spec stats |
| A-02 | Scope of work (8 services) |
| A-03 | Selected work (project gallery) |
| A-04 | Project phases (process) |
| A-05 | Field reports (testimonials) |
| A-06 | Service area (GTA) |
| A-07 | Contact — call / WhatsApp / email |

Contact is CTA-first: `tel:` call button, `wa.me` WhatsApp deep link with pre-filled message, and `mailto:` — no form backend needed.

## Business details

Real: name, address (4 Claudia Ave, Vaughan ON), phone (+1 647-705-5245), Instagram (@northviewconstco).
Demo filler: email, hours, stats, services copy, testimonials, project details.

## Deploy

Any static host works. On GitHub Pages: Settings → Pages → Deploy from branch → `main` → `/ (root)`.

*Demo website — all illustrative content.*
