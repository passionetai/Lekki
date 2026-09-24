# The Family Safety Playbook — Product Blueprint

> **For an LLM reading this:** this file is the working brief for an existing digital info-product. Read it fully before you suggest or write anything. It covers what exists, what's live, how the business works, the voice, the facts, and the known problems. The full product text is in `content/playbook-full-text.txt` (110-page PDF, extracted). The free lead magnet is in `content/starter-checklist-text.txt`. Don't invent statistics. Reuse the verified ones in §9, or flag any new claim as *needs a source*.
>
> Last updated: 2026-09-24 · Owner: Jerry Asemota · Source of truth before this file: a Notion workspace (not in this repo)

---

## 1. One-paragraph summary

**The Family Safety Playbook (Nigeria Edition)** is a premium digital guide (PDF, 110 pages). It teaches everyday Nigerian families how to avoid kidnapping, robbery and scams, and what to do if the worst happens. It is sold through a funnel: organic social content brings people to a free WhatsApp Channel, whose welcome gift is a Starter Checklist. From there they're offered a ₦2,500 Quick-Start Kit, then the ₦20,000 Playbook (₦15,000 launch price). Later rungs are a Templates order bump, affiliate referrals to security vendors, a paid WhatsApp community and a ₦55,000 premium bundle. The plan is to build in Nigeria first, then clone the funnel for Kenya, Ghana and the diaspora.

**Positioning line:** *"The families who stay safe aren't lucky — they're prepared."*
**Core idea of the book:** every criminal needs **Surprise, Isolation, Control**. Awareness removes surprise, layers and habits deny isolation, and a practised plan removes their control.
**Tone rule:** calm, not fear-mongering. The ads use a fear hook, but the product itself sells calm and preparation.

---

## 2. Assets inventory — what exists and where

| Asset | Status | Location |
| --- | --- | --- |
| Playbook PDF (110 pp, designed, final) | ✅ Done | `source/pdfs/The-Family-Safety-Playbook-Nigeria-Edition.pdf` |
| Playbook full text (extracted) | ✅ | `content/playbook-full-text.txt` |
| Free Starter Checklist PDF (2 pp) | ✅ Done | `source/pdfs/The-Family-Safety-Starter-Checklist.pdf` |
| Starter Checklist text | ✅ | `content/starter-checklist-text.txt` |
| Emergency Quick-Start Kit (₦2,500) | ✅ Written in Notion; **PDF not in repo** | Contents summarised in §5.2 |
| Sales page copy | ✅ | Carried in `web/main/index.html` |
| Main landing page (familysafetyplaybook.com) | ✅ Built; hosted on Cloudflare Pages | `web/main/index.html` |
| Alternate / partner landing page | 🆕 Built in this repo | `web/alternate/index.html` |
| WhatsApp nurture messages | ✅ | `content/whatsapp-nurture.md` |
| Brand assets (logo, cover, 3D mockup) | ✅ In Notion; **image files not in repo** | Need `logo.png`, `mockup.png`, `cover.png` |
| Selar store + Playbook product | ✅ Live (see link conflict in §11) | Selar |
| Recommended Safety Gear page (Jumia affiliate) | ✅ | Notion page; link in PDF |
| Social plan (IG, TikTok, X, FB) | ✅ Plan written; accounts being set up | Notion |
| "First 7 Days" video scripts + production line-up | ⚠️ Named in Notion, **content not supplied** | — |
| Templates toolkit (Rung 2) | 🟡 Not built | — |
| Premium bundle ₦55,000 | 🟡 Defined, not built | — |

### Live links (found inside the PDFs)
- WhatsApp Channel: `https://whatsapp.com/channel/0029VbCP5YI7T8bcUcxd0Z0I`
- Playbook checkout (the button in the Starter Checklist): `https://selar.com/791a812429`
- Jumia affiliate link (Playbook gear appendix): `https://jforce.jumia.com.ng/s/YcDAHMy`
- Direct WhatsApp chat: `https://wa.me/2348053717830`
- Support email: `info@familysafetyplaybook.com`
- Domain: `familysafetyplaybook.com`

---

## 3. The business model

### 3.1 Funnel (organic first, then paid)
```
Organic content (IG · TikTok · X · Facebook) — daily value + fear-hook-then-fix
   ↓
Free WhatsApp Channel join  ← the real lead magnet (welcome gift: Starter Checklist)
   ↓
₦2,500 Emergency Quick-Start Kit (tripwire; one-time offer right after opt-in)
   ↓
₦20,000 Core Playbook (launch ₦15,000) — main profit
   ↓  order bump: Templates ₦4,000 (Rung 2) · affiliate gear/vendors (Rung 3)
₦55,000 Premium bundle (Playbook + Templates + Community + 1 consult) — anchor
   ↓
THEN paid ads: scale proven organic posts → Channel join; retarget with Kit/Playbook
```

