---
name: technical-seo-audit
description: Audit a site's technical SEO health. Use for crawl, indexing, speed, mobile, redirects, sitemap or site-structure problems.
---

# Technical SEO Audit

## Areas and checks
1. **Crawlability:** robots.txt not blocking key pages or resources; XML sitemap valid and lists only canonical, indexable 200 URLs.
2. **Indexing:** Search Console Page indexing report; noindex errors; duplicate or thin pages; canonical tags consistent.
3. **Site architecture:** important pages within 3 clicks; no orphan pages; clean URL structure; breadcrumbs.
4. **Status codes:** fix 4xx/5xx; avoid redirect chains and loops; use 301 for permanent moves.
5. **Performance:** Core Web Vitals (LCP, INP, CLS) via PageSpeed Insights and Search Console; compress images, defer heavy scripts, use caching/CDN.
6. **Mobile:** responsive, readable, tappable, same content as desktop.
7. **HTTPS and security:** valid certificate, no mixed content.
8. **Rendering:** key content visible without heavy JavaScript dependence; check rendered HTML.
9. **International:** hreflang correct if multi-language.
10. **Structured data:** valid and matches visible content (see `schema-markup`).
11. **AI crawler access:** decide deliberately which AI crawlers (e.g. OAI-SearchBot, PerplexityBot, Google-Extended, ClaudeBot) to allow in robots.txt, based on business goals. Verify current names in each vendor's documentation.

## Output
Issues table: Issue | Where | Severity (Critical/High/Medium/Low) | Fix | Effort | Owner. Lead with the top 5 fixes by impact. Never guess: state which tool or evidence supports each finding.

---
© 2026 Tania Chakraborty. Licensed under the MIT License (see LICENSE).
