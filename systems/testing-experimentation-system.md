# Testing and Experimentation System

Use this as the deep companion playbook. For the primary EDGE OS testing operating system, load `systems/testing-and-experimentation.md` first, then return here for expanded test types, templates, and implementation detail.

Testing is how EDGE OS turns opinions into learning. The goal is not to run tests for decoration. The goal is to make better decisions about product, offer, creative, landing pages, checkout, retention, and capital allocation.

This system combines CRO testing, creative testing, offer testing, product testing, and launch/post-mortem discipline.

## Core Principle

Do not ask, "What best practice should we copy?"

Ask:
- What is the bottleneck?
- What is the hypothesis?
- What signal would prove we are right?
- How much traffic, spend, or time do we need?
- What will we do if it wins, loses, or is inconclusive?

## The EDGE Test Hierarchy

Test in this order unless a known emergency exists:

1. **Measurement** - Can we trust the data?
2. **Offer/product clarity** - Does the customer understand and want it?
3. **Creative angle** - Are we attracting the right demand?
4. **Landing page/PDP match** - Does the page continue the ad promise?
5. **Proof and objections** - Does the buyer believe it and feel safe?
6. **Checkout/payment/friction** - Can they buy easily?
7. **AOV and LTV lifts** - Can we increase cash collected without hurting conversion?
8. **Retention** - Can we make the second order easier?
9. **Distribution expansion** - Can the engine work on more channels?

## Test Types

### 1. Research Test

Used when you do not know what to test yet.

Inputs:
- customer surveys
- post-purchase surveys
- heatmaps
- session recordings
- reviews
- support tickets
- ad comments
- creator comments
- competitor reviews

Output:
- ranked list of hypotheses
- customer language
- objection map
- proof gaps

Best for: Levels 1-5, especially before redesigns.

### 2. Smoke Test

Used to test interest before building fully.

Examples:
- static ad for new angle
- waitlist landing page
- preorder page
- fake-door "coming soon" module
- survey with product concept
- creator seeding before inventory purchase

Best for: Level 1-3 product and offer validation.

### 3. Creative Market Test

Used to see if an angle can attract quality traffic.

Signals:
- thumbstop/hook rate
- CTR
- CPC
- add-to-cart
- CAC/CPA
- comment quality
- RTO/order quality
- repeat quality later

Best for: all levels.

### 4. CRO A/B Test

Used when traffic is high enough to isolate a variable.

Rules:
- define primary metric before launch
- calculate sample size or minimum detectable effect
- run across a representative business cycle
- avoid stopping early because the result looks exciting
- read CVR with AOV, RPU, contribution, and order quality

Best for: Level 3-5, and Level 2 when traffic is enough.

### 5. Big-Swing Test

Used when the current experience is structurally wrong or old.

Examples:
- full PDP rebuild
- theme redesign
- new landing page type
- new bundle collection flow
- new checkout/cart architecture

Rules:
- port over proven learnings from past tests
- avoid changing multiple things aimed at the same KPI if you need clean attribution
- after a big win, decompose by removing or isolating sections to learn what drove the lift
- judge on RPU/contribution, not CVR alone

Best for: Level 3-5 when incremental tests are too slow or the page no longer fits the brand.

### 6. Plus-One / Ladder Test

Used when you want speed and directional learning.

Example:
- V0: current page
- V1: new above-fold
- V2: V1 + proof module
- V3: V2 + bundle module
- V4: V3 + review/FAQ improvement

Use when:
- development cost is low
- traffic is enough for directional reads
- the team needs to discover combinations fast
- strict scientific isolation is less important than learning velocity

Best for: Level 4-5 teams with higher traffic and faster dev/design.

## CRO Metrics

Do not judge CRO by conversion rate alone.

Track:
- CVR
- AOV
- revenue per user/session (RPU/RPS)
- add-to-cart rate
- checkout start rate
- checkout completion rate
- contribution margin
- new vs returning customer split
- RTO/cancellation rate
- support burden
- repeat rate by cohort

If CVR is flat but AOV and RPU rise without hurting order quality, the test can still be a win.

## Creative Testing Rules

