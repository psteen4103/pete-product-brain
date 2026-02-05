# Mobile Usability Study: Task Completion & Pain Points

**Prepared by:** Jordan Chen, UX Research  
**Date:** January 22, 2026  
**Sources:** Moderated usability sessions (n=12), heatmap analysis, session recordings

---

## Executive Summary

Our mobile experience significantly underperforms desktop, with key tasks taking 2.4x longer on mobile. This study identifies specific friction points that directly inform the [Mobile App v3](/specs/mobile-app-v3.md) roadmap and validates checkout improvements in [Checkout Redesign](/specs/checkout-redesign.md).

## Methodology

- **Participants:** 12 outdoor enthusiasts (6 existing customers, 6 prospects)
- **Demographics:** Ages 28-52, mix urban/suburban, iOS and Android users
- **Tasks:** Product search, filtering, add to cart, checkout, account management
- **Tools:** Lookback for recordings, Hotjar for heatmaps, SUS scoring

## Task Completion Results

| Task | Success Rate | Avg Time (sec) | Desktop Benchmark |
|------|--------------|----------------|-------------------|
| Find specific product | 83% | 47s | 22s |
| Apply size filter | 58% | 31s | 12s |
| Add to cart | 92% | 8s | 6s |
| Complete checkout | 42% | 187s | 78s |
| Find order history | 67% | 24s | 11s |
| Update shipping address | 50% | 52s | 19s |

**Critical finding:** Checkout task completion of 42% is unacceptable. 5 of 12 participants abandoned during checkout flow.

## Key Pain Points

### 1. Filter Interaction (58% success)

> "These dropdowns are impossible on my phone. I keep accidentally selecting the wrong size and there's no way to see what I picked." — P04, iPhone 14 Pro

> "I gave up on filtering. The menu covers the whole screen but then I can't see any products to know if it's working." — P09, Samsung Galaxy S23

**Heatmap finding:** 73% of tap attempts on filter pills missed their target. Touch targets are 32px (minimum recommended: 44px).

### 2. Checkout Form Fields (42% completion)

> "The keyboard keeps covering the field I'm typing in. I literally cannot see what I'm entering for my address." — P02, iPhone 13

> "Why do I have to scroll sideways to see the full form? This feels like a website from 2010." — P11, Pixel 7

**Session observation:** Average of 3.2 input errors per checkout attempt due to field visibility issues.

### 3. Navigation Confusion

> "I found the tent but then I couldn't figure out how to get back to my search results. The back button took me all the way home." — P07, iPhone 15

**Heatmap finding:** 67% of users tapped the logo expecting "back" behavior, not home navigation.

## System Usability Scale (SUS) Scores

| Platform | SUS Score | Industry Benchmark | Rating |
|----------|-----------|-------------------|--------|
| Mobile web | 52 | 68 | Poor |
| Desktop web | 71 | 68 | Good |
| Competitor avg (mobile) | 74 | 68 | Good |

A SUS score of 52 places our mobile experience in the bottom 15% of e-commerce sites.

## Heatmap Insights

**Product Detail Page:**
- 89% scroll below the fold but only 23% reach size selection
- "Add to Cart" button gets 12% of taps; "See Reviews" gets 34%
- Users hunting for inventory/shipping info (not prominently displayed)

**Cart Page:**
- Promo code field draws 67% of initial attention (but 78% leave it empty)
- Quantity selector has high mis-tap rate (small increment buttons)
- Estimated total partially obscured on smaller screens

## Participant Quotes by Theme

### Frustration with Speed
> "Every tap feels like I'm waiting. On Amazon, it's instant." — P01

### Trust Concerns
> "I don't love entering my credit card on a mobile site that feels this clunky." — P06

### Comparison to Competitors
> "REI's app just works. Why don't you have an app?" — P12

## Recommendations

| Issue | Recommendation | Priority | Linked Spec |
|-------|---------------|----------|-------------|
| Filter touch targets | Increase to 48px minimum | P0 | [Mobile App v3](/specs/mobile-app-v3.md) |
| Checkout form | Native app with proper keyboard handling | P0 | [Checkout Redesign](/specs/checkout-redesign.md) |
| Navigation model | Implement proper back-stack behavior | P1 | [Mobile App v3](/specs/mobile-app-v3.md) |
| Page speed | Target <2s LCP on 4G | P1 | [Mobile App v3](/specs/mobile-app-v3.md) |
| Add to Cart visibility | Float above fold, increase size | P2 | [Mobile App v3](/specs/mobile-app-v3.md) |

## Implications

This study provides strong evidence for prioritizing native mobile app development. Mobile web optimization has diminishing returns given fundamental browser limitations around form handling and navigation.

**Recommended next step:** Validate native app prototype with 8 of these participants (re-recruitment approved).

---

*Full session recordings available in Lookback. Heatmaps accessible in Hotjar dashboard under "Mobile Usability Jan 2026" project.*
