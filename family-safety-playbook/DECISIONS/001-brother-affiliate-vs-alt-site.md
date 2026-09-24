# Decision 001: Brother's channel — separate website or affiliate link?

**Status:** Recommendation made, waiting on Jerry · **Date:** 2026-09-24

> Note on "chat memories": this was prepared in a Claude Code session, which can't see your claude.ai chat history or memories. It's based only on the Notion export and the PDFs in this repo. If an earlier chat settled something that conflicts with this (for example, a commission split you already agreed), that chat wins. Add it to `QUESTIONS.md`.

## The question
Your brother wants to sell the Playbook. There are two options:
- **A. Alternate website:** his own site and his own checkout, and he keeps the revenue.
- **B. Affiliate link:** he gets a tracked link to *your* Selar product, and his sales pay him commission (you want him to keep all of it).

## Recommendation: **B (affiliate link), plus his own landing page that points at it**

Give him an affiliate link on the existing Selar product. If he wants his own page to share, deploy `web/alternate/index.html` with his link in the one `CHECKOUT_URL` slot. He gets "his own site" and all the commission, and you keep a single product, a single delivery flow, a single refund policy and one set of sales data.

### Why not a separate website with its own checkout
| Issue | Separate site + own checkout | Affiliate link |
| --- | --- | --- |
| Setup | New Selar store/product, bank account, uploaded PDF, domain | Minutes |
| Product control | A copy of your PDF lives in his store. The © notice says "no resale without permission", so you'd have to license it to him | You deliver; he never holds the file |
| Updates (new edition, fixed stats, the PCRRU label) | Must be re-uploaded in two places | One place |
| Refunds and support | Split; buyers see two sellers for the same book | One policy, one support line |
| Your funnel data (the 20-sale trigger for Rung 2, testimonials) | His sales are invisible to you | Counted in your dashboard |
| Upsells (Kit, Templates, bundle) | He'd need to rebuild them | Buyers land in your ecosystem |
| Brand trust | Two storefronts for one product look like a knock-off | One brand |
| His payout | He gets 100% minus Selar fees | Commission % you set, minus fees |

**The only real advantage of option A is that he owns the customer relationship and the payout rail.** If you're giving him all the commission anyway, the affiliate route gives him nearly the same money with none of the duplication.

## How to set it up (Selar)
1. In Selar, open the Playbook product → turn on **affiliates** for the product (Selar calls this its affiliate program).
2. Set the commission percentage. You want him to get "all the commission", so set it to the **maximum Selar allows**. ⚠️ Check the current cap in Selar; this doc hasn't verified it. If the cap is below what you want to give him, pay him the difference each month from your Selar payout records.
3. He signs up as an affiliate with his own Selar account (and bank details), requests or joins your product, and copies his **unique affiliate link**.
4. Paste that link into `CHECKOUT_URL` at the top of `web/alternate/index.html` and deploy it (Cloudflare Pages, a free `*.pages.dev` subdomain, or his own domain).
5. Test it: open his page, click Buy, and confirm the Selar URL carries his affiliate reference.
6. Optional: give him the ₦2,500 Kit and a WhatsApp script pack as well, so he can run the same funnel.

### One thing to watch: attribution vs your Channel
If his buyers join **your** WhatsApp Channel first and later buy through **your** link, he loses the sale. Either:
- give him his own WhatsApp number/Channel and keep his audience separate (the alternate page is set up this way; see `WHATSAPP_URL`), or
- agree that anyone he refers who later buys still counts for him (manual tracking), or use a dedicated coupon code for him.

## When option A *would* make sense
- He wants to **adapt the product** (a different country edition, his own bonuses, his own voice). Then write a licence: rights, price floor, update duties, revenue share.
- Selar affiliates aren't available to him (location/KYC), or the commission cap is too low and paying him manually is a hassle.
- You plan to split the brand deliberately, for example **he runs the diaspora/Gumroad USD version** while you run NGN. That's a cleaner split than two NGN sites competing for the same buyers.

## Decision
- [ ] Jerry confirms B, or picks A (and a licence gets written)
- [ ] Commission % set: ___
- [ ] Brother's affiliate link: ___
- [ ] Separate WhatsApp for his audience: yes / no
