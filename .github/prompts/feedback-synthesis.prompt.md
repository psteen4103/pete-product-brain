---
description: "Synthesize raw customer feedback into structured insights with themes, quotes, and product implications"
agent: "agent"
tools: ["read", "edit"]
---

# Feedback Synthesis

Analyze raw customer feedback and produce a structured insight document.

## Input

Provide the feedback source: survey responses, call transcripts, support tickets, or NPS comments.

## Process

1. **Read** the raw feedback from the provided file or pasted content
2. **Extract themes** - Identify recurring patterns, pain points, and feature requests
3. **Select key quotes** - Pull 3-5 verbatim quotes that best represent each theme
4. **Map to product areas** - Connect themes to specific features or flows (e.g., checkout, onboarding, search)
5. **Assess sentiment** - Rate overall sentiment and urgency per theme
6. **Identify opportunities** - Translate pain points into potential product improvements

## Output

Create a structured insight document in `insights/` with:

- **Summary**: 2-3 sentence overview
- **Themes**: Ranked list with quote count and sentiment
- **Key Quotes**: Verbatim excerpts with context
- **Product Mapping**: Which areas are affected
- **Recommendations**: Prioritized action items
- **Metadata**: Source, date range, sample size
