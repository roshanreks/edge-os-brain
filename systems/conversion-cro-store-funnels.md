# Conversion, CRO, Store, and Funnels

The store is where attention becomes cash. In EDGE OS, conversion rate is not treated as a design metric only. It is a business metric connected to ad angle, traffic temperature, product trust, offer, speed, proof, checkout, and fulfillment expectation.

## Core Principle

The store should answer the next question in the buyer's mind.

Hot traffic needs clarity and checkout speed. Cold traffic needs education, proof, and a reason to care.

## Benchmarks and Reality

Use benchmarks directionally, never blindly. Conversion rate depends on category, AOV, traffic source, discounting, trust, device mix, and offer.

Useful guardrails:
- Under 1% CVR: usually a serious offer, trust, traffic, speed, or product-message mismatch
- 1-1.5%: usable but leaky for many stores
- 1.5-2.5%: workable for many early/mid brands
- 2.5-4%+: strong for many D2C contexts, depending on AOV and traffic
- Mobile CVR should be tracked separately because most traffic is mobile

Do not chase CVR alone. A higher CVR with bad margins, low AOV, or high RTO can still be a weak business.

## The CRO Hierarchy

Fix in this order:

1. **Traffic match** - Are the right people arriving?
2. **Message match** - Does the page continue the ad promise?
3. **Offer clarity** - Is the deal/value obvious?
4. **Product clarity** - Do they know what it is, who it is for, and why it works?
5. **Proof** - Do they believe it?
6. **Objection handling** - Are doubts answered?
7. **Friction** - Is checkout simple and trustworthy?
8. **Speed** - Does the page load and respond fast on mobile?
9. **AOV** - Can bundles/upsells lift order value without hurting purchase rate?

## High-Converting PDP Structure

Above the fold:
- clear product visual
- one-line promise
- price and offer
- rating/review proof
- delivery/payment trust
- CTA
- variant choice without confusion

Mid page:
- problem and outcome
- product mechanism
- product demo
- ingredient/material/feature explanation
- customer proof
- comparison
- FAQs and objections

Bottom:
- guarantee/returns
- shipping/COD clarity
- reviews
- bundles or related products
- final CTA

## Message Match

Every winning ad angle should have a matching page module.

If the ad sells:
- "pain relief" -> page must explain the pain and relief mechanism
- "premium design" -> page must show product quality and lifestyle
- "before/after" -> page must show proof and conditions
- "founder story" -> page must continue trust and mission
- "celebrity" -> page must show the association and why it matters
- "offer" -> page must make the offer impossible to miss

## Landing Page Types

### PDP
Best for:
- Product Aware
- Most Aware
- warm retargeting
- simple products

### Offer Landing Page
Best for:
- sale/drop campaigns
- bundles
- gifting
- seasonal demand

### Advertorial
Best for:
- Problem Aware
- Solution Aware
- education-heavy products
- categories with skepticism

### Quiz / Guided Selling
Best for:
- multiple SKUs
- skin/hair/fitness/nutrition/personalized categories
- confused buyers

### Comparison Page
Best for:
- Solution Aware traffic
- premium pricing
- competitive categories

### Founder / Story Page
Best for:
- trust-sensitive categories
- founder-led brands
- mission/quality proof

### Hero Landing Page

Best for:
- one hero product or hero bundle
- traffic that already understands the problem
- clear visual categories where the offer can be explained quickly

Structure:
- benefit-driven hero
- product/offer visual
- problem and outcome
- proof
- benefits
- objections/FAQs
- CTA repeated through the page

### Advertorial

Best for:
- colder Problem Aware or Solution Aware traffic
- education-heavy categories
- products with skepticism or a unique mechanism

Structure:
- pain or market insight
- why common solutions fail
- mechanism explanation
- product introduction
- proof
- offer
- risk reversal

### Quiz / Guided Selling

Best for:
- multiple SKUs
- personalization categories
- confused buyers
- high-consideration categories

