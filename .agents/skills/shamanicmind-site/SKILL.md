---
name: shamanicmind-site
description: Build and refine the ShamanicMind website, lore library, and symbolic graphics in its original midnight-navy-and-antique-gold visual system, with the supplied purple accent kept on the original logo. Use when working in Mac-iX/ShamanicMind on site content, graphics, layouts, accessibility, or conversion flows.
---

# ShamanicMind website builder

## Read first
1. `brand/BRAND_KIT.md` for authoritative visual tokens, prohibitions, and brand voice.
2. `content/reading-offers.json` for confirmed offer prices and unresolved checkout fields.
3. `content/lore/prana-chakras-tattvas.md` for the founding Symbols & Lore article and Regardie-specific tattva geometry.
4. `docs/SITE_SPEC.md` for architecture, conversion funnel, and source provenance.

## Build procedure
- Inspect existing site files and protect user-authored assets before changing styles or copy.
- Implement mobile-first accessible HTML; make progressive improvements in small reviewable commits.
- Use SVG illustrations from `assets/` as reusable components, not a substitute for the missing **original Egyptian eye logo**. Never generate a replacement brand logo.
- Ensure backgrounds are subtle, contrast passes WCAG AA for ordinary body text, animations honor prefers-reduced-motion, and every illustration has meaningful alt text or is decorative.
- Maintain one public entry point for each major topic. `Symbols & Lore` is the editorial/blog section; write real articles with source distinctions, not page farms or fictional posts.
- Keep headings informative, clear and human. Use American English; no placeholder testimonials, fake urgency, fabricated payment URLs, unsupported mystical/medical efficacy claims, or misleading services.
- Confirm $60 personal and $125 couples everywhere prices appear. The user gave a general 30–60 minute duration range; do not assign an exact duration to each offer unless confirmed. Payment and booking links remain unresolved until supplied.
- Clearly label Pharaoh as in development.
- When implementing Next.js later, carry over the existing source material, check routing and metadata, test a production build, and verify on mobile and desktop. Do not scaffold over or delete older design assets.
- Deliver a working preview and file inventory with every major change.
- Keep the homepage brand phrase “Discover the symbols behind your lore,” include the full Pythagorean A–Z map, and ground first-person story copy only in user-provided facts.

## Current tasks
- Restore the genuine supplied eye logo and Pharaoh art from the earlier site; obtain originals before substituting.
- Implement booking integration only after validated user-supplied URLs and session terms.
- Expand Symbols & Lore using attributed scholarship; ensure source note for Regardie and Indian traditions.
