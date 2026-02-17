# Product Brain Customization Checklist

Use this checklist to adapt the demo repo for your own product. The repo is built on reusable PM workflow patterns—you just need to replace Contoso-specific content with your own.

---

## 🟢 UPDATE (Keep structure, replace content)

### [AGENTS.md](AGENTS.md)
- [ ] Line 1: `# Contoso Product Brain` → `# [Your Company] Product Brain`
- [ ] Line 2: Update subtitle from `Demo workspace... Contoso — outdoor gear e-commerce` → Your product description
- [ ] Line 3: Remove or update `"IMPORTANT: When adding new features, update README.md and prototypes/demo-narrative."`
- [ ] **"About Contoso"** section (after design system) → Replace with your company description
- [ ] **"Active Product Areas"** → Replace with your current initiatives (keep 2-3 examples)
- [ ] **"Team Personas"** → Replace with your actual team (name, role, focus area)
- [ ] Keep everything else: Folder Structure, Conventions, Design System, Integration

### [README.md](README.md)
- [ ] Line 1: Update title if desired
- [ ] Line 2: Replace `Agentic PM workflows demo — Contoso outdoor gear e-commerce` with your elevator pitch
- [ ] Lines 3-4: Replace context about Contoso with your product story
- [ ] **"Demo Scenarios"** section: Update all Contoso-specific examples to your domain
  - [ ] "Knowledge Repo" — Replace checkout/loyalty examples with your feature areas
  - [ ] "Feedback Synthesis" — Replace support-tickets example with your data source
  - [ ] "Data Analysis" — Update CSV filename and use case
  - [ ] "Rapid Prototyping" — Update checkout prototype example to your feature
  - [ ] "GitHub Issues" — Replace feedback theme example
- [ ] Keep framework sections: "What's Inside", "How PMs Think", workflow descriptions

### [CONTRIBUTING.md](CONTRIBUTING.md)
- [ ] Line 1: Replace `Contoso Product Brain` → `[Your Product] Product Brain`
- [ ] Keep everything else (contribution categories are generic and reusable)

### [roadmap/strategic-vision.md](roadmap/strategic-vision.md)
- [ ] Replace entire "Contoso Strategic Vision" section with yours
- [ ] Keep structure: Vision Statement, Mission, Five Principles, Bets

### [roadmap/brand-positioning.md](roadmap/brand-positioning.md)
- [ ] Replace entire "Contoso Brand Positioning" with yours
- [ ] Keep structure: Positioning statement, Personas, Competitive differentiation, Voice

### [prototypes/AGENTS.md](prototypes/AGENTS.md)
- [ ] Same updates as main AGENTS.md (if this file exists in your version)

---

## 🔴 DELETE (Contoso-specific demo content)

### specs/ (6 files)
- [ ] `checkout-redesign.md`
- [ ] `loyalty-program-v2.md`
- [ ] `mobile-app-v3.md`
- [ ] `returns-experience.md`
- [ ] `search-personalization.md`
- [ ] `sustainability-dashboard.md`

### insights/ (7 files)
- [ ] `competitive-analysis.md`
- [ ] `customer-feedback-q4.md`
- [ ] `mobile-usability-study.md`
- [ ] `nps-drivers-q4.md`
- [ ] `returns-friction-analysis.md`
- [ ] `search-analytics-deep-dive.md`
- [ ] `sustainability-survey-2025.md`

### research/ (6 markdown files)
- [ ] `ai-in-retail-2026.md`
- [ ] `competitor-deep-dive-ridgeline-outfitters.md`
- [ ] `competitor-deep-dive-summit-coop.md`
- [ ] `dtc-outdoor-brands.md`
- [ ] `gen-z-outdoor-trends.md`
- [ ] `outdoor-gear-market.md`

### research/data/ (2 files)
- [ ] `customer-survey-2025.csv`
- [ ] `support-tickets-q4-2025.csv`

### analysis/notebooks/ (1 file)
- [ ] `customer-nps-analysis-q4-2025.ipynb`

### roadmap/ (4 files)
- [ ] `2026-h1.md`
- [ ] `2026-h2.md`
- [ ] `okrs-2026.md`
- [ ] `tech-debt-register.md` *(optional: keep template if useful for your team)*

### prototypes/demo-narrative/ (optional)
- [ ] Delete entire folder if you don't need a conference demo narrative
- [ ] Keep if you plan to build your own demo presentation

---

## 🟡 OPTIONAL (Customize if desired)

- [ ] Design system colors in [AGENTS.md](AGENTS.md) — customize if your brand has a different palette
- [ ] Prototype tech stack — currently HTML/Tailwind/Alpine; swap or upgrade if preferred
- [ ] `.github/instructions/` — Read through and customize guidance for your team's specific workflow

---

## ✅ KEEP AS-IS (No changes needed)

- ✓ Folder structure (specs/, insights/, research/, analysis/, roadmap/, prototypes/)
- ✓ File naming conventions (kebab-case.md)
- ✓ Cross-linking patterns (specs ↔ insights)
- ✓ Markdown metadata format
- ✓ `.github/copilot-instructions.md`
- ✓ `.github/instructions/` folder structure (customize guidance but keep organization)
- ✓ `.github/prompts/` and `.github/agents/`
- ✓ Prototype templates (can be deleted or repurposed for your product)
- ✓ LICENSE

---

## Next Steps

1. **Start with UPDATE** — Customize AGENTS.md, README.md, and strategic documents to reflect your product
2. **Then DELETE** — Remove all Contoso demo files to clear clutter
3. **Then BUILD** — Start adding your own specs, insights, and research
4. **Then CUSTOMIZE OPTIONAL** — Fine-tune design and workflow guidance for your team

Done! Your Product Brain is ready to be your PM knowledge repository.