Structure:
- customer self-identification
- problem/goal questions
- recommended routine/product
- proof
- offer
- email/WhatsApp capture if purchase is delayed

## Funnel by Awareness Stage

| Awareness | Best funnel |
|---|---|
| Unaware | content/ad -> story/education -> product proof -> PDP |
| Problem Aware | problem ad -> advertorial/quiz -> product page |
| Solution Aware | comparison/mechanism ad -> comparison/landing page -> PDP |
| Product Aware | demo/proof ad -> PDP |
| Most Aware | offer/retargeting -> PDP/cart |

## Store Design Rules

Good-looking means commercially clear, not decorative.

The store should feel:
- trustworthy
- fast
- mobile-first
- category-appropriate
- visually consistent
- easy to scan
- clear about price, delivery, and returns

Avoid:
- oversized generic hero sections on product traffic
- hard-to-read fonts
- unclear CTAs
- app bloat
- popups that block buying
- visual style that contradicts price point
- hiding proof below too much brand copy

## Mobile Priorities

Mobile is usually the main battlefield.

Check:
- first screen loads fast
- CTA visible without confusion
- images are compressed
- variant picker is easy
- reviews/proof are visible
- sticky add-to-cart works
- cart drawer is simple
- UPI/COD/payment options are clear
- delivery expectations are visible
- WhatsApp support does not block checkout

## Speed Priorities

Speed improvements often improve both user experience and economics.

Audit:
- image sizes
- unused apps
- theme bloat
- third-party scripts
- video loading
- font loading
- checkout redirects
- mobile Core Web Vitals where available

Do not install a conversion app if it slows the buying path more than it helps.

## CRO Testing Ideas

High-priority tests:
- headline/promise above fold
- product image order
- review placement
- offer format
- bundle structure
- sticky CTA
- comparison section
- FAQ order
- guarantee language
- COD/prepaid incentive
- free shipping threshold
- landing page vs PDP
- advertorial for cold traffic
- creator proof module

## Advanced CRO Testing Rules

Use `systems/testing-and-experimentation.md` for the primary testing process, and `systems/testing-experimentation-system.md` for deeper templates.

Important rules:
- Judge pages by CVR, AOV, RPU/RPS, contribution, and order quality together.
- If a page increases AOV and revenue per user without damaging conversion or RTO, it can be a win even if CVR is flat.
- Use big-swing tests when the existing page is structurally wrong, old, slow, or mismatched to the brand.
- Use incremental tests when the page is mostly healthy and the team needs cleaner attribution.
- Use plus-one/ladder tests when development speed is high and the goal is rapid directional learning.
- Use customer surveys, reviews, heatmaps, and support data before choosing tests. Best-practice tests often fail when they are not tied to customer truth.
- Landing page diversity can help a Meta-heavy account reach different audience pockets, but only if each page has a clear role and tracking.

## The Landing Page Planning Questions

Before building a page, answer:
- What problem is this page solving?
- Who is the exact customer seeing it?
- What is the traffic source and awareness stage?
- What is the angle?
- What proof must appear before the CTA?
- What is the single primary action?
- What happens after purchase?

## Product Page Sales Assets

Treat the PDP image carousel as a sales tool, not a gallery.

Useful assets:
- product in use
- scale/size reference
- texture/material/ingredient close-up
- before/after or outcome visual
- review screenshot
- comparison chart
- how-to-use visual
- bundle/routine visual
- guarantee/return/shipping visual

Every image slot should answer a buyer question or reduce a buyer risk.

## Level-Specific CRO Focus

| Level | CRO focus |
|---|---|
| 1 | clarity, offer, mobile checkout, basic proof |
| 2 | PDP match to winning ads, reviews, bundles, friction fixes |
| 3 | landing pages, advertorials, proof depth, speed, AOV without CVR loss |
| 4 | funnel architecture, persona pages, retention journeys, CRO cadence |
| 5 | personalization, portfolio UX, speed governance, channel-specific funnels |

