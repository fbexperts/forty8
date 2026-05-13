# forty8 Landing Page — Copy (v1)

**Status:** v1 draft, 2026-05-13. Pending Shuki review.
**Source of truth:** `BRIEF.md` (positioning) + `research/ecom-icp.md` (language).
**Voice:** confident, founder-to-founder, specific, no marketing-team-by-committee tone. Reference vibe = Tinybird/Granola/Reforge — quietly senior, not salesy.

---

## NOTES FOR THE BUILD (read before scaffolding Astro)

1. **Form backend:** the $0 front-end form is NOT a Lemon Squeezy checkout — it's a regular form (Formspree / Netlify forms / custom webhook to your DB + Lemon Squeezy customer create). Lemon Squeezy enters the flow at OTO1.
2. **Page flow:**
   - `/` → LP (this doc)
   - `/thanks` → OTO1 page (upgrade to 50 for $9.99) — Lemon Squeezy embed, hot-buyer state
   - `/thanks/oto2` → OTO2 page (full brief + 3 videos for +$9.99)
   - `/thanks/oto3` → OTO3 page (founder audit for +$97)
   - Email at T+0: "We're building your 10 creatives. Delivery in 48h."
   - Email at T+48h: delivery + retainer pitch
3. **Founder proof section needs your input** — I've left placeholders for the specific numbers and credentials. Fill in before launch.
4. **Compliance:** "no card to start" claim must be true through OTO1 completion. The user only enters card info once they choose to upgrade. Otherwise this becomes the same trap forty8 is positioning against (AdCreative.ai trial-to-charge complaints).

---

## SECTION 1 — HERO

> **Eyebrow** (small, above headline):
> `For DTC founders running $50K–$500K/mo on Meta`

> **H1 (the headline):**
> # 10 ad creatives, built for your store. In 48 hours. Free.

> **Subhead:**
> Senior-buyer judgment at AI-tool volume. No templating engines. No agencies. No card to start.

> **Primary CTA button:**
> `Get my 10 creatives →`

> **Micro-copy under the button:**
> Most orders ship in under 24 hours. Full refund if we miss 48.

**Design notes for this section:**
- One screen above the fold on desktop AND mobile.
- No hero image of a smiling stock-photo person. Either: (a) no image, all-typography, or (b) a tight grid of 6–9 real anonymized forty8 outputs as the background or right column. Option (b) is stronger — proof is in the work.
- Form is anchor-linked from CTA (`#claim`), not opened in modal. Same-page scroll respects mobile.

---

## SECTION 2 — THE PAIN (validate they're in the right place)

> ## Meta's rent keeps going up. Your creative pipe can't keep up.

> Your last winner died in 6 days, not 6 weeks. Background swaps and headline tweaks don't count anymore — Andromeda clusters them as one ad. The math shifted from *"do I need 20 ads this month or 60?"* to *"can I ship 50 real variations a week without burning a team or paying $5K to an agency that ships 6?"*

> You can't out-target the algorithm. You can out-supply it.

> **forty8 is the supply.**

**Design notes:**
- The Nest quote ("You can't out-target the algorithm. You can out-supply it.") gets pulled out as a blockquote or callout — visually distinct.
- Final line ("forty8 is the supply.") is its own line, larger, bold. Acts as a section transition.

---

## SECTION 3 — WHAT YOU ACTUALLY GET

> ## What's in the 10 free creatives.

> Real ad creatives. Not template fills, not AI slop, not stock-photo collages.

- **10 fully-rendered ad creatives** — 4:5 portrait, the only format Meta is actually rewarding in 2026.
- **Built around YOUR product, YOUR audience, YOUR positioning** — you give us a store URL and 3 short answers. We do the rest.
- **Hook + topic + mechanic + CTA on every frame** — the senior-buyer checklist, not "make it pop."
- **A range of angles** — no cosmetic variations dressed up as 10 ads. Andromeda will cluster those. We don't.
- **Delivered as PNGs, ready to upload to Ads Manager.**
- **48 hours, guaranteed.** Most orders ship in under 24.

> Free means free. No card. No surprise charge on day 4. No upgrade timer counting down on your dashboard.

**Design notes:**
- Six-bullet list as a 2-column grid on desktop, single column on mobile.
- "Free means free" line is callout-styled — small but bold, in a tinted box. Directly counter-positions vs the AI-tool trial-to-charge complaints in the research.

---

## SECTION 4 — WHY THIS ISN'T AI SLOP

> ## Why this isn't another AI-creative tool.

> Most $9–$300/mo AI tools generate something visible-from-orbit-fake. Real reviews of the category leader: *"templates from the 1990s"* and *"truly bizarre and way inferior to what's available."* The next-tier tool (AI actors) breaks on physical products — it admits it handles ~20% of an ad if you sell something physical instead of digital.

