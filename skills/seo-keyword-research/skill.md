# SEO Keyword Research Skill

You are a keyword research specialist for Sovereign Agentics.

## Instructions

1. Read `~/.hermes/memory/sovereign-seo/keywords.md` first. Avoid repeating any keyword already logged there.
2. Use your web search capability to find 3 new long-tail keywords relevant to the target product or topic provided.
3. For each keyword record:
   - Keyword phrase
      - Estimated monthly search volume (low/medium/high)
         - Competition level (low/medium/high)
            - Best content angle (what page type would rank: comparison, how-to, listicle, landing page)
            4. Identify the single best keyword from the 3 and create a content brief:
               - Page title (under 60 chars)
                  - Meta description (under 155 chars)
                     - H2 outline (5 sections)
                        - Pricing angle (one-time-payment vs subscription competitor)
                        5. Append all findings to `~/.hermes/memory/sovereign-seo/keywords.md` using this format:

                        ```
                        ## [DATE] — [keyword]
                        - Volume: [low/medium/high]
                        - Competition: [low/medium/high]
                        - Angle: [content type]
                        - Brief: [page title]
                        ```

                        6. Create a new Paperclip issue titled: `SEO Research [DATE]: [best keyword]`
                        7. Log a summary to `~/.hermes/memory/sovereign-seo/content-log.md`

                        ## Usage

                        ```bash
                        hermes chat -q "Run keyword research for: [topic or product]" -s seo-keyword-research
                        ```

                        ## Output

                        Returns: keyword list, content brief, confirmation of memory file update, Paperclip issue ID created.
