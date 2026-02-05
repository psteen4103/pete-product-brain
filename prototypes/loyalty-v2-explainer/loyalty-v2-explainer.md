# Trail Rewards: Loyalty Program Transformation

> Reimagining loyalty through experiential tiers, not point hoarding

## Meta
- **Author(s)**: Marcus Webb, Product Manager
- **Last Updated**: February 4, 2026
- **Status**: In Review → Awaiting Finance Sign-Off (Jan 25)
- **Audience**: Executive team, board, marketing, engineering, finance
- **The Ask**: Approve investment in Trail Rewards v2; green-light Q2 beta preparation

## TL;DR

Contoso Rewards is broken: 12% redemption (vs. 25-30% industry benchmark), low engagement, confusing experience. We're replacing points-hoarding with **Trail Rewards**, a three-tier program built on *experiential benefits*, *sustainability*, and *community*. Summit members get gear try-before-buy, adventure partnerships, and concierge. Expected outcomes: 30% redemption, +40 NPS, 55% revenue share by Q3 2026.

---

## Problem: Current Loyalty Is Broken

### The Pain (Quantified)

- **12% redemption rate** — Members are earning points but not redeeming them (industry benchmark: 25-30%)
- **Only 8% reach first reward** — 500-point threshold is too high; most members abandon before first payout
- **NPS for program: +12** — Vs. +45 for the overall Contoso brand. Loyalty experience is dragging the relationship.
- **23% active rate** — Most enrolled members are inactive; we're not sustaining engagement

*Evidence: Q4 customer feedback synthesis ([insights/customer-feedback-q4.md](../../insights/customer-feedback-q4.md)); program analytics dashboard*

### What's Broken

Members feel:
- **Confused** — "How many points is that actually worth? Why is this taking forever?"
- **Unrewarded** — Small purchases = tiny points. Redemptions feel like a chore, not a win.
- **Cynical** — "This is just a trick to make me buy more stuff I don't need."

The program is optimized for *volume* (spending), not for *engagement* (relationship).

### Why Now?

1. **Competitive gap** — REI and Peak Design have tier-based adventure programs. We're falling behind.
2. **Sustainability tailwind** — 40% of our catalog is eco-certified. Members want to earn for *giving*, not just taking.
3. **Q2 window** — Checkout redesign completion frees engineering bandwidth for loyalty infrastructure changes.

---

## Solution: Trail Rewards

### The Transformation

Instead of "accumulate points for discounts," we're building "climb a mountain of benefits."

**Trail Rewards** is a **three-tier experiential program** where climb from Explorer → Trailblazer → Summit earns access to community, adventure, and sustainability benefits.

### Tier Structure

| Tier | Entry Path | Spirit & Benefits |
|------|-----------|------------------|
| **Explorer** | Free signup (new members) | Discover phase: 5% rewards back, birthday gift, early sale access, app exploration |
| **Trailblazer** | $500/year spend OR 3 purchases within 12 months | Active adventurer: 10% rewards back, free shipping, gear rental discounts, invite to member events, AllTrails Pro partnership |
| **Summit** | $1,500+/year spend | Committed community leader: 15% rewards back, exclusive product drops, concierge service, **gear try-before-buy**, national park partnerships, annual trail cleanup event invite |

### Experiential Benefits (The Real Value)

Members aren't redeeming *points* — they're unlocking *experiences*:

#### Tier 1: Gear Try-Before-Buy (Summit Exclusive)
- Rent new gear for 2 weeks before committing to purchase
- Real-world test: "Is this tent actually waterproof in the PNW?"
- Builds trust; reduces return rates; Summit members feel investment-worthy

#### Tier 2: Adventure Partnerships
- **AllTrails Pro Access** (Trailblazer+): Offline maps, pro features
- **National Park Passes** (Summit+): Annual pass partnerships with NPS
- **REI Adventures discounts** (Summit+): Guided experiences, expeditions
- Not discount-code transactional — this is *access to adventures*

#### Tier 3: Sustainability Program
- Donate old gear → earn Trail Points (gives expired/damaged gear new life)
- Contoso carbon-offsets every redemption
- Summit members can amplify: sponsor cleanups (points boost)
- Taps into sustainability values; attracts mission-driven members

### Earning Mechanics

- **Base:** 1 Trail Point per $1 spent (transparent, not confusing)
- **Bonus activities:** Reviews (50 pts), referrals (200 pts), app purchases (2x multiplier)
- **Durability:** Points never expire for active members (simple threshold: 1 purchase/year)

### Migration Strategy

Existing members see immediate wins:
- All auto-migrate to Explorer tier (free, no action needed)
- Current points convert at 100:1 ratio to Trail Points (existing value preserved)
- "Trail Bonus" period (60 days post-launch): 2x points on everything
- Personalized email per tier showing "Your new benefits" (educational, not scary)

---

## Key Assumptions

> These are beliefs we're operating on. Flag if any conflict with your intel.

- [ ] **Members will value experiences more than generic discounts** — *Status: Validated* (Q4 feedback shows "I want to try before I buy" and "adventure access" as top unmet needs)
- [ ] **$500/$1,500 thresholds are achievable** — *Status: Unvalidated* (need spend distribution analysis; higher risk if avg customer is <$500/year)
- [ ] **AllTrails, NPS, REI will partner with us** — *Status: In Discussion* (preliminary conversations positive; terms TBD)
- [ ] **Concierge can be outsourced profitably** — *Status: TBD* (engineering feasibility unknown; cost model TBD)
- [ ] **Members won't abuse referral program** — *Status: Risk* (referral fraud is a known issue; need anti-fraud strategy)

