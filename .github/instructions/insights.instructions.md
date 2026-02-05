---
description: "Use when processing customer feedback, user research, or competitive analysis. Covers insight extraction and tagging."
applyTo: "insights/**"
---

# Insight Processing Guidelines

## Insight Structure

Each insight file should follow this format:

### Source
- Type: `user-research` | `support-ticket` | `survey` | `competitive` | `analytics`
- Date collected
- Sample size or confidence level

### Key Quotes
Include 2-3 verbatim quotes that capture the insight:
> "I abandoned my cart because I couldn't find the promo code field" — User P12

### Theme Summary
One paragraph synthesizing the pattern observed. Be specific about:
- Who experiences this (link to persona if applicable)
- Frequency/severity of the issue
- Context where it occurs

### Implications
- What this suggests we should build or change
- Link to existing specs this supports: `[[specs/checkout-redesign]]`
- Priority recommendation: `high` | `medium` | `low`

## Tagging Conventions

Apply relevant tags in frontmatter:
- **checkout** — cart, payment, shipping, promo codes
- **loyalty** — rewards, points, membership tiers
- **ux** — navigation, search, mobile experience
- **pricing** — discounts, competitor pricing, value perception
- **onboarding** — new user experience, account creation

## Linking to Specs

When an insight supports or challenges a spec:
1. Add a backlink in the insight's Implications section
2. Update the spec's "Supporting Insights" list
3. If insight contradicts spec assumptions, flag in #product-specs
