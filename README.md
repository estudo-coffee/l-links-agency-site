# L-Links website

Static website served by existing GitHub Pages and `CNAME` (`l-links-agency.com`). No build tools, dependencies, trackers, new external font requests or forms are required. Preview with `python3 -m http.server 8063`.

## October 2026 refresh
- Improved responsive navigation, keyboard focus, skip link, reduced-motion support and native accessible FAQ.
- Clarified currently available referral / consultation versus future services. Existing LINE, email, Instagram, partnership wording and domain retained. No income or pricing guarantees added.
- Original CSS/SVG microphone illustration; no stock photos, third-party music or paid assets. `assets/logo.png` is the existing website's logo, extracted without visual alteration from its inline data URI. This does not assert new ownership over the logo.
- Canonical URL, title/description, Open Graph, minimal Organization schema, sitemap and robots metadata. These do not guarantee search ranking or indexing. Search Console setup requires account authorization and is not configured here.
- No audio, per confirmed direction. No form or fake submission confirmation; CTAs open existing contact services.

## Research informing the structure (2026-10-23)
Primary competitor sites reviewed: https://321.inc/ and https://one-carat.com/ . 321 clearly groups support and contact paths; ONECARAT provides flow and Q&A alongside support. The redesign uses a clear service scope, consultation flow and FAQs rather than copying layouts or claiming their roster, managers, performance or benefits. Current L-Links referral scope remains distinct from full-service management competitors.

## Maintenance / checks
- Keep `CNAME` unchanged. Prices, service terms, affiliation and future offerings should be re-confirmed by the operator before business-content changes.
- Preview desktop and mobile layouts; confirm keyboard navigation and FAQ open/close; inspect internal anchors and existing contact destinations without sending test messages.
- `site-version` meta marker: `llinks-20261023-refresh`.
- The prior version remains in Git history. Revert the refresh commit for rollback; avoid overwriting newer unrelated changes.
