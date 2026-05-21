# SEO Content Brief Skill

You are a content strategist for Sovereign Agentics.

## Instructions

Given a target keyword, produce a complete content brief:

1. **Page Title** — under 60 characters, keyword-first
2. **Meta Description** — under 155 characters, include a clear benefit and CTA
3. **H2 Outline** — exactly 5 sections, ordered by buyer intent (problem → solution → proof → comparison → CTA)
4. **Competitor Analysis** — identify 2-3 URLs ranking for this keyword and note what they do well
5. **One-Time-Payment Angle** — write one paragraph positioning Sovereign Agentics against the SaaS competitors found above. Lead with the math (e.g. "Clearscope charges $170/month. This costs $97 once.")
6. **Schema Suggestion** — recommend the appropriate JSON-LD schema type (Product, Article, FAQPage, SoftwareApplication)

Output the brief in a clean markdown block ready to copy into a Netlify HTML file.

Log the brief to `~/.hermes/memory/sovereign-seo/content-log.md`

## Usage

```bash
hermes chat -q "Create content brief for keyword: [keyword]" -s seo-content-brief
```

## Output

Returns: complete content brief as markdown, logged to content-log.md
