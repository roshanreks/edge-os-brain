# Testing and Experimentation System

How EDGE OS tests creative, offers, landing pages, and products without gambling the P&L.

Related:
- `systems/testing-experimentation-system.md` — complementary SOP file (keep both)
- `systems/creative-engine.md`
- `systems/conversion-cro-store-funnels.md`
- `systems/offers-money-models.md`
- `systems/product-development.md`
- `systems/scaling.md`
- `systems/growth-scorecards.md`
- `wiki/research-benchmarks-2026.md`

## Core Principle

Testing is not "try random things."

Testing is a production system that:
1. States a hypothesis
2. Isolates one variable
3. Gives it enough traffic or spend to speak
4. Kills, iterates, or scales with a rule
5. Writes the learning back into the brain

Two different games get mixed up. Keep them separate.

| Game | What you are testing | Decision tool |
|---|---|---|
| **Creative / media** | Concepts, hooks, awareness stages | Spend gates + leading indicators, then purchases |
| **Store / CRO** | Page, offer, checkout | Sample size + confidence, then contribution |
| **Product / offer** | SKU, kit, price, guarantee | Stage gates + customer quality, not vanity CVR |

Common Thread Collective's research (2026) is the creative math we use: outliers follow a power law. You cannot pick the winner in a Figma file. You can only build a machine that finds it.

## The Scores

### Creative scores (Meta / paid social)

Use these as **directional**. Category, hook style, and placement move the numbers.

| Score | What it means | Weak | Workable | Strong signal |
|---|---|---|---|---|
| 3-sec view / thumbstop | Hook earned a look | < 15% | 20–30% | 30%+ or comments that restate the problem |
| Hold / thru-play quality | Message was followed | Drops immediately after hook | Mid-roll hold | People watch the product demo |
| Outbound CTR | Wanted the next step | < 0.6% | 0.8–1.5% | 1.5–3%+ with relevant landing |
| CPC | Attention cost | Rising with no CTR lift | Stable | Falling while CTR holds |
| ATC rate from click | Page/offer interest | Clicks, no ATC | Some ATC | ATC without discount desperation |
| Landing CVR | Message match + offer | < 0.8% on relevant traffic | 1.2–2% | 2.5%+ |
| CPA vs break-even | Can we buy this customer? | Above break-even after spend gate | Near target | Below target with decent order quality |
| Frequency | Fatigue | 3+ and falling CTR | 1.5–2.5 | Fresh enough that winners still spend |

**CTC math to remember (global ecommerce panel, not India-only):**
- Top ~3.5% of ads generate ~66% of spend
- ~79% of ads never reach meaningful spend (their $1,000 mark) before being killed
- ~21% "activate"
- Fast outliers can show in ~18 days; median ~39; slow ~81
- Activation often happens in the first $500–$1,000 of spend

India translation of the spend gate (directional, scale with AOV and Level):

| Level | Spend per concept before kill | What "activate" looks like |
|---|---|---|
| 1 | ₹500–2,000 | CTR + ATC or a handful of purchases |
| 2 | ₹1,500–5,000 | CPA near target or strong ATC + checkout |
| 3 | ₹4,000–10,000 | New-customer CPA inside band |
| 4–5 | ₹8,000–20,000+ | Can absorb budget without efficiency collapse |

Do not use US $1,000 gates on a Level 1 brand. Do not use ₹800 gates on a Level 4 brand.

### Store / CRO scores

| Score | Weak | Workable | Strong |
|---|---|---|---|
| Site CVR | < 1% | 1.5–2.5% | 3%+ (category/AOV dependent) |
| Mobile CVR | < 0.8–1.0% | 1.2–2.0% | 2.5%+ |
| ATC rate | < 3% | 4–8% | 8%+ |
| Checkout completion | < 35% | 40–60% | 60%+ |
| Cart abandonment | 75%+ | ~70% (Baymard global bench) | Materially better after recovery |
| Page load (mobile) | > 4s | 2.5–3.5s | < 2.5s |
| Offer take rate | Nobody sees the offer | Offer is visible | Offer chosen without wrecking margin |

Littledata Shopify bench in this brain: ~1.4% average, 3.2%+ top 20%, 4.7%+ top 10%, mobile ~1.2%. See `wiki/research-benchmarks-2026.md`.

### Offer / money-model scores

See the full scorecard in `systems/offers-money-models.md`.

Minimum weekly:
- Upsell take rate
- Downsell recovery
- Continuity attach
- Prepaid mix
- Contribution after gifts and RTO
- CAC payback

### Product scores

| Score | Meaning |
|---|---|
| Repeat 30/60/90 | Truth serum for PMF |
| Refund / complaint rate | Product truth |
| Review quality (not only stars) | Language for copy |
| Contribution by SKU | What to stock |
| Support tickets per 100 orders | Hidden product tax |

## Testing Rules That Do Not Change

