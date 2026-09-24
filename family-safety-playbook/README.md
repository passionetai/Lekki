# The Family Safety Playbook — working folder

Everything for the product lives here. **Start with [`BLUEPRINT.md`](BLUEPRINT.md)**: it's written so you can paste it into any LLM (Claude, ChatGPT, Gemini) and carry on working.

| Path | What |
| --- | --- |
| `BLUEPRINT.md` | Full product brief: offers, funnel, structure, brand, voice, verified facts, fix list |
| `QUESTIONS.md` | Open questions and decisions log. Ask questions about the package here |
| `DECISIONS/001-brother-affiliate-vs-alt-site.md` | Brother: affiliate link vs separate site (recommendation + Selar steps) |
| `content/playbook-full-text.txt` | Full text of the 110-page Playbook (extracted from the PDF) |
| `content/starter-checklist-text.txt` | Free checklist text |
| `content/whatsapp-nurture.md` | Greeting, 5-day sequence, weekly tips |
| `source/pdfs/` | Final PDFs (Playbook + Starter Checklist). `partner/` holds the brother's copies (only the links differ) |
| `PARTNER-LINKS.md` | Where the brother's Selar + Jumia affiliate links are placed, and what's left to check |
| `web/main/index.html` | familysafetyplaybook.com landing page (Notion version, broken links fixed) |
| `web/alternate/index.html` | Alternate/partner page: new angle, 60-second readiness quiz, sticky mobile CTA. Currently set to the brother's Selar affiliate link. Edit `CHECKOUT_URL`, `WHATSAPP_URL`, `PARTNER_NAME` at the top |

## Deploying a page
Both pages expect `logo.png` (the main page also expects `mockup.png`) **in the same folder**. They aren't in the repo yet. Export them from the Brand Assets page in Notion. Then upload the folder to Cloudflare Pages (Workers & Pages → Create → Upload assets).

## Missing from the repo
Emergency Quick-Start Kit PDF · brand images · "First 7 Days" video scripts and production line-up.
