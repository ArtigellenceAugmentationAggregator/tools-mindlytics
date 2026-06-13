# Mindlytics Tools

**Tell me your situation — I'll build your AI income plan.**

Live at **[tools.mindlytics.xyz](https://tools.mindlytics.xyz)**

A free, situation-first AI-tools aggregator and life-situation planning engine. Describe where you are in plain language — in any of 25 languages — and get a personalised 6-horizon roadmap: free tools, paid tiers at every budget, free courses from real providers, what to sell, and honest income ranges. Week 1 to year 3.

Built and maintained solo from Sydney. Sister site to the podcast-first [mindlytics.xyz](https://mindlytics.xyz).

## What's here

- **Pinpoint** — natural-language life-situation planner. Currently runs in preview mode with sample archetype plans; the live AI planner activates once the secure server proxy is deployed.
- **The Wedge** — the same tool library browsable six ways: by category, profession, usage, industry, life moment, and budget.
- **25-language support** — 15 world languages + 10 Indian languages, with RTL for Arabic and Urdu. Page chrome is translated; full UI is rolling out. Machine-assisted translations are marked as such.
- **Listen** — a short spoken audio brief.
- **Income Stories, Skills, Process, FAQ** — real tool names, real course links, documented income patterns.

## Honesty principles

This project follows a strict no-overclaiming rule. Income ranges are documented public patterns, **not** guarantees. Tool availability, free tiers, and prices change — always check the provider's own page. Pinpoint output is AI-generated and can be wrong; use it as a starting structure to research from, never as a final decision. Not financial, legal, medical, immigration, or tax advice.

## Tech

- Single self-contained `index.html` (HTML5 + vanilla JS + a CSS design system)
- Hosted on GitHub Pages with a custom domain via CNAME
- AEO/SEO/GEO layer: structured data (WebApplication + Organization + FAQPage), `robots.txt`, `sitemap.xml`, `llms.txt`, AI-crawler and geo meta
- Live planner (when active): browser → Cloudflare Worker proxy → AI provider, with training opt-out

## Files

| File | Purpose |
|---|---|
| `index.html` | The entire site |
| `favicon.svg` | Site icon |
| `site.webmanifest` | PWA / install metadata |
| `robots.txt` | Crawler directives — AI answer-engines explicitly welcomed |
| `sitemap.xml` | Sitemap |
| `llms.txt` | Plain-language summary for AI answer-engines |
| `CNAME` | Custom domain |

## Contact

Raj Singh · [raj@artigellence.com](mailto:raj@artigellence.com) · ABN 83 988 690 362 · Sydney, Australia
