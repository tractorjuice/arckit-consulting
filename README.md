# ArcKit FDE

**ArcKit Forward Deploy Engineering (FDE)**: embedded architecture engineering for UK public sector programmes.

Senior architects deployed into delivery teams to produce decision-grade governance evidence, then stay embedded through assurance, procurement and delivery.

Live site: <https://tractorjuice.github.io/arckit-fde/>

## What this repo is

Source for the static GitHub Pages site at the URL above. Hand-written HTML and CSS, no build step.

## Layout

| Path | Purpose |
| --- | --- |
| `index.html` | Single-page site (hero, what FDE means, first sprint, embedded follow-on, policy alignment, samples, delivery cadence, CTA) |
| `samples/governance-pack.html` | Representative outputs from a first-sprint pack (principles, requirements, risk, stakeholders) |
| `styles.css` | All site styling |
| `assets/` | Logo (`arckit-mark.svg`) and hero image (`hero-governance-pack.png`) |
| `llms.txt` | Structured summary for LLM discovery |
| `sitemap.xml`, `robots.txt` | Search engine metadata |

## Local preview

Open `index.html` in a browser, or run any static file server from the repo root:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000/`.

## Publishing

GitHub Pages is configured to publish from the `main` branch root. Pushes to `main` trigger a Pages rebuild within a minute or two.

## Core offer

- **First sprint (£25K, one week)**: Principles, Requirements, Risk, Stakeholders
- **Follow-on embedded delivery**: Design and decisions, procurement and vendor, assurance and AI, team enablement

Outputs are shaped for HM Treasury Green Book and Orange Book, GOV.UK Service Standard, Technology Code of Practice (TCoP), and Government Functional Standard GovS 005 Digital.

## About ArcKit

[ArcKit](https://arckit.org) is an enterprise architecture governance toolkit for AI coding assistants. The toolkit runs alongside the FDE so that discovery, evidence and traceability work that traditionally needs a large consultancy bench is compressed into focused sprints.

## Contact

mark.craddock@mcc.co.uk
