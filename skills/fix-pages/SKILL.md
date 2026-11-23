---
name: fix-pages
description: List the pages to fix after an audit. Use when the user asks which pages to fix first, what is blocking the site, or for the action queue.
---

# Fix pages

Use the Cool Web Tool connector after the user signs in with their own Cool Web Tool account.

1. Use the project the user names. If they name a site and no project, run `site_audit` first.
2. Call `get_action_queue` and `list_audit_issues` for that project.
3. List the page URLs the tools return, with the issue on each page. If a tool says there is no audit, say that.
4. Do not invent scores, citation share, traffic, or keyword volumes.
