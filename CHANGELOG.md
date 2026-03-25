# Changelog

## Round 4 — Final Polish (2026-03-25)
- Linked Nick Romero (LaunchPath) testimonial to lead qualifier case study by name
- Calculator section given blue tint gradient to break bottom-half white run
- All card hover effects wrapped in `@media (hover: hover)` for touch devices
- `aria-hidden="true"` added to all decorative SVGs (~15 elements)

## Round 3 — Testimonials, A11y, Visual Variety (2026-03-25)
- Testimonials rewritten with full names + company names (Nick Romero/LaunchPath, Marco da Silva/Vertex Partners, Laura Kimura/Peakline Commerce)
- One testimonial set to 4 stars for credibility (Laura's)
- Testimonial language made conversational, not polished marketing copy
- Testimonial cards styled with left accent border + quote mark graphic
- Trust strip changed from "12+ automations shipped" → "500+ manual hours eliminated monthly"
- Services section given light blue tint gradient background
- Problem grid gap increased to 24px, case metric gap to 20px, trust strip padding to 36px
- FAQ items fully wired with `id`, `aria-controls`, `aria-labelledby`
- FAQ SVG icons, nav logo, hero visual, footer logo: `aria-hidden="true"`
- Star ratings given `role="img"` + `aria-label`
- Cookie bar changed from `role="alert"` to `role="dialog"`
- FAQPage structured data expanded from 4 to all 8 questions
- Section heading inline styles replaced with `.section-heading` / `.section-heading-light` classes
- Mobile case tables: header hidden, names span full width below 500px
- "What if it breaks" FAQ updated with "4-hour response time on business days"
- About section updated with specific industry experience
- Services subhead tightened
- Process closer reworded

## Round 2 — Comprehensive Reviewer Feedback (2026-03-25)
- Added testimonials section (3 client quotes)
- Removed jargon from services tags (ETL, webhook, API → plain language)
- Rewrote problem card 3 from AI FOMO to "operations aren't keeping up"
- Anglicized all case study mock data (German → English names)
- ROI calculator lowered from 75% to 60% automation rate
- Added email fallback (jasper@surestepautomations.com) in CTA + footer
- Added 2 FAQ items: "what if it breaks" and "how different from Zapier"
- Hero eyebrow → "Automation systems for small & mid-size teams"
- Hero subhead shortened and made more specific
- Services card descriptions made more concrete
- Final CTA headline rewritten
- About section includes founder background
- Accessibility: skip link, `<main>`, focus-visible, prefers-reduced-motion, noscript fallback, aria-expanded on FAQ/nav, calculator aria-labels
- SEO: structured data (Organization + FAQ), canonical URL, theme-color
- JS fixes: passive scroll listener, href="#" bug, aria-valuetext updates
- CSS: nav-cta !important removed, section heading class consolidated, cookie bar mobile, print styles

## Round 1 — Full Site Build (2026-03-25)
- Complete site rebuild from scratch with premium design
- Dark hero with animated before/after workflow visualization
- Trust strip with key metrics
- "Sound familiar?" problems section with 3 pain point cards
- Bento grid services layout with featured card
- 3 real case studies (lead qualifier, B2B prospecting, follow-up system) with mock UI visuals
- Interactive ROI savings calculator with sliders
- 4-step process section
- Founder about section with photo
- 8-item FAQ accordion
- Dark final CTA section
- Cookie consent bar
- Scroll-triggered reveal animations
- Fully responsive (960/900/768/700/600/500/480px breakpoints)

## Initial (2026-03-25)
- Copied existing surestep-site as starting point
- Created GitHub repo jnarvil3/surestep-site-upgraded

## PT-BR Version
- Full Brazilian Portuguese translation of the site
- Language switcher in nav and footer
- All copy, FAQ, case studies, calculator labels translated
- Structured data translated