### 3.2 Value ladder
| Offer | Price (NG) | Role |
| --- | --- | --- |
| WhatsApp Channel + Starter Checklist | Free | Capture the list |
| Emergency Quick-Start Kit | ₦2,500 | Recoup ad spend, filter buyers. 7-day refund |
| **Core Playbook** | **₦20,000 (launch ₦15,000)** | Main profit. 30-day no-questions refund |
| Templates order bump | ₦4,000 (₦7,500 standalone) | Rung 2 |
| Premium bundle | ₦55,000 | Anchor + margin |
| Paid community | ₦3,000–5,000/mo or ₦25,000/yr | Rung 4 (dormant) |

### 3.3 Rungs and activation triggers
| Rung | What | Status | Trigger |
| --- | --- | --- | --- |
| 1 | Playbook | 🟢 Active | — |
| 2 | Templates & toolkits (Family Emergency Plan, go-bag list, staff vetting form, child pickup card, home audit, contacts sheet, vendor directory) | 🟡 Standby | 20 Playbook sales |
| 3 | Affiliate / lead-gen: CCTV, trackers, anti-shatter film, doors, response firms, safe rooms. 5–15% commission or flat fee, plus directory listing fees. Jumia affiliate already live in the PDF | 🟢 Passive | — |
| 4 | WhatsApp community: free nurture now, paid tier later (area alerts, monthly briefing + Q&A, vendor discounts) | 🟡 Foundation live, paywall off | 500+ subscribers or steady sales |

### 3.4 Markets (build Nigeria first, clone the rest)
| Market | Lead fear | Core price | Order |
| --- | --- | --- | --- |
| Nigeria | Kidnapping, banditry, school abductions | ₦20,000 | 1st |
| Kenya | Abductions, urban violent crime, cybercrime | ~KSh 2,500 | 2nd |
| Ghana | Urban robbery, online scams | ~GHS 300 | 3rd |
| Diaspora | "Protect family back home" | $35–60 (Gumroad) | Parallel |

### 3.5 Tools and stack
Notion (writing), Canva (layout; 6×9 in), Selar (NGN checkout and delivery), Gumroad (USD, planned), Cloudflare Pages (site hosting), WhatsApp Business + Channel (list), CapCut (video template), Jumia jForce (gear affiliate).

---

## 4. The core product — Playbook structure

110 pages. Page 2 is copyright and disclaimer (© 2026 Jerry Asemota; personal-use licence; not professional advice). Every module ends with a **✅ checklist** and a **📝 worksheet**.

