# Tech Debt Register

**Owner:** Engineering Leadership  
**Last Updated:** February 3, 2026  
**Review Cadence:** Monthly (Engineering All-Hands)

---

## Overview

Technical debt items that impact product delivery, stability, or velocity. Items are prioritized based on business impact and blocking potential.

**Current policy:** 20% of sprint capacity allocated to tech debt reduction.

---

## Critical Priority

### TD-001: Payment Gateway Migration {#payment-gateway}
**Status:** 🟡 In Progress  
**Owner:** Platform Team  
**Estimated Effort:** 8 person-weeks  
**Target:** September 2026

**Problem:**  
Current Stripe integration uses deprecated API (v2019-03-14). Missing features:
- Apple Pay domain verification (blocking checkout redesign)
- Multi-currency support (blocking international expansion)
- 3DS2 compliance (mandatory by October 2026)

**Impact:**
- Blocks [Checkout Redesign](/specs/checkout-redesign.md) Apple Pay integration
- Blocks [International Expansion](/roadmap/2026-h2.md) currency support
- Regulatory compliance risk

**Plan:**
1. Migrate to Stripe API v2023-10-16 (Q1 - In Progress)
2. Multi-currency configuration (Q2)
3. Full 3DS2 implementation (Q3)

---

### TD-002: Legacy Cart System
**Status:** 🟠 Planning  
**Owner:** Backend Team  
**Estimated Effort:** 12 person-weeks  
**Target:** Q4 2026

**Problem:**  
Cart service is a 7-year-old monolith with:
- No horizontal scaling (peak traffic issues during sales)
- Tight coupling to legacy inventory system
- 4-second average response time under load
- 23% of on-call incidents trace to cart service

**Impact:**
- Checkout performance ceiling
- Black Friday/Cyber Monday scaling risk
- Developer velocity (2x time for cart-adjacent features)

**Plan:**
1. Cart API extraction (Q2)
2. Redis session migration (Q3)
3. Monolith decomposition (Q4)

**Workaround:** Load balancer traffic shaping during peak events

---

## High Priority

### TD-003: Search Index Staleness
**Status:** ⚪ Backlog  
**Owner:** Platform Team  
**Estimated Effort:** 3 person-weeks  
**Target:** Q3 2026

**Problem:**  
Elasticsearch index refresh runs every 4 hours. New products and inventory changes have delayed visibility.

**Impact:**
- Customer sees out-of-stock items in search results
- New product launches have discovery delay
- [Search Personalization](/roadmap/2026-h2.md) requires real-time index

**Plan:** Implement near-real-time indexing via Kafka events

---

### TD-004: Test Coverage Gaps
**Status:** 🟡 In Progress  
**Owner:** QA Team  
**Estimated Effort:** Ongoing (2 hrs/week)  
**Target:** 60% coverage by Q2

**Problem:**  
Critical paths have inadequate test coverage:
- Checkout flow: 34% unit test coverage
- Payment processing: 28% integration test coverage
- Loyalty points calculation: 41% coverage

**Impact:**
- Regression risk during feature launches
- Manual QA bottleneck (3-day regression cycle)

**Plan:** Coverage targets per PR, automated in CI pipeline

---

## Medium Priority

### TD-005: Session Management
**Status:** ⚪ Backlog  
**Owner:** Backend Team  
**Estimated Effort:** 2 person-weeks  
**Target:** Q4 2026

**Problem:**  
Sessions stored in MySQL, causing login latency and database load.

**Impact:** 400ms login latency, database contention during peaks

**Plan:** Migrate to Redis session store

---

### TD-006: Image CDN Configuration
**Status:** ⚪ Backlog  
**Owner:** Platform Team  
**Estimated Effort:** 1 person-week  
**Target:** Q3 2026

**Problem:**  
Product images not optimized for mobile. Missing WebP format, no responsive sizing.

**Impact:** Mobile page load 2.3s slower than desktop, impacts Core Web Vitals

**Plan:** CloudFront Lambda@Edge image transformation

---

## Resolved (Last 90 Days)

| ID | Item | Resolved | Notes |
|----|------|----------|-------|
| TD-007 | Node.js 16 EOL | Jan 2026 | Upgraded to Node 20 LTS |
| TD-008 | SSL certificate automation | Dec 2025 | Let's Encrypt integration |

---

## Related Documents

- [H1 2026 Roadmap](/roadmap/2026-h1.md) — Tech debt allocation
- [OKRs 2026](/roadmap/okrs-2026.md) — KR4 payment migration
- [H2 2026 Roadmap](/roadmap/2026-h2.md) — International dependencies

---

*Tech debt review: Second Wednesday of each month*
