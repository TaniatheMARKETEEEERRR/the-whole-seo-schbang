# The Whole SEO Schbang

An open toolkit of **AI agents and skills** for running SEO, AEO (Answer Engine Optimization) and GEO (Generative Engine Optimization) for a business, from research to content to technical fixes to reporting.

Built by **Tania Chakraborty**, a B2B growth marketer.

## What is this?

- **Skills** (`/skills`) are step-by-step playbooks. Each one teaches an AI assistant how to do one job well, such as keyword research or writing a content brief.
- **Agents** (`/agents`) are "team members" with a role. Each agent uses several skills to complete a bigger job, such as "research everything about my competitors".
- **Templates** (`/templates`) are fill-in-the-blank documents you can reuse.

Works with Claude (as Skills / Projects) and can be pasted into any AI assistant that accepts instructions (ChatGPT, Gemini, etc.).

## The team (agents)

| Agent | Job |
|---|---|
| `goal-intake-agent` | ALWAYS goes first. Interviews you about goals, business, budget and constraints before any work starts |
| `seo-orchestrator` | The manager. Takes a goal, plans the work, hands tasks to the others |
| `research-agent` | Keywords, search intent, audience and market research |
| `competitor-intelligence-agent` | Studies who ranks and who gets cited by AI, and why |
| `content-strategy-agent` | Topic maps, content calendars, briefs |
| `content-writer-agent` | Writes and refreshes SEO, AEO and GEO optimized content |
| `technical-seo-agent` | Crawlability, speed, schema, site structure |
| `ai-search-agent` | Gets your brand cited in ChatGPT, Perplexity, Gemini, Google AI Overviews |
| `authority-agent` | Links, digital PR, brand mentions, E-E-A-T |
| `local-seo-agent` | Google Business Profile, local pages, reviews |
| `humanizer-agent` | Edits drafts so they read like a real person wrote them (voice, rhythm, no AI clichés) |
| `eeat-qa-agent` | Audits content for experience, expertise, authority and trust before publishing |
| `fact-check-agent` | Verifies every claim, stat, quote and source |
| `brand-voice-guardian` | Keeps tone, terminology and claims consistent with the brand |
| `final-qa-gatekeeper` | Last pre-publish check: SEO, AEO/GEO, E-E-A-T, facts, voice, links, schema |
| `conversion-cro-agent` | Turns traffic into leads and sales (CTAs, page layout, forms) |
| `distribution-agent` | Promotes content on LinkedIn, newsletters, communities and repurposes it |
| `analytics-reporting-agent` | Measures results and writes clear reports |

## The skills

**Research:** `keyword-research`, `search-intent-mapping`, `competitor-analysis`, `topical-authority-map`
**Content:** `content-brief`, `seo-article-writing`, `on-page-optimization`, `meta-titles-descriptions`, `content-refresh`, `eeat-content-quality`
**Technical:** `technical-seo-audit`, `schema-markup`, `internal-linking`
**AI search (AEO + GEO):** `aeo-answer-optimization`, `geo-generative-optimization`, `ai-visibility-tracking`
**Authority and local:** `link-building-outreach`, `local-seo`
**Intake and QA:** `goal-intake-interview`, `humanizer-editing`, `fact-checking`, `brand-voice-guide`, `pre-publish-qa-checklist`
**Growth extras:** `conversion-optimization`, `content-distribution`, `ecommerce-seo`, `programmatic-seo`
**Measurement:** `seo-reporting`

## How to use

1. Copy the text of a `SKILL.md` file (or upload the folder as a skill in Claude).
2. Tell your AI: "Use the keyword-research skill. My business is ___, my customers are ___."
3. For bigger jobs, start with `agents/seo-orchestrator.md` and describe your goal.

See `/templates` for ready-made business-context and brief templates. Fill in `templates/business-context.md` once and reuse it everywhere.

## A suggested workflow

0. Start with `agents/goal-intake-agent.md` so the AI asks about your goals first
1. Fill in the business context template
2. Research (keywords, intent, competitors)
3. Plan (topical map, calendar, briefs)
4. Create (write, optimize, add schema)
5. Fix the technical foundation
6. Earn authority (links, mentions, reviews)
7. Humanize, fact-check and QA everything before publishing
8. Measure and refresh, repeat monthly

## Honest note

SEO, AEO and GEO change quickly and nobody can guarantee rankings or AI citations. These playbooks encode good practice: be useful, be accurate, be clear, be trustworthy. Always check current search engine guidelines, and verify tool data before acting on it.

## Contributing

Ideas and improvements are welcome. Open an Issue or a Pull Request.

## License

MIT License. Copyright (c) 2026 Tania Chakraborty. See [LICENSE](LICENSE).