1. **One variable.** New hook *or* new offer *or* new first screen. Not all three.
2. **Hypothesis first.** "If we put UPI + delivery date above the fold, mobile checkout completion rises because trust anxiety drops."
3. **Traffic quality first.** Do not CRO a page that is being fed the wrong audience.
4. **Message match.** Ad promise and first screen must be the same conversation.
5. **Contribution over CVR.** A test that lifts CVR and RTO is a failed test.
6. **Write it down.** Winning and losing tests go into the creative library / wiki.

## Creative Testing Operating System

### Volume vs concepts
A concept is a different idea (problem, mechanism, proof, offer, identity). A color swap is a variant, not a concept.

CTC: most monthly volume should be systematic variants of proven frameworks (~70%), with a minority as true new concepts (~30%) once a brand has winners.

### Kill / iterate / scale

**Kill** if after the spend gate:
- No hook retention
- Clicks but no PDP engagement
- Purchases happen but CPA stays above break-even
- Comments show misunderstanding
- Order quality is junk (RTO, one-star, wrong customer)

**Iterate** if:
- Hook works, body dies
- CTR good, CVR weak → page/offer/message match
- ATC high, checkout weak → trust, shipping, payment, COD
- Comments show demand + a repeated objection

**Scale** if:
- New-customer CPA inside target
- Contribution acceptable
- Inventory and fulfillment can take the volume
- Feedback is not a support fire

### Account structure (practical)
- Testing campaign ≠ scaling campaign
- Do not starve tomorrow's winners to feed today's one ad
- 10–20%+ of media in pure testing at most levels; higher at L1–L2
- Name ads: `L{level}_{awareness}_{angle}_{offer}_{format}_{date}`

## CRO / Landing Page Testing

Baymard and Shopify agree on the unglamorous truth: most conversion is lost to confusion, missing proof, checkout friction, and mobile pain — not to button color.

### What to test first (in order)
1. Traffic match and first-screen message match
2. Offer / price / shipping / prepaid clarity
3. Product images + zoom + demo
4. Reviews above or near the fold (count + average)
5. Checkout length, guest checkout, UPI/COD
6. Hide coupon field behind a link
7. Speed
8. Then: hero order, FAQ order, bundle widgets

### Statistical common sense
- Shopify's 2026 guidance: act when you have enough sample and typically ~95% confidence, not on day-two vibes.
- Bayesian tools (VWO, Optimizely) can call tests faster; still do not stop on 40 sessions.
- Level 1–2 often lack the traffic for clean A/B. Use sequential fixes on obvious leaks (Baymard: 18% abandon from checkout UX issues; 56% inspect images immediately; 95% use reviews).
- Level 3+ : proper A/B on high-traffic PDPs and landing pages.
- Never test two tiny things while the page is slow and the offer is unclear.

### Landing page test matrix

| Traffic | Control | Variant to try |
|---|---|---|
| Product / Most Aware | PDP | Tighter ATF + offer + sticky ATC |
| Solution Aware | PDP | Comparison / mechanism page |
| Problem Aware | PDP | Advertorial or quiz |
| Offer ads | Generic collection | Dedicated offer LP |
| Creator/celebrity | Generic PDP | Association module above fold |

## Product and Offer Tests

Use stage gates, not vibes:

1. **Hypothesis + audience + dream outcome**
2. **Cheap proof:** conversations, reviews of competitors, waitlist, small creative test
3. **Spend gate** with a target CPA / ATC
4. **Fulfill 50–100 orders** and read refunds + WhatsApp
5. **Repeat signal** before inventory commitment
6. Kill or install into the money model

Cap new-product testing as a % of revenue (see Level playbooks, typically 5–10%).

## Level Map

| Level | Creative tests | CRO tests | Offer tests |
|---|---|---|---|
| 1 | 8–20 concepts, low-effort, founder | Fix obvious leaks, no tiny A/B | One attraction offer |
| 2 | 20–50, weekly batches | PDP vs winning ad, bundles | Menu upsell + trial downsell |
| 3 | 50–120, scorecard | Advertorial vs PDP, speed | Full attraction/upsell/continuity |
| 4 | 100–250+, dedicated pod | Persona LPs, holdouts | Offer-level P&L |
| 5 | 200–500+, newsroom | Personalization, channel funnels | Portfolio models, incrementality |

## Weekly Testing Meeting (45 min)

1. What did we launch?
2. What activated / died / is still learning?
3. What did comments and CX say?
4. Which page leak is now obvious?
5. What is next week's one CRO test and one offer test?
6. What do we stop?

## Sources

- CTC, *The Ecommerce Creative Testing Framework* (2026): https://commonthreadco.com/blogs/coachs-corner/the-ecommerce-creative-testing-framework-from-gambling-to-math
- CTC YouTube: Hierarchy of Metrics, Meta 2026 measurement, creative volume
- Shopify A/B testing (2026): https://www.shopify.com/blog/ab-testing
- Baymard ecommerce CRO: https://baymard.com/learn/ecommerce-cro
- Littledata / Baymard benches in `wiki/research-benchmarks-2026.md`