| # | Title | Subtitle | PDF page | What it covers |
| --- | --- | --- | --- | --- |
| — | Introduction | The new reality of safety in Nigeria | 4 | Stats, "not a book about fear", Surprise/Isolation/Control, how to use the book |
| 1 | Situational Awareness | Seeing trouble before it reaches you | 10 | Awareness Ladder (4 gears, after Cooper's colour code); being "marked"; transition points; trusting instinct; **3-turn follow test**; household awareness; 30-second drills; myths |
| 2 | Daily Movement Safety | Commuting, traffic, ATMs & ride-hailing | 21 | "One chance" and express kidnapping; Abuja hotspots; ride-hailing rules (match plate, share trip, **never go off-app**); danfo/keke/okada; ATMs; go-slow habits; comply if robbed |
| 3 | Home & Estate Security | Turning your home into a hard target | 29 | 5 layers: perimeter/lighting (solar backup) → gate (**verify before you open**, visitor script) → doors/windows + **gate-arrival drill** → detection (CCTV/alarm on backup) → safe core. Staff and artisan vetting (NIN, guarantor, references) |
| 4 | Child & School Safety | Protecting our children at the gate and beyond | 39 | Mass abduction vs everyday child-targeting; **pickup code word + rescue word**; authorised pickup list; teaching children; insider risk; online oversharing; questions to ask schools; missing child: the first hour |
| 5 | Vehicle & Travel Safety | The car, the checkpoint, and the open road | 49 | Daily drive vs interstate; travel by day; pre-trip prep; tracker/film/dashcam; real vs fake checkpoints; crashes as the underrated risk; breakdowns; comply if carjacked |
| 6 | If the Worst Happens | Kidnap, ransom & getting your people home | 58 | 4 kidnap types; survival in captivity; family's first hour (point-person, 112, log, go silent online); negotiation basics (**proof of life first**); the ransom-payment law (2022); **virtual/fake kidnap** scam; after release |
| 7 | Digital & Financial Safety | Protecting your money, identity & family online | 68 | Fake bank call/OTP/USSD; SIM-swap; phishing and loan apps; Ponzi (CBEX 2025); romance scams; **AI voice clones → family safe word**; digital footprint; child online safety and sextortion; what to do if defrauded |
| 8 | Your Family Emergency Plan | One plan your whole household has practised | 80 | Contact tree and point-person; emergency numbers card; **all code words in one table**; meeting points and scenarios; go-bag; document vault; roles; drill twice a year; one-week challenge |
| — | A Final Word | | 91 | |
| — | Quick-Reference Safety Cards (10) | | 93 | 1 Emergency numbers · 2 3-turn test · 3 Ride-hailing · 4 ATM · 5 Gate verification · 6 School pickup · 7 Highway · 8 Ransom call · 9 OTP/SIM-swap · 10 Plan summary |
| — | Recommended Safety Gear | | 100 | By module; Jumia affiliate link; honest affiliate disclosure |
| — | Emergency Contacts Directory | | 102 | National, fraud, helplines, Lagos example, fill-in local lines |
| — | Sources & Verification | | 107 | |

**The code-word system (a signature feature):** "Act now" word (M1) · Pickup word (M4) · Rescue word (M4) · Family safe word (M6/M7) · Proof-of-life question (M6).

---

## 5. Supporting products

### 5.1 Free Starter Checklist (2 pp) — lead magnet / Channel welcome gift
12 habits grouped as Awareness & movement, Home & estate, Children & school, Travel, Money & online, and Your emergency plan. It includes a numbers table (112, PCRRU WhatsApp, NSCDC 199, FRSC 122, NEMA, NCDC 6232), a "Going deeper" pointer to Modules 3 and 8, a WhatsApp Channel button + QR code, and an upsell to the Playbook at ₦15,000 (was ₦20,000).

### 5.2 Emergency Quick-Start Kit (₦2,500) — tripwire
"Emergency-ready in 30 minutes." Contents: 1-page Family Emergency Plan (fill-in) · Family code word setup · ICE cards per person · Go-bag checklist (house + car) · 6 "If it happens" action cards (kidnap/ransom call, robbery, fire, medical, child missing in public, road/checkpoint) · Verified contacts. Selar product: suggested link `selar.co/emergencykit`, 7-day refund. Its delivery page upsells the Playbook. Sold as a one-time offer right after the checklist opt-in; no separate website.

### 5.3 WhatsApp engine
Greeting auto-reply → keyword **SAFETY** sends the checklist → 5-day sequence (Story → Quick win → Proof → Offer → Close) → weekly tips, with a soft pitch every 4–5 tips. Full text is in `content/whatsapp-nurture.md`.

---

## 6. Brand

| Token | Hex | Use |
| --- | --- | --- |
| Deep navy | `#13294b` | Primary background, titles |
| Navy 2 | `#1f3a5f` | Gradients |
| Teal | `#2a9d8f` | Accents, kickers |
| Green | `#1f9d57` | Buy buttons / CTAs |
| Warm gold | `#e7b53c` | Highlights, badges, key numbers |

- Fonts: an elegant serif for headlines (Georgia / Playfair Display) and a clean sans-serif for body text.
- Logo: a shield enclosing a family. Handles: `@familysafetyplaybook` (X: `@FamilySafetyNG`).
- Bio: *"Calm, practical safety guides for Nigerian families 🛡️ Daily tips + free starter checklist 👇"*
- Sign-off: **"Stay aware. Stay prepared. Stay free."**
- Video format: 9:16, voiceover + kinetic captions (gold key word) on a navy→teal moving background; logo in the corner; identical end card.

## 7. Voice and copy rules
- A calm insider Nigerian voice, warm and practical. It uses local terms naturally: *danfo, keke, okada, "one chance", go-slow, NEPA, gateman, oga, face-me-I-face-you, "I dey wait for person"*.
- Structure: **hook → hard truth → hope turn → the system → proof/value stack → risk reversal → CTA.**
- Recurring devices: "two endings" mini-stories, 📞 scripts to say out loud, checklists, worksheets, and 🛒 "Get the gear" pointers.
- **Never** gory detail, never shaming, never paranoia. "Comply over property" everywhere. No legal or negotiation advice beyond general guidance.
- The 80/20 rule on social: 80% value, 20% promotion. Every post drives to the WhatsApp Channel.

## 8. Customer and objections
**Who:** parents on the school run, interstate drivers, young professionals riding home after dark, traders, families putting up their first gate. Facebook's older family audience is the strongest buyer pool.
**FAQ objections already handled:** "just common sense" · "will it scare my kids" · "my area isn't dangerous" · delivery · after-sale support.

## 9. Verified facts in use (keep consistent)
- NBS Crime Experience & Security Perception Survey (May 2023–Apr 2024): **~2.2M kidnapping *incidents***, **₦2.23T** ransom, ~65% of affected households paid, average **₦2.67M**; ~52M crime incidents in total.
- SBM Intelligence (Jul 2024–Jun 2025): **4,722 abducted in 997 incidents**, 762 killed; ~₦48bn demanded, ~₦2.57bn paid.
- 2026: >1,000 Nigerians abducted in the first weeks (civic groups).
- Digital payment fraud **−51%: ₦52.26bn (2024) → ₦25.85bn (2025)**, ~67,515 cases, Lagos ~63% (NIBSS).
- School attacks: Papiri, Niger State, 315 taken (Nov 2025, all freed by Christmas); Kebbi, 25 girls; 2026: Mussa (Borno) 50+, Oyo 39 students + 7 teachers; >1,500 schoolchildren taken since Chibok 2014; ~19M children out of school.
- 2022 law: paying a ransom is a crime (minimum 15 years).
- Emergency: 112 (national) · NSCDC 199 · FRSC 122 · NEMA 0800 2255 6362 · NCDC 6232 · **PCRRU = Police *Complaint* Response Unit**: 0913 333 3785/6, WhatsApp 0805 700 0003 · EFCC 0809 332 2644 · NAPTIP 627 · LASEMA 767.

---

## 10. Current plan and next actions
**Done:** Playbook, checklist, Kit copy, brand, sales page, landing page, Selar, WhatsApp engine.
**Phase 1 (organic, weeks 1–2):** set up IG/TikTok/X/FB → post daily → drive everything to the Channel → sell the Kit and Playbook to the warm audience → collect first sales and testimonials.
**Phase 2 (paid):** turn the winning organic posts into ads → Channel join; retarget with Kit/Playbook; test one straight-to-Kit ad set; track cost per buyer and revenue per subscriber.
**Parallel:** pitch 5–10 security vendors (Rung 3); at 20 sales switch on Templates; at 500 subscribers switch on the paid community.
**New:** partner/affiliate channel for a family member (see `DECISIONS/001-brother-affiliate-vs-alt-site.md`).

---

## 11. Known inconsistencies and issues (fix list)
1. **Checkout link conflict.** The docs say `selar.co/familysafetyplaybook`, but the live PDF button goes to `selar.com/791a812429`. Confirm which one is canonical, and make every asset use the same link.
2. **Landing page placeholders.** `PASTE_YOUR_CHECKOUT_LINK_HERE` appeared 3× in the Notion HTML, and the `wa.me` hrefs were wrapped in `<…>`, which broke them. Both are fixed in `web/main/index.html`.
3. **Headline accuracy.** "2.2 million Nigerians were kidnapped" is not what the NBS reported: it counted **2.2M kidnapping *incidents*** from a household survey. The Playbook text is correct; the sales headline overstates it. Suggested wording: *"2.2 million kidnapping incidents in a single year."* (Ad platforms and consumer law both punish misleading claims.)
4. **PCRRU label.** The Starter Checklist calls it "Police rapid response". It is the Police **Complaint** Response Unit. The Kit copy repeats the label.
5. **Module order in the Selar description** doesn't match the book (it lists kidnap as module 7 and "Travel" with ✈️). Rewrite it from §4.
6. **Page count.** The Rung 1 spec says 35–50 pages; the final book is 110. Update the claims ("110-page guide" is a selling point).
7. **Price display.** The ₦20,000 core price is mostly shown as ₦15,000 "launch". Decide when the launch price ends, or the scarcity claim goes stale.
8. **Cards count.** The outline said 11 quick-reference checklists; the product ships 10. Use **10** everywhere.
9. **Refunds differ** (Kit 7 days, Playbook 30 days). That's intentional; keep it explicit on each page.
10. **The Rung 2 lead-magnet idea** (the Emergency Contacts sheet) was superseded by the Starter Checklist.
11. **Missing in repo:** the Kit PDF, brand images, and the "First 7 Days" scripts and production line-up.

## 12. How to work on this repo
```
family-safety-playbook/
├── BLUEPRINT.md            ← this file (feed it to any LLM first)
├── QUESTIONS.md            ← open questions + decisions log
├── DECISIONS/              ← one file per decision
├── content/                ← extracted text + copy (edit copy here)
├── source/pdfs/            ← final PDFs (don't edit; replace on re-export)
└── web/
    ├── main/index.html     ← familysafetyplaybook.com
    └── alternate/index.html← partner/affiliate page (one CHECKOUT_URL to change)
```
**Prompt to start any LLM session:** *"Read BLUEPRINT.md and QUESTIONS.md. You are helping Jerry grow The Family Safety Playbook. Keep the calm insider Nigerian voice, reuse only the facts in §9, and tell me which §11 issues your work touches."*
