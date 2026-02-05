# Contoso Prioritization Framework

**Owner:** Product Leadership  
**Last Updated:** February 3, 2026  
**Review Cadence:** Quarterly

---

## RICE-Based Scoring Model

Contoso uses a modified RICE framework (Reach, Impact, Confidence, Effort) adapted for e-commerce priorities.

### Scoring Components

| Component | Description | Scale |
|-----------|-------------|-------|
| **Reach** | Users/transactions affected per quarter | Actual number (e.g., 500K) |
| **Impact** | Revenue/conversion improvement | 0.25 (minimal) → 3 (massive) |
| **Confidence** | Data quality supporting estimates | 20% → 100% |
| **Effort** | Person-months required | Actual estimate |

### Formula

```
RICE Score = (Reach × Impact × Confidence) / Effort
```

### Impact Scale Guide

| Score | Meaning | Example |
|-------|---------|---------|
| 3.0 | Massive | >20% conversion lift, new revenue stream |
| 2.0 | High | 10-20% conversion lift, major cost reduction |
| 1.0 | Medium | 5-10% improvement, moderate efficiency gain |
| 0.5 | Low | 1-5% improvement |
| 0.25 | Minimal | <1% improvement, quality of life |

---

## Current Initiative Scores (2026)

| Initiative | Reach | Impact | Confidence | Effort | **RICE** | Priority |
|------------|-------|--------|------------|--------|----------|----------|
| Checkout Redesign | 1.2M | 2.0 | 70% | 2.0 | **847** | #1 |
| Loyalty v2 | 850K | 1.5 | 80% | 1.5 | **612** | #2 |
| Mobile App v3 | 500K | 1.5 | 60% | 3.0 | **150** | #3 |
| Search Personalization | 1.0M | 1.0 | 50% | 4.0 | **125** | #4 |
| International (CA/UK) | 200K | 2.0 | 40% | 5.0 | **32** | #5 |

---

## Trade-off Decisions

### Why Checkout > Loyalty > Mobile

**Decision Date:** December 2025  
**Decision Makers:** CPO, VP Engineering, VP Marketing

**Rationale:**

1. **Checkout Redesign first:**
   - 68% cart abandonment is bleeding revenue daily
   - Highest confidence (competitive benchmarks, user research)
   - Foundational for other initiatives (Loyalty enrollment, Mobile checkout)
   - Clear, measurable success criteria

2. **Loyalty v2 second:**
   - Depends on checkout for frictionless enrollment
   - 2.3M existing members = large reach
   - Partner agreements require lead time (sequential constraint)
   - Customer retention compounds over time

3. **Mobile App v3 deferred to H2:**
   - Requires stable checkout & loyalty APIs from H1
   - PM hire in progress (capacity constraint)
   - Web mobile conversion improvements from checkout will reduce urgency
   - Lower confidence without dedicated PM research

**Alternative considered:** Mobile-first approach  
**Rejected because:** Mobile web improvements via checkout redesign deliver 80% of value at 30% of mobile app effort. Native app adds incremental value, not transformational.

---

## Scoring Guidelines

### When to Re-score

- Major market shift or competitor move
- New customer research data (>500 responses)
- Significant scope change (>20% effort delta)
- Quarterly planning cycles

### Confidence Boosters

| Action | Confidence Increase |
|--------|---------------------|
| User research (n>100) | +15% |
| A/B test on similar feature | +20% |
| Competitive validation | +10% |
| Engineering spike complete | +10% |

### Red Flags

- Confidence <50% + Effort >3 months → Needs research spike
- Impact based on single stakeholder opinion → Gather more data
- Reach estimates not tied to analytics → Validate with data team

---

## Related Documents

- [H1 2026 Roadmap](/roadmap/2026-h1.md) — Current execution plan
- [H2 2026 Roadmap](/roadmap/2026-h2.md) — Future initiatives
- [OKRs 2026](/roadmap/okrs-2026.md) — Company and team objectives
- [Tech Debt Register](/roadmap/tech-debt-register.md) — Effort considerations

---

*Framework reviewed and approved by Product Leadership, January 2026*
