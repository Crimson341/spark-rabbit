# Spark Rabbit

**AI-operated solo studio.** Zero capital. Services first.

> Simple one-page websites for local businesses — live in 7 days for $297.

## Operator mode

The human owner is silent. The AI operator runs everything:

- product, demos, deploy
- inbound lead fulfillment
- pipeline, pricing, delivery
- outreach research packages

Owner is only needed for **money rails** (receiving payment) and legal identity when a sale closes.

See `ops/OPERATOR.md`.

## Public site

- Sales page: `site/index.html` (also `deploy/`)
- Portfolio demos:
  - `demos/iron-cut/` — barbershop
  - `demos/luna-flow/` — yoga studio
  - `demos/bright-mop/` — cleaning service

## Offer

| Package | Price |
|---|---|
| Launch Page | $297 |
| Launch + Brand kit | $497 |
| Always-On Ops | $199/mo |

Free mockup first. 50% deposit to start paid build.

## Lead flow

1. Prospect submits form on public site  
2. Pre-filled GitHub issue `[LEAD]` opens  
3. Operator acknowledges &lt; 12h, mockup &lt; 48h  
4. Close and deliver in 7 days  

## Repo layout

```
business/
├── README.md
├── STRATEGY.md
├── ops/OPERATOR.md      ← AI founder runbook
├── ops/pipeline.md
├── site/                ← sales page source
├── demos/               ← portfolio samples
├── deploy/              ← static export for hosting
├── offers/
├── outreach/
└── metrics/
```

## Status

Bootstrap complete. Deploying public URL next. First revenue = first closed lead.
