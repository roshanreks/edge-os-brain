# Research Benchmarks 2026

This file stores directional outside benchmarks for EDGE OS. These numbers should inform diagnosis, not replace brand-specific unit economics.

Last reviewed: 2026-08-16

## India E-Commerce and D2C Market

### Bain and Flipkart: How India Shops Online 2026

Source: https://www.bain.com/insights/how-india-shops-online-2026/

Useful points:
- India e-retail market more than doubled over the previous five years.
- Online shoppers reached roughly 290-300 million.
- Gen Z accounts for about 40-45% of e-retail shoppers.
- Tier 2+ cities contributed roughly half of incremental e-retail orders in 2025.

EDGE OS implication:
- Do not design only for metro-first buyers.
- Gen Z and Tier 2/3 growth increase the importance of mobile-first creative, trust, local context, COD/RTO management, and creator-led distribution.

### McKinsey: Indian MSMEs and the D2C Revolution

Source: https://www.mckinsey.com/industries/logistics/our-insights/the-great-unbundling-of-indian-e-commerce-msmes-and-the-direct-to-consumer-revolution

Useful points:
- India's D2C channel is expected to grow materially by 2030.
- McKinsey frames D2C and MSMEs as a major part of India's next e-commerce growth wave.

EDGE OS implication:
- Direct brand-owned channels matter, but marketplaces and quick commerce may also become important distribution surfaces as brands scale.

## Conversion and Store

### Littledata: Shopify Conversion Rate Benchmark

Source: https://www.littledata.io/ecommerce-conversion-rate

Useful points:
- Average Shopify conversion rate benchmark: about 1.4%.
- Top 20% benchmark: above 3.2%.
- Top 10% benchmark: above 4.7%.
- Mobile average benchmark: about 1.2%.

EDGE OS implication:
- A 1-2% CVR may be normal but still leaky.
- Mobile CVR deserves its own review.
- CVR should be read with AOV, margin, traffic source, and RTO.

### Baymard: Cart Abandonment

Source: https://baymard.com/lists/cart-abandonment-rate

Useful points:
- Baymard's documented average cart abandonment benchmark is around 70%.

EDGE OS implication:
- Checkout friction, trust, shipping clarity, payment options, and cart recovery flows can have high leverage.
- Cart abandonment should be segmented by device, traffic source, product, and payment mode.

### Deloitte and Google/Web.dev: Mobile Speed

Source: https://web.dev/case-studies/milliseconds-make-millions

Useful points:
- A 0.1 second improvement in mobile speed was associated with retail conversion rate lift and AOV lift in the cited study.

EDGE OS implication:
- Speed is conversion infrastructure.
- At Level 3+, app bloat and heavy pages should be audited before adding more CRO tools.

## Creative Testing and Paid Media

### Common Thread Collective: E-Commerce Creative Testing

Source: https://commonthreadco.com/blogs/coachs-corner/the-ecommerce-creative-testing-framework-from-gambling-to-math

Useful points:
- Activation testing often needs enough spend per creative to see signal.
- CTC emphasizes that brands often test too few ads to reliably find outliers.
- Directional output benchmarks from the article include higher monthly ad counts as brands scale.

EDGE OS implication:
- Creative volume is not optional at scale.
- Level 3-5 brands need a real creative operating system, not occasional shoots.

### Common Thread Collective: Meta Andromeda and Creative Strategy 2026

Source: https://commonthreadco.com/blogs/coachs-corner/meta-andromeda-roas-creative-strategy-2026

Useful points:
- Creative diversity and output are increasingly important for Meta performance.
- The article gives spend-linked creative output ranges such as 8-12 new creatives/month under $10K/month, 15-25 for $10K-$50K/month, and 25-40+ for $50K+/month.

EDGE OS implication:
- Testing volume must rise with spend.
- Swapping small visual details is not the same as testing distinct concepts, hooks, personas, and awareness stages.

### Shopify: Marketing Efficiency Ratio

Source: https://www.shopify.com/blog/marketing-efficiency-ratio

Useful point:
- MER = total revenue / total marketing spend.

EDGE OS implication:
- MER helps founders avoid over-trusting platform ROAS.
- Use MER alongside contribution margin, new customer revenue, repeat revenue, and cash flow.

## Retention and Lifecycle

### Klaviyo: 2026 Email Marketing Benchmarks

Source: https://www.klaviyo.com/products/email-marketing/benchmarks

Useful points:
- Automated flows generated nearly 41% of email revenue from about 5.3% of sends in the benchmark.
- Flow-based email can be much more revenue-efficient than campaigns.

EDGE OS implication:
- Retention flows are not optional after Level 2.
- Welcome, abandoned cart, post-purchase, replenishment, cross-sell, winback, and review flows should be installed progressively.

## Fulfillment, COD, and RTO

### GoKwik: Return to Origin in E-Commerce

Source: https://www.gokwik.co/blog/what-is-return-to-origin-rto-in-ecommerce

Useful points:
- GoKwik reports Indian e-commerce average RTO around 20-25%, with some cases going near 40% depending on category, geography, and other factors.

EDGE OS implication:
- RTO is a growth and cash-flow lever.
- Diagnose by payment mode, pincode, courier, SKU, offer, and traffic source.

### GoKwik: How to Reduce RTO

Source: https://www.gokwik.co/blog/how-to-reduce-rto-in-e-commerce

Useful points:
- RTO reduction requires looking at the full order journey, including pre-dispatch signals and NDR handling.

EDGE OS implication:
- COD verification, address validation, prepaid incentives, delivery expectation clarity, and NDR follow-up should be treated as systems.

## Platform Creative Notes

### TikTok for Business: Ad Format and Quality

Source: https://ads.tiktok.com/resources/help/article/tiktok-ads-policy-ad-format-and-functionality

Useful points:
- TikTok ad policies emphasize consistency between ad and landing page, legibility, high resolution, standard video sizes including 9:16, audio quality, and dynamic content.

EDGE OS implication:
- Native platform creative matters.
- Ad-message-to-landing-page consistency is both a policy and conversion issue.

## How To Use This File

- Treat these as outside reference points.
- Update this file when a better source appears.
- Do not blindly apply global benchmarks to Indian D2C without category, AOV, COD/RTO, and traffic context.
- When a benchmark changes an operating recommendation, update the relevant file in `/levels/` or `/systems/`.