## Baymard-Backed Store Fixes (install these before clever tests)

Source: Baymard Institute ecommerce CRO research. Global UX, still highly relevant to Indian Shopify stores.

1. **Checkout is the closest money.** ~18% of users abandon from checkout UX (too long / too confusing). Guest checkout. Fewer fields. UPI first. COD as a labelled option, not a novel.
2. **Trust is a gut feel.** Security look, payment encapsulation, delivery promise, return policy. Seals help only if the page already looks safe.
3. **Reviews are not optional.** Up to 95% of testers used ratings. Show **average + count** near the title, not only a wall at the bottom.
4. **Mobile is the store.** Search, variants, ATC, and payment must work with a thumb.
5. **Images sell.** 56% start with images. Zoom, scale, texture, what's-in-the-box, on-body/in-use. Blurry pack shots leak money. Baymard: only ~25% of sites give enough imagery.
6. **Mark required *and* optional fields.** Uncertainty creates validation errors and drop-off.
7. **Don't ambush with chat.** User-initiated WhatsApp/chat helps. Auto popups while they are reading the PDP hurt.
8. **Navigation must be obvious.** Categories visible. Search-within-category should not eject them into site-wide junk.
9. **Shipping and returns in the footer *and* on the PDP.** Some buyers look only in the footer. 11% have abandoned over return policy.
10. **Create accounts after purchase**, and say why it helps them (reorder, tracking), never as a gate.
11. **Hide coupon fields behind a link.** Visible coupon boxes trigger "I must be overpaying" and send people to Google.
12. **Descriptions must answer the real questions:** size, quantity, ingredients, smell, compatibility, what they receive. Two unlabelled dimension tables destroy confidence.
13. **Autocomplete must survive misspellings.** Nearly all testers use it.

Full testing protocol: `systems/testing-and-experimentation.md`.

## Money-Model Surfaces On The Store

The store is not only a PDP. It is the fulfilment of the Hormozi sequence. See `systems/offers-money-models.md`.

| Surface | Job |
|---|---|
| First screen | Dream outcome + product + price + proof + CTA |
| Offer module | Named kit / Buy X Get Y / prepaid perk |
| Decoy table | Starter vs Ritual so the real offer is obvious |
| Guarantee module | If X in Y then Z. Specific, not "quality guaranteed" |
| Cart | Menu upsell: 1 or 2? Add the complement. Hide coupons. |
| Checkout | Guest, UPI, COD, delivery date, returns link |
| Post-purchase page | Classic upsell, then one downsell if they skip |
| Thank-you / WhatsApp | Continuity, education, review, refill |

Do not put four upsell modals on a Level 1 store. One relevant next product is enough.

## CRO Scores To Review Weekly

| Score | Weak | Workable | Strong |
|---|---|---|---|
| Site CVR | < 1% | 1.5–2.5% | 3%+ |
| Mobile CVR | < 1% | 1.2–2% | 2.5%+ |
| ATC rate | < 3% | 4–8% | 8%+ |
| Checkout completion | < 35% | 40–60% | 60%+ |
| Mobile load | > 4s | 2.5–3.5s | < 2.5s |
| Upsell take rate | < 5% on a relevant add | 8–15% | 15%+ without RTO spike |
| Prepaid mix | Falling while spend rises | Stable | Rising with a real perk |

Read CVR with AOV, RTO, and contribution. Always.

## CRO Review Checklist

- Does the page match the ad that sent the traffic?
- Is the product promise visible in 3 seconds?
- Is the product visually understandable?
- Is proof above the fold or close to it?
- Are price, shipping, return, and payment clear?
- Are objections answered before checkout?
- Is the page fast on mobile?
- Is the CTA clear and repeated?
- Are bundles increasing profit or only creating complexity?
- Are CVR, AOV, RTO, and contribution margin reviewed together?
- Is there a designed next offer after the first yes?
- Is the coupon box hidden?
- Can a Tier 2 buyer on Jio 4G finish checkout without confusion?