Creative testing is usually not classic A/B testing. Platform algorithms allocate impressions unevenly and the creative itself affects who sees it.

Use:
- conceptually distinct angles
- clear naming conventions
- enough spend to see activation
- kill rules based on spend and signal, not personal taste
- a distinction between variants and new concepts

Concept variables:
- persona
- pain/desire
- awareness stage
- hook
- proof type
- demo
- offer
- format
- creator type
- landing destination

## Static Ads as Cheap Tests

Static ads are useful because they let the team test an angle quickly before turning it into video, creator briefs, PDP modules, or landing pages.

Use statics to test:
- headline
- visual metaphor
- product claim
- review angle
- before/after
- comparison
- offer stack
- objection
- meme/relatability
- founder POV

If a static wins, convert it into:
- UGC script
- founder video
- PDP section
- email
- landing page hero
- creator brief

## Landing Page Testing

Landing pages can be tested for both conversion and platform learning.

In Meta-heavy accounts, multiple landing pages may function as diversity for the algorithm, not just as a clean A/B test. This means:
- one page can speak to one customer segment
- another can explain the mechanism
- another can sell a bundle
- another can use founder/creator proof

Do not run 12 pages if you cannot learn from them. But do not force one generic PDP to serve every awareness stage.

## Valid A/B Testing Discipline

For higher-confidence tests:
- calculate sample size before launch
- define primary and secondary metrics
- define minimum detectable effect
- run long enough to include weekdays/weekends and normal traffic mix
- avoid peeking and stopping early
- segment after the test, but do not cherry-pick segments to declare victory
- document the test even when it loses

If the brand has low traffic, use directional tests, smoke tests, surveys, or creative tests instead of pretending the A/B result is statistically clean.

## Product Testing Stage Gates

Before a full product launch, run stage gates:

1. **Customer pain proof** - reviews, comments, surveys, search, competitor complaints
2. **Concept proof** - mockup/static/waitlist/preorder
3. **Unit economics proof** - margin, shipping, COD/RTO risk, replenishment
4. **Creative proof** - ads can generate interest
5. **Landing proof** - page can explain and convert
6. **Operational proof** - supplier, inventory, fulfillment, support
7. **Retention proof** - reason to buy again, cross-sell, or refer

## Weekly Testing Rhythm

### Level 1
- 1 weekly founder/customer learning review
- 2-5 creative/offer tests
- 1 store friction fix
- no heavy statistical tests

### Level 2
- weekly creative batch
- weekly CRO/offer review
- monthly customer survey/review mining
- simple landing page or PDP tests

### Level 3
- weekly creative review
- biweekly CRO sprint
- monthly product/offer stage-gate review
- RTO/order-quality read on test traffic

### Level 4
- creative pod weekly review
- CRO roadmap with big-swing and incremental tests
- monthly product launch/post-mortem meeting
- ongoing survey/heatmap/review synthesis

### Level 5
- full experimentation council across growth, product, creative, CRO, lifecycle, ops, finance
- portfolio test budget
- incrementality and blended measurement where possible
- formal knowledge base of wins, losses, and hypotheses

## Experiment Brief Template

- Name:
- Level:
- Department:
- Bottleneck:
- Hypothesis:
- Customer insight:
- Awareness stage:
- Test type:
- Variant(s):
- Primary metric:
- Secondary metrics:
- Quality guardrails:
- Required sample/spend/time:
- Owner:
- Launch date:
- Kill rule:
- Scale rule:
- Follow-up if win:
- Follow-up if loss:

## Experiment Post-Mortem Template

- What did we test?
- Why did we test it?
- What happened?
- Did CVR, AOV, RPU, contribution, and order quality move together or conflict?
- What customer insight did we learn?
- What should be scaled, repeated, killed, or decomposed?
- Which system file should this update?

## Common Mistakes

- testing best practices without customer research
- running low-traffic A/B tests and pretending they are conclusive
- judging landing pages only by CVR while ignoring AOV and RPU
- changing five variables and calling one element the winner
- killing creative before it has a real spend signal
- letting platform spend allocation decide the truth without human review
- launching products without unit economics and fulfillment stage gates
- not documenting losses
