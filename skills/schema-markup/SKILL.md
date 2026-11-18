---
name: schema-markup
description: Create valid JSON-LD structured data. Use for schema, rich results, entity markup, or helping search and AI systems understand a page.
---

# Schema Markup (JSON-LD)

## Choose by page
- Home/about: `Organization` (name, url, logo, sameAs profiles), `WebSite`
- Articles: `Article`/`BlogPosting` with author (`Person`), datePublished, dateModified
- Products: `Product` with offers, ratings only if real and visible
- Local: `LocalBusiness` with address, hours, geo, phone
- Navigation: `BreadcrumbList`
- Events, `Course`, `SoftwareApplication`, `VideoObject` where relevant
- FAQ: `FAQPage` may still help machines understand content, but Google limits FAQ rich results to few sites; do not expect a visual result.

## Rules
1. Markup must match what users can see on the page. Never fabricate reviews or ratings.
2. Use JSON-LD inside a `<script type="application/ld+json">` tag.
3. Link entities with `@id` and `sameAs` (LinkedIn, Wikipedia/Wikidata, social profiles) to strengthen brand entity clarity.
4. Validate with Google's Rich Results Test and Schema.org validator.

## Output
Ready-to-paste JSON-LD, where to place it, and a validation checklist.

---
© 2026 Tania Chakraborty. Licensed under the MIT License (see LICENSE).