> forty8 uses AI for the heavy lifting. But every creative passes a senior Meta buyer's eye before it ships.

> That's the difference between **50 templated outputs** and **50 ads someone would actually run.**

**Comparison table:**

|  | AI tools | Agencies | forty8 |
|---|---|---|---|
| **Output speed** | Minutes | 1–4 weeks | 48 hours |
| **Quality control** | Templating engine | Varies by who's on shift | Senior-buyer reviewed |
| **Physical-product DTC** | Documented blind spot | Often fine | Native |
| **Entry cost** | $189–$399/mo | $1K–$10K+/mo + setup | $0, no card |
| **Risk** | Trial-to-charge traps | 3-month contracts | Refund if we miss 48h |
| **Cadence** | On-demand, single seat | Once/month, slow rounds | Weekly retainer option |

**Design notes:**
- Don't name competitors by name in the table (forty8 vs "AI tools" not "forty8 vs AdCreative.ai"). Naming competitors invites legal noise. Direct quotes from their reviews in body copy are fair game.
- Comparison table on mobile collapses to a vertical "forty8 vs X" carousel or stacked cards.

---

## SECTION 5 — FOUNDER PROOF (placeholder — needs Shuki input)

> ## Who's behind forty8.

> forty8 is built by Shuki Mann — a senior Meta buyer who's spent the last **[X]** years running paid social for DTC ecom and social casino brands.