---

## Success Metrics

We're measuring engagement *quality*, not just volume:

| Metric | Current Baseline | Target (6mo) | Target (12mo) | How We Measure |
|--------|------------------|--------------|----------------|---|
| **Redemption Rate** | 12% | 30% | 40% | % of enrolled members who redeem ≥1 benefit in period |
| **Active Member Rate** | 23% | 40% | 50% | Members with 1+ transaction in 90-day window |
| **Member Revenue Share** | 34% | 45% | 55% | % of annual revenue from enrolled members (vs. non-members) |
| **Program NPS** | +12 | +35 | +40 | Quarterly member satisfaction survey |
| **Tier Distribution** | 100% Explorer (no tiers) | Explorer 60%, Trailblazer 30%, Summit 10% | Explorer 50%, Trailblazer 35%, Summit 15% | Member count by tier |

---

## Open Questions & Risks

### Questions Blocking Launch

1. **Partner Finality** (Owner: Marcus) — AllTrails, NPS, REI Experiences have agreed in principle, but contracts need CFO review. Target resolution: Jan 20.
2. **Concierge Model** (Owner: Sam, CS Lead) — Summit service: in-house (expensive, high-touch) or outsource? Staffing/cost impact? Target decision: Jan 22.
3. **Fraud Prevention** (Owner: Engineering) — Referral abuse risk: how do we detect/prevent fake referral rings? Detection rules needed before beta. Target: Feb 5.
4. **Finance Tier Economics** (Owner: CFO) — Tier discounts, experiential costs, infrastructure investment all need ROI modeling. Awaiting formal review.

### Known Risks & Mitigations

| Risk | Mitigation |
|------|-----------|
| **Thresholds too high** — Members can't qualify for Trailblazer | Start with lower thresholds in beta; monitor 4-week velocity. Be ready to adjust to $300/$1,200 if needed. |
| **Partner terms change** — AllTrails/NPS renegotiate post-launch | Lock contracts pre-launch; build 20% contingency into benefit roadmap (non-partner fallbacks). |
| **Redemption doesn't improve** — Program doesn't address root cause (low engagement) | This is an engagement *vessel*, not a magic bullet. Needs concurrent: email nurture, onboarding improvements, in-app education. |
| **Fraud on referrals** — Members game the system | Pre-launch: ML model to detect patterns; post-launch: manual review team for high-value invites. |
| **Concierge overwhelm** — Summit service falls apart at scale | Beta: cap Summit tier at 2,500 members; manual enrollment review. Scale only after ops validated. |

---

## Out of Scope

Explicitly **not** in v2 launch:

- Mobile app redesign for loyalty dashboard (native feature tracked separately)
- Integration with third-party POS systems (B2B ordering)
- International program expansion (US/Canada only, Q4 2026)
- Gamification leaderboards (fun, but adds complexity; v2.1 discussion)

---

## Timeline & Milestones

| Phase | Dates | Key Deliverables | Status |
|-------|-------|------------------|--------|
| **Planning & Validation** | Jan 15 - Feb 15 | Finance sign-off, contract finalization, fraud rules | Current |
| **Beta Build** | Feb 20 - Apr 30 | Infrastructure, frontend, migration tools, ops playbook | Scheduled |
| **Closed Beta** | May 1 - May 31 | 5,000 member pilot, feedback loops, metrics validation | Scheduled |
| **Full Launch** | Jun 1 - Jun 30 | All members migrated, production stability, comms campaign | Scheduled |
| **Optimization** | Jul - Sep 30 | Tier rebalancing, benefit promotions, CS training | Scheduled |

**Ship date: Q2 2026 beta (May). Full rollout: Q3 (June-July).**

---

## Success Looks Like (6 Months Post-Launch)

- Summit members are excitedly talking about gear try-before-buy (organic word-of-mouth)
- Redemption rate hits 30%+ (low-friction, high-value benefits)
- Trailblazer tier becomes aspirational (most active members pursuing it)
- Marketing uses loyalty in acquisition messaging (retention plays into growth)
- NPS for program rises to +35+ (loyalty is now a brand strength, not a drag)

---

## Appendix: Discussion Log

| Date | Topic | Owner | Outcome |
|------|-------|-------|---------|
| Jan 18 | Initial spec review; alignment on experiential angle | Marcus | Spec approved for stakeholder review, escalation for finance sign-off |
| Jan 20 | Partner conversation readout | Marcus | AllTrails & REI positive; NPS still negotiating annual volume commitments |
| Jan 23 | CS capacity for concierge | Sam | Outsource preferred; RFP issued to BPOs; decisions by Jan 25 |

---

## Related Documents

- [Q4 Customer Feedback Synthesis](/insights/customer-feedback-q4.md) — "I want to try gear first" ranked #2 unmet need
- [H1 2026 Roadmap](/roadmap/2026-h1.md) — Loyalty v2 scheduled post-checkout
- [Contoso Personas](/personas/core-personas.md) — Adventurer & Sustainability-First personas highest priority for this program
- [Current Loyalty Program Analytics](/analytics/loyalty-current-state.md) — Deep dive on 12% redemption rate causes
