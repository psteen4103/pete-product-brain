# Sustainability Attitudes Survey: Customer Preferences & Willingness to Pay

**Prepared by:** Jordan Chen, UX Research & Market Insights  
**Date:** January 15, 2026  
**Sources:** Online survey (n=3,247), focus groups (n=32 across 4 sessions)

---

## Executive Summary

Sustainability is a significant purchase driver for 67% of Contoso customers, but current eco-features are poorly surfaced. Customers demonstrate willingness to pay 8-15% premiums for verified sustainable products. This research supports expanding our eco-certified assortment and informs the [Loyalty Program v2](/specs/loyalty-program-v2.md) sustainability perks.

## Survey Methodology

- **Distribution:** Email to active customers (purchased in last 12 months)
- **Response rate:** 8.2% (3,247 completed of 39,600 sent)
- **Margin of error:** ±1.7% at 95% confidence
- **Fielding period:** December 1-15, 2025
- **Incentive:** $10 store credit

## Sustainability Importance

*"How important is environmental sustainability when choosing outdoor gear?"*

| Response | Percentage | n |
|----------|------------|---|
| Extremely important | 28% | 909 |
| Very important | 39% | 1,266 |
| Somewhat important | 22% | 714 |
| Not very important | 8% | 260 |
| Not at all important | 3% | 98 |

**67% rate sustainability as "very" or "extremely" important** — higher than apparel industry average of 52%.

## Willingness to Pay Premium

*"How much more would you pay for a product with verified sustainable materials/manufacturing?"*

| Premium Level | Would Pay | Would Not Pay |
|---------------|-----------|---------------|
| 5% more | 78% | 22% |
| 10% more | 61% | 39% |
| 15% more | 42% | 58% |
| 20% more | 23% | 77% |
| 25%+ more | 11% | 89% |

**Sweet spot: 10-15% premium acceptable to majority.** Current eco-certified products average 18% premium — slightly above threshold.

## Feature Priority Ranking

*"Rank these sustainability features by importance to your purchase decision:"*

| Rank | Feature | Avg Score (1-7) |
|------|---------|-----------------|
| 1 | Durable/long-lasting products | 6.4 |
| 2 | Recycled materials | 5.8 |
| 3 | Ethical manufacturing (fair labor) | 5.6 |
| 4 | Carbon-neutral shipping | 5.2 |
| 5 | Recyclable packaging | 4.9 |
| 6 | Repair services offered | 4.7 |
| 7 | Product take-back/trade-in | 4.3 |

**Insight:** Durability is the #1 sustainability signal. "Buy it for life" messaging resonates more than "eco-friendly."

## Customer Segmentation

Cluster analysis revealed four distinct segments:

### Segment 1: Eco-Champions (23%)

- Sustainability is primary purchase driver
- Will pay 20%+ premium without hesitation
- Actively seeks certifications (bluesign, Fair Trade)
- Over-indexes on Patagonia, Cotopaxi purchases

> "I won't buy anything without checking the sustainability page first. I'd rather have fewer, better things." — Focus group, Eco-Champion

### Segment 2: Conscious Considerers (44%)

- Sustainability matters but balanced with price/performance
- Sweet spot: 10-15% premium
- Influenced by visible eco-badges and comparison tools
- Appreciate sustainability info but won't hunt for it

> "If two jackets are similar and one is more sustainable, I'll pay a bit more. But I'm not going to sacrifice quality or spend an hour researching." — Focus group, Conscious Considerer

### Segment 3: Performance-First (24%)

- Technical specs drive decisions
- Sustainability is a tiebreaker, not a driver
- Skeptical of "greenwashing"
- Responds to durability/longevity messaging

> "Show me the specs. If the 'eco' version performs as well and lasts as long, fine. But don't trade performance for a green badge." — Focus group, Performance-First

### Segment 4: Price-Focused (9%)

- Price is primary decision factor
- Sustainability not a significant consideration
- Often shopping sales/clearance
- Younger demographic skew (18-29)

> "I'm a student. I need gear that works at a price I can afford. Sustainability is a luxury I can't prioritize yet." — Focus group, Price-Focused

## Current Eco-Feature Awareness

*"Are you aware that Contoso offers these features?"*

| Feature | Aware | Unaware |
|---------|-------|---------|
| Eco-certified products (40% of catalog) | 34% | 66% |
| Carbon-neutral shipping | 28% | 72% |
| Recycled packaging | 41% | 59% |
| Gear trade-in program | 12% | 88% |

**Critical gap:** 88% unaware of our trade-in program. Major opportunity for visibility.

## Key Quotes

### On Loyalty & Sustainability

> "If your rewards program gave me points for recycling old gear or choosing eco products, I'd be way more engaged than just earning points on purchases." — Survey verbatim

> "REI's dividend feels like I'm part of something. Your points feel like... points." — Survey verbatim

### On Product Discovery

> "I'd love a filter for 'sustainable' but I don't trust that every brand defines it the same way. Third-party certifications matter." — Focus group participant

> "Make it easy. A green badge on the product card would be enough for me to consider it." — Survey verbatim

### On Trade-In

> "Wait, you have a trade-in program? I just donated my old tent to Goodwill. I would have traded it in." — Focus group participant

## Competitive Comparison

| Feature | REI | Patagonia | Backcountry | Contoso |
|---------|-----|-----------|-------------|---------|
| Eco-filter in search | ✓ | ✓ | ✗ | ✗ |
| Sustainability product badges | ✓ | ✓ | ✗ | ✗ |
| Repair services | ✓ | ✓ (Worn Wear) | ✗ | ✗ |
| Trade-in/resale | ✓ (Re/Supply) | ✓ (Worn Wear) | ✗ | ✓ (hidden) |
| Carbon offset at checkout | ✗ | ✓ (default) | ✗ | ✗ |

## Recommendations

| Initiative | Target Segment | Impact | Linked Spec |
|------------|---------------|--------|-------------|
| Eco-filter and badges in search | Conscious Considerers | +12% conversion on eco-SKUs (est.) | Search-Personalization |
| Trade-in program promotion | Eco-Champions | +$180K annual GMV (est.) | [Loyalty v2](/specs/loyalty-program-v2.md) |
| Sustainability loyalty perks | Eco-Champions | +8 NPS points (est.) | [Loyalty v2](/specs/loyalty-program-v2.md) |
| Durability/longevity messaging | Performance-First | +6% conversion on premium items (est.) | Marketing |
| Carbon offset at checkout | Conscious Considerers | 23% opt-in rate expected | [Checkout Redesign](/specs/checkout-redesign.md) |

## Implications

Sustainability is a real differentiator that we're under-leveraging. The 67% who care can't easily find eco-products, and 88% don't know about trade-in. Quick wins:

1. Add eco-filter and badges to search/browse (supports Conscious Considerers)
2. Promote trade-in program via email and checkout (supports Eco-Champions)
3. Tie sustainability actions to loyalty rewards (differentiates vs. competitors)

**Key strategic insight:** Frame sustainability as durability ("gear that lasts") rather than sacrifice ("pay more for the planet"). This resonates across all segments except Price-Focused.

---

*Full survey data and focus group recordings available in Dovetail. Segment definitions in Amplitude cohorts.*
