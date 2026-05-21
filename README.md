# sovereign-seo-skills

**6 installable Hermes SEO skills for Paperclip — built for Sovereign Agentics.**

Install in seconds via Paperclip's Skills page. Each skill runs on `qwen2.5:14b` locally via Ollama. No cloud API required.

---

## Skills Included

| Skill | Description |
|---|---|
| `seo-keyword-research` | Finds 3 long-tail keywords per run, logs to persistent memory |
| `seo-content-brief` | Full content brief: title, meta, H2 outline, competitor gaps, pricing angle |
| `seo-page-builder` | Generates complete HTML landing pages deployed to Netlify |
| `seo-audit` | On-page SEO audit: 10-point checklist, PASS/FAIL, prioritized fixes |
| `seo-meta-writer` | Title tags, meta descriptions, Open Graph, Twitter Card, JSON-LD schema |
| `seo-competitor-analysis` | Competitor breakdown, content gaps, one-time-payment advantage analysis |

---

## Install via Paperclip

1. Open Paperclip at `http://127.0.0.1:3100`
2. 2. Navigate to **Skills**
   3. 3. Click **Paste GitHub URL**
      4. 4. Paste the URL for the skill you want:
        
         5. ```
            https://github.com/raijinhabiki-maker/sovereign-seo-skills/tree/main/skills/seo-keyword-research
            https://github.com/raijinhabiki-maker/sovereign-seo-skills/tree/main/skills/seo-content-brief
            https://github.com/raijinhabiki-maker/sovereign-seo-skills/tree/main/skills/seo-page-builder
            https://github.com/raijinhabiki-maker/sovereign-seo-skills/tree/main/skills/seo-audit
            https://github.com/raijinhabiki-maker/sovereign-seo-skills/tree/main/skills/seo-meta-writer
            https://github.com/raijinhabiki-maker/sovereign-seo-skills/tree/main/skills/seo-competitor-analysis
            ```

            ---

            ## Usage

            ```bash
            # Keyword research
            hermes chat -q "Run keyword research for: one-time payment SEO tools" -s seo-keyword-research

            # Content brief
            hermes chat -q "Create content brief for keyword: plagiarism checker no account" -s seo-content-brief

            # Build landing page
            hermes chat -q "Build landing page for: Sovereign SEO | keyword: ai seo tool one time payment | price: $97" -s seo-page-builder

            # Audit a page
            hermes chat -q "Audit this page: https://sovereign-seo.netlify.app" -s seo-audit

            # Write meta tags
            hermes chat -q "Write meta tags for: Sovereign SEO | keyword: seo tool no subscription | price: $97" -s seo-meta-writer

            # Competitor analysis
            hermes chat -q "Competitor analysis for keyword: local seo tool no monthly fee" -s seo-competitor-analysis
            ```

            ---

            ## Requirements

            - [Paperclip](https://paperclip.sh) — local AI agent platform
            - - [Hermes](https://github.com/raijinhabiki-maker) — installed and configured
              - - Ollama running `qwen2.5:14b` locally
                - - `GH_TOKEN` environment variable set in Paperclip for GitHub write operations
                 
                  - ---

                  ## Premium Kit — $197

                  The full Sovereign SEO Premium Kit includes these 6 skills plus:

                  - Gumroad product listing templates
                  - - 4-Layer Daily SEO Pipeline (Paperclip Routine)
                    - - Netlify deployment automation
                      - - Google Search Console verification workflow
                        - - Commercial license — use for clients
                         
                          - **[Get the Premium Kit on Gumroad](https://raijin24.gumroad.com/l/sovereign-seo)**
                         
                          - ---

                          ## License

                          MIT — free to use, modify, and self-host. Commercial use requires the Premium Kit license.

                          Built by [Sovereign Agentics](https://raijin24.gumroad.com) · Anchorage, Alaska
