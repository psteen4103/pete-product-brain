---
description: "Create a well-structured GitHub Issue from a product insight with proper labels and context"
agent: "agent"
tools: ["read", "mcp_github/*"]
---

# Insight to GitHub Issue

Convert a product insight into an actionable, well-documented GitHub Issue.

## Input

Specify the insight document from `insights/` to convert.

## Process

1. **Read** the insight document thoroughly
2. **Extract** the core problem or opportunity
3. **Formulate** as an actionable issue:
   - Clear, specific title (not vague like "Improve checkout")
   - Problem statement with user impact
   - Supporting evidence from the insight (quotes, data)
   - Proposed approach or acceptance criteria
4. **Add context** linking back to the insight doc
5. **Suggest labels** based on content:
   - Type: `enhancement`, `bug`, `research`
   - Area: `checkout`, `onboarding`, `loyalty`, `search`
   - Priority: `p0-critical`, `p1-high`, `p2-medium`
6. **Create** the issue via GitHub API

## Output

A GitHub Issue with:

- **Title**: Action-oriented, scannable
- **Body**: Context, evidence, and proposed solution
- **Labels**: Appropriate categorization
- **Footer**: Link to source insight for traceability

Example title format: "Reduce checkout friction: Add guest checkout option"
