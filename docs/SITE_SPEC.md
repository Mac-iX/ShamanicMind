# ShamanicMind | Site implementation specification

## Intent
Build an elegant, fast website for personal numerology-led symbolic readings, with astrology, Egyptian oracle cards, and reflective psychological framing integrated when relevant. Establish a distinguished editorial property: **Symbols & Lore**, starting with Prana, Chakras & Tattvas. Reserve Pharaoh as an *in-development* app, separate from Mac's live personal readings.

## Source material
- Earlier ChatGPT Sites text recording ShamanicMind used the language “Ancient symbols. A personal conversation.”, “Know your patterns. Choose your path.”, and emphasized reading choice and user discernment.
- The earlier design was described as a **digital temple-library** with a threshold hero, guided reading paths, method/ethics, and preview of Pharaoh.
- Current user brief (Oct 2026) sets **$60 personal / $125 couples**; sessions are 30–60 minutes and available virtually or in person.
- The original golden Egyptian-eye and Pharaoh artwork remain intact in the existing Site source. The GitHub review branch uses supporting geometry and must never replace or redraw that original art.
- Historic source site record: https://shamanicmind-readings.yogamac.chatgpt.site (external earlier prototype; current deployment status may change). Do not replace it or claim source-code parity without examining the original build.

## Navigation
Home / Readings (home section) / My Story (home section) / Symbols & Lore (library) / Pharaoh (home section).

## Landing-page information architecture
1. **Threshold hero**: symbologist position, numerology as core, integrative astrology / Egyptian oracle / psychological framing, primary CTA to readings, secondary CTA to Lore. Decorative gold celestial geometry on violet.
2. **Reading format cards**: Personal $60, Couples $125. Both virtual and in person, with the user-provided general range of 30–60 minutes.
3. **The Approach**: question-led reflection, numerology first, supplemental correspondences, interpretation does not replace free will.
4. **My Story**: poetic first-person account of the trenches, alchemizing darkness, nearly ten years of introspection, hundreds of books, and the layered perception of reality; do not invent events.
5. **Pythagorean A–Z map**: clearly pair every English letter with its repeating 1–9 value; explain that this is one symbolic convention.
6. **Symbols & Lore**: the blog is Mac’s write-up library across numerology, astrology, mythology, and symbols; publish meaningful essays with precise provenance.
7. **Pharaoh**: clearly marked in development. No sign-up or fake launch window.
8. **Booking contact**: informational readiness only until supplied links. No dead booking control.

## Art direction
Midnight navy and warm gold, cosmic gridding, Egyptian symbols revealed subtly on scroll, high legibility, expensive editorial restraint. Reserve the original purple accent for the supplied logo. Font fallback works without internet. Space and geometry as background, not busy overlays. Use no invented hieroglyph translation or fake historical imagery.

## Lore and publishing
- The section is an editorial library/blog, with archival article layout and future taxonomy for animals, Egyptian symbolism, geometry, yoga, numerology and astrology.
- All source-derived claims should be attributed in article notes.
- Regardie's Golden Dawn tattvas have specific shapes/colors: yellow square, silver crescent, red triangle, blue circle, black oval. Distinguish from chakra yantras, medieval philosophy, and modern rainbow colors.
- Publish meaningful articles rather than empty SEO pages.

## Technical
- First pass: accessible semantic dependency-free HTML+CSS+JS, responsive at ~320–1440px, static asset paths relative to repo root. Easy to migrate to Next/Vercel, GitHub Pages or another host.
- Progressive navigation, reduced motion, keyboard focus, image alternative text, dark contrast. No external third-party tracker.
- Check in both content Markdown and rendered article. Keep SVGs standalone and reusable.
- Before production: recover original logo, choose final site framework, connect booking/checkout, supply contact and policy copy, run accessibility/performance tests, verify canonical and metadata, confirm custom-domain DNS.
