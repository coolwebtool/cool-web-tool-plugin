---
name: compare-competitors
description: Compare a brand with competitors in AI answers. Use when the user asks where AI skips the brand, who is cited instead, or how competitors compare.
---

# Compare competitors

Use the Cool Web Tool connector after the user signs in with their own Cool Web Tool account.

1. Use the project the user names. If they name a site and no project, run `site_audit` first.
2. Call `get_ai_visibility` and `get_competitor_gaps` for that project.
3. Say where AI answers skip the brand and which competitors the tools name. If a tool says there is no AI visibility scan, say that.
4. Do not invent scores, citation share, traffic, or keyword volumes.
