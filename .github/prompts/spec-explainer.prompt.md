---
description: "Transform a product spec into a polished explainer site for stakeholder communication"
agent: "agent"
tools: ["read", "edit", "execute"]
---

# Spec to Explainer Site

Transform a technical product spec into a visually compelling single-page explainer for stakeholders.

## Input

Specify which spec to transform from `specs/` directory.

## Process

1. **Read** the source spec and extract core narrative
2. **Identify** the problem statement, solution, and key benefits
3. **Structure** content for non-technical stakeholders
4. **Generate** single-page HTML with dark theme design:
   - Hero section with bold headline and one-liner
   - Problem/solution narrative with visual contrast
   - Key features with icons or visual markers
   - Timeline or milestones if applicable
   - Call-to-action or next steps
5. **Apply** visual hierarchy: large headings, generous spacing, accent colors
6. **Save** to `prototypes/` with descriptive filename

## Output

A polished `prototypes/{spec-name}-explainer.html` file that:

- Tells the story in 60 seconds of scrolling
- Works standalone (no external dependencies)
- Prints cleanly for async review
- Includes source spec reference in footer