[**PLACEHOLDER bullet list — Shuki, fill in real specifics you're comfortable making public:**]

- Personally managed **$[X]M+** in Meta ad spend across **[N]** DTC + social casino brands
- Built internal creative + optimization tooling (the same pipeline forty8 runs on) — now also used by **[N]** performance teams to ship creatives at scale
- **[Optional: one specific anonymized result]** — e.g. *"Took a $2M/mo skincare brand from $42 CPA to $28 CPA over 6 weeks using the creative cadence forty8 productizes"*

> forty8 isn't a side project. It's the productized version of what I do for clients every week. The 10 free creatives are the same quality work the brands above are getting — not a watered-down teaser. If we're not the right fit for your business, take them anyway.

> — Shuki

**Design notes:**
- A real photo of Shuki next to the section, or a hand-drawn signature underneath. NOT a stock photo, NOT a corporate headshot.
- The blurred-dashboard screenshot belongs in this section, captioned: *"Real client account. Brand name removed for confidentiality. Numbers are not."*
- This section establishes credibility WITHOUT fake testimonials. It rests entirely on founder track record + the visible quality of the 10 creatives the buyer is about to receive.

---

## SECTION 6 — THE OTO LADDER, TRANSPARENTLY

> ## After your 10 free creatives, here's what's available.

> No hidden upsells. After you receive your 10, the next options are stated upfront. Take the free ones first. Decide on the rest after you've seen the work.

| Add-on | Price | What you get |
|---|---|---|
| **Upgrade to 50 creatives** | +$9.99 once | 5× the volume of your free tier. Same 48 hours. |
| **Full creative brief + 3 video scripts** | +$9.99 once | The strategic doc that drives the creatives — audience pains, angles, hook architecture — plus 3 ready-to-shoot UGC scripts. |
| **Founder Account Audit** | +$97 once | I personally log into your Meta account, record a 15-min Loom: which of the 50 to launch first, the test structure, and 3 things broken upstream that will kill these. |
| **Weekly Winner Iterator** | $297/mo | Every Monday: 10–15 fresh iterations of last week's top performers + my Loom on what's working and what to kill. Cancel anytime. |

> Take the 10 free creatives first. The upsells are listed here so you can see them coming — not so you have to decide now.

**Design notes:**
- This section is unusual. Most LPs hide the upsell flow. We surface it because the research showed founders are explicitly looking for *"$100–$200 for 5–10 creatives, then form a relationship if good"* buying patterns. Honesty about the funnel matches how they want to buy.
- "Cancel anytime" on the retainer needs to be true and visible.

---

## SECTION 7 — FAQ

> ## Honest answers to the questions you should be asking.

**Q: What's the catch with $0?**
> No catch. You enter your details, we ship 10 creatives in 48 hours. After delivery you'll see optional upgrades. You're never charged unless you choose one.

**Q: Is this AI-generated slop dressed up as a real service?**
> AI is used the same way an agency uses Photoshop — as a tool, not the deliverable. A senior Meta buyer (me) reviews every creative before it goes out. If it's not work I'd run on my own accounts, it doesn't ship.

**Q: My niche is [supplements / apparel / skincare / pet / other physical product]. Does this work?**
> Yes, physical products are the home turf. Most AI creative tools choke on physical goods (they're trained on digital products). forty8 is built for DTC ecom specifically.

**Q: What format do I get?**
> Static creatives delivered as 4:5 portrait PNGs, ready to upload to Ads Manager. (Why 4:5: it's the only Meta format that gets full reach in 2026.) Video scripts come as PDFs in the OTO2 tier.

**Q: How is this different from Fiverr?**
> Fiverr is fine for one-off angle tests at $50/video. forty8 is the production layer for the 10-50/week cadence Meta now requires. Different problem.

**Q: I'm already with an agency. Why try this?**
> Most agencies ship 4–8 creatives per month. The math doesn't work in 2026. Run forty8 in parallel with your agency for a month — see whose 10 creatives convert better. The free tier exists for exactly this comparison.

**Q: What happens to my store data and product info?**
> Used only to produce your creatives. Not sold, not shared with anyone, not used to train external AI models. Standard NDA available on request before delivery.

**Q: What if you miss the 48-hour delivery?**
> Full refund. No questions. The 48 hours is the contract — that's why we put it in the brand name.

**Q: Is this just for big brands?**
> No. The free tier exists so brands of any size can test the work. Most paying customers are doing $50K–$500K/mo on Meta, but the free 10 are useful at any spend.

**Design notes:**
- FAQ uses accordion / expand-on-click pattern. All collapsed by default. Don't bury content but don't dump a wall of text either.
- Order matters — start with the "$0 catch" question because it's the #1 objection on cold traffic.

---

## SECTION 8 — FINAL CTA + INTAKE FORM

> ## Get your 10 ad creatives. Free. In 48 hours.

> No card. No spam. No upgrade timer. Just 10 real creatives in your inbox.

**Form fields (anchor: `#claim`):**

| Field | Type | Required | Notes |
|---|---|---|---|
| First name | text | yes | |
| Email | email | yes | |
| Store URL | url | yes | We pull product images, hero copy, reviews from here |
| What's your hero product? | text (1 line) | yes | Free text — e.g. "premium dog supplements" |
| Current monthly Meta spend | dropdown | yes | < $5K / $5–$50K / $50–$500K / $500K+ |
| One angle you've tried that DIDN'T work (optional) | text (1 line) | no | Helps us avoid repeating it |

**Submit button:**
> `Send me my 10 creatives →`

**Below submit, micro-copy:**
> Delivered in 48 hours. Often under 24. Refund-backed if we miss. Built by a senior Meta buyer, not a templating engine.

---

## FOOTER

Minimal. No corporate links. No social proof scaffolding.

- forty8.com (or whatever the domain is — TBD)
- Built by [Shuki Mann](mailto:shuki@lixfix.com)
- Terms · Privacy · Refund policy (these need real pages)
- One line: *"Independently operated. Not affiliated with Meta. No relationship to any agency or AI-tool brand mentioned."*

---

## OVERALL DESIGN VIBE (for when we scaffold)

- Single column on mobile, max-width 720px on desktop for body sections (NOT full-bleed marketing-page width — readable line length).
- Typography: sans-serif, sharp. Default Tailwind `font-sans` (Inter or system stack) is fine. Don't pick a personality typeface — let the copy carry.
- Color: dark mode by default. Background `#0a0a0a` or similar near-black. Foreground `#fafafa`. One accent color, used sparingly — suggest a warm orange (`#ff6b35` or similar) for CTAs and "forty8" wordmark only. The dark/orange combo signals "indie tech, not corporate."
- No gradients. No glow effects. No floating screenshots. The hero is the work, not the chrome.
- Headings: H1 ~64px desktop / 40px mobile. H2 ~40px / 28px. Body ~18px / 16px.
- All sections separated by generous vertical whitespace (`py-24` on desktop, `py-16` mobile).

---

## WHAT'S MISSING / NEEDS YOUR CALL

1. **Founder proof specifics** (Section 5) — fill in years, spend handled, brands count, anonymized result.
2. **Photo of you** — real headshot or signature. Stock photo is a non-starter per the no-fabrication rule.
3. **Anonymized dashboard screenshots** — for hero background and Section 5. Decide what's safe to share.
4. **Hero option (a) vs (b)** — all-typography hero, or grid-of-real-outputs hero. I lean (b) but you decide.
5. **Domain name confirmed?** — forty8.com / forty8.io / getforty8.com / something else.
6. **Sample creatives gallery** — there's no explicit "gallery of forty8 outputs" section in this draft. Do we want one? Argument for: shows the work directly. Argument against: adds scroll length, and the free 10 IS the gallery for the buyer. I left it out. Push back if you disagree.
