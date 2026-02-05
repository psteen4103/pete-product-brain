# Contoso Product Brain

> Demo workspace for agentic PM workflows at Contoso — outdoor gear e-commerce

IMPORTANT: When adding new features, update README.md and prototypes/demo-narrative.

---

## Project Guidelines

### Folder Structure
| Folder | Purpose |
|--------|---------|
| `specs/` | PRDs with Problem Statement, Proposed Solution, Success Metrics, Open Questions |
| `insights/` | Synthesized research with quotes, recommendations, and spec backlinks |
| `research/` | Market analysis, competitive intel, user studies |
| `research/data/` | Raw CSV datasets for analysis |
| `roadmap/` | Quarterly plans, OKRs, prioritization |
| `prototypes/` | Disposable HTML demos — no build step |
| `analysis/notebooks/` | Jupyter notebooks for data exploration |

### Conventions
- **File naming**: `kebab-case.md` everywhere
- **Spec headers**: Use Markdown metadata (not YAML frontmatter): `**Status:** Draft`, `**Author:**`, `**Last Updated:**`, `**Stakeholders:**`
- **Cross-linking**: Specs link to `insights/`, insights link back to `specs/` — unlinked content is "unvalidated"
- **Prototype stack**: HTML + [Tailwind CDN](https://cdn.tailwindcss.com) + Alpine.js — stakeholders open files directly
- **Brand colors**: Sage `#7a9b7e`, Earth `#8b7b6b`, Cream `#fefcf7`

---

## About Contoso

Contoso is an outdoor gear e-commerce retailer with 50K+ products across camping, hiking, climbing, and water sports. We're committed to sustainability: 40% of our catalog features eco-certified products, and we offset shipping emissions for all orders.

## What Is This Repo?

This is our **Product Brain** — a knowledge repository where Product Management maintains specs, research, insights, and roadmaps. Think of it as the single source of truth for product decisions.

## Active Product Areas

- **checkout-redesign** — Streamlining purchase flow, reducing cart abandonment
- **loyalty-program-v2** — Revamping rewards program with sustainability incentives

## Team Personas

- **Alex** (PM Lead) — Owns checkout-redesign, focuses on conversion metrics
- **Jordan** (UX Researcher) — Runs user studies, synthesizes feedback into insights
- **Sam** (Engineering Lead) — Technical feasibility, implementation estimates

## Integration

This repo integrates with:
- **GitHub Issues** — Tasks, bugs, and feature requests
- **GitHub Projects** — Sprint planning boards
- **Figma** — Design files linked from specs

---

*This is a demo workspace for conference presentation purposes.*
