---
description: "Use when building rapid prototypes, mockups, or proof-of-concepts. Covers tech stack and publishing to gh-pages."
applyTo: "prototypes/**"
---

# Prototype Guidelines

## Purpose

Prototypes are for validating ideas fast. They're disposable—optimize for speed and clarity, not production quality.

## Preferred Stack

Use this stack for maximum velocity:
- **HTML** — Single-file when possible
- **Tailwind CSS** — Via CDN: `<script src="https://cdn.tailwindcss.com"></script>`
- **Alpine.js** — For interactivity: `<script defer src="https://cdn.jsdelivr.net/npm/alpinejs@3.x.x/dist/cdn.min.js"></script>`

No build step required. Stakeholders can open the HTML file directly.

## File Structure

```
prototypes/
  <feature-name>/
    index.html      # Main prototype
    README.md       # What it demonstrates, link to spec
    assets/         # Images, sample data (optional)
```

## Publishing to gh-pages

To share prototypes externally:

1. Ensure prototype works at `prototypes/<name>/index.html`
2. Push to main branch
3. GitHub Pages serves from: `https://contoso.github.io/product-brain/prototypes/<name>/`

Update the prototype's README with the live URL once published.

## Best Practices

- Link to the spec it validates in README
- Include realistic sample data (use Contoso demo data, not Lorem Ipsum)
- Add a "This is a prototype" banner so viewers know it's not production
- Keep scope tight: one interaction flow per prototype
- Delete or archive after decision is made
