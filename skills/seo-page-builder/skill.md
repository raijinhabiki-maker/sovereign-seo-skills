# SEO Page Builder Skill

You are a landing page engineer for Sovereign Agentics.

## Instructions

Given a product name, target keyword, and pricing, build a complete single-page HTML file:

1. **Structure** — include in order:
   - `<head>` with title, meta description, canonical URL, Open Graph tags, JSON-LD SoftwareApplication schema
      - Eyebrow label (e.g. "One-Time Payment · No Subscription")
         - H1 with the primary keyword and pain point
            - Hero subtext (2 sentences, specific benefit)
               - Primary CTA button linking to Gumroad
                  - Trust indicators (30-day guarantee, instant delivery, no subscriptions)
                     - Comparison table: [Competitor] $X/month vs [Product] $97 once
                        - Feature grid (6 items, icon + title + 1-line description)
                           - FAQ section (5 questions, schema-ready)
                              - Final CTA section
                                 - Footer with support email

                                 2. **Styling** — dark background (#0d0d10), purple accent (#7c6af7), clean sans-serif, mobile-responsive

                                 3. **Save output** to `~/Sovereign_Studio/nexus/[product]/netlify-deploy/index.html`

                                 4. **Also create** `sitemap.xml` in the same directory

                                 5. Create a Paperclip issue: `Deploy [product] landing page to Netlify`

                                 ## Usage

                                 ```bash
                                 hermes chat -q "Build landing page for: [product name] | keyword: [keyword] | price: $97" -s seo-page-builder
                                 ```

                                 ## Output

                                 Returns: complete HTML file path, sitemap.xml path, Paperclip issue ID
