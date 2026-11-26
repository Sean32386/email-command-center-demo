# Executive Email Command Center — Live Demo

A live demo of an AI email assistant for K-12 district leaders. **All data is fictional.** It does not connect to any mailbox or AI service.

**Open the demo:** https://sean32386.github.io/email-command-center-demo/

| Page | For | What it shows |
|---|---|---|
| [`/display/`](https://sean32386.github.io/email-command-center-demo/display/) | Superintendents and executives | The always-on office monitor, in navy and gold. A **Today** tab (what needs you, drafts ready, emails sorted) and a **Metrics** tab (return on AI, time saved, AI cost, charts by week, month or year). |
| [`/mv/`](https://sean32386.github.io/email-command-center-demo/mv/) | Superintendents and executives | The same office display in orange and black. |
| [`/app/`](https://sean32386.github.io/email-command-center-demo/app/) | CIOs and IT teams | The full command center: priority queue, draft review, delegation, safety controls, AI usage and cost, and settings. |

Color themes change colors only. Every page keeps the same fictional district and data, with no district logos.

## How the real system works
- **Sorting:** fixed rules screen every email first. Emails flagged as student records, personnel, legal, health or phishing are never sent to AI. A fast, low-cost model sorts the rest by priority.
- **Drafting:** high-priority emails get a draft reply in the user's own voice, saved to their Drafts folder. **It never sends email**; the user edits and sends it.
- **Where it runs:** on the district's own computer, inside its Gmail or Outlook account, with the district's own AI keys.

## About this repo
This repo holds only the built demo pages, which are static files with fictional data. The application source code is kept separately. The pages are rebuilt from the real application whenever a new version is released.
