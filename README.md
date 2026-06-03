# SAP Joule + SAP Advanced Event Mesh

**A reusable pattern and eleven ready-to-run plays** for event-driven agentic AI on SAP landscapes.

🔗 **[View the live page →](https://solacese.github.io/sap-joule-aem-value/)**

## What this is

A single-page reference that shows how SAP Joule agents and SAP Advanced Event Mesh combine into a repeatable, production-grade pattern:

1. **Trigger** — Joule subscribes to a business event on AEM
2. **Tools** — The agent calls real-time data streams as pub/sub tools
3. **Transactions** — Joule publishes a throttled, secure, well-formed event back onto the mesh

The same pattern is applied across **11 industry plays** (manufacturing, finance, automotive, retail, logistics, energy, procurement, field service) — each with specific topics, business benefits, and governance guardrails.

## Running locally

Just open `index.html` in any browser — it's a self-contained static page with no build step.

```bash
open index.html
# or
python3 -m http.server 8000
```

## GitHub Pages

This site is deployed via GitHub Pages from the `main` branch root. The `index.html` file is served directly.

To enable: **Settings → Pages → Source: Deploy from a branch → `main` / `/ (root)`**

## Tech

- Pure HTML, CSS, JavaScript — no frameworks, no build tools
- Figtree + Space Mono from Google Fonts
- Scroll-reveal animations via IntersectionObserver
- Animated flow diagram in the hero section
- Mobile-responsive with hamburger nav
- Respects `prefers-reduced-motion`
- Filter buttons for the 11 plays by industry domain

## License

Internal use — Solace EMEA & UK.
