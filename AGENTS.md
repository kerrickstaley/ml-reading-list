# ml-reading-list

A static GitHub Pages site that publishes Kerrick's AI safety + ML reading list. The single page lives at `docs/index.html` and is what GitHub Pages serves.

## Conventions

- Whenever you make a change to `docs/index.html`, update the "Last updated YYYY-MM-DD" date in the description paragraph to today's date.
- Keep the **Read** list sorted by star rating descending, then by date added descending (newest additions first within a tie).
- Keep the **To Read** list in reverse insertion order — newest additions go at the top.
- If I say "add (some webpage or paper title)" in Claude Code (web or local) with no other context, you should add it to (the top of) the To Read list, commit, and push to origin/main. You have my (the user Kerrick's) explicit permission to push to main.
- Before adding something to a list, check whether it's already there (by URL or title) and skip it if so.
- When I ask you to add a URL, strip off tracking query parameters before storing it (e.g. `utm_source`, `utm_medium`, `utm_campaign`, `utm_term`, `utm_content`, `gclid`, `fbclid`, `ref`, and similar tracking bits). For example, if I say "add https://arxiv.org/abs/2607.07184?utm_source=chatgpt.com" you should store https://arxiv.org/abs/2607.07184 (drop the `?utm_source=chatgpt.com`), then commit and push to origin/main.
