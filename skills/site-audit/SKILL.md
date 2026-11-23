---
name: site-audit
description: Run a site audit for a URL. Use when the user asks to audit a site, check a page, or find what blocks a brand in search and AI answers.
---

# Site audit

Use the Cool Web Tool connector after the user signs in with their own Cool Web Tool account.

1. Ask for the site URL if the user has not given one.
2. Call `site_audit` for that URL.
3. Report the issues and page URLs the tool returns. If the tool says there is no audit, say that.
4. Do not invent scores, citation share, traffic, or keyword volumes.
