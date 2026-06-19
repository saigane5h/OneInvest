# OneInvest

AI-native IPO + Bond + Equity subscription platform — designed for the 60-second UPI window between mandate and bank confirmation.

## Pages

| File | Purpose |
|---|---|
| [`oneinvest.html`](./oneinvest.html) | Journeys & workflow — homepage mockup, three personas, three journey flows (success / stuck / failed) |
| [`oneinvest-prototype.html`](./oneinvest-prototype.html) | Interactive prototype — phone-frame app with persona + scenario switcher, live "persona diff" panel |
| [`oneinvest-prd.html`](./oneinvest-prd.html) | Product Requirements Doc — problem, competitive matrix, AI thesis, 8 KPIs, risks |

## Run locally

Open any of the three HTML files directly in a browser. They cross-link via relative filenames, so keep them in the same folder.

```bash
# Or serve with any static server
python -m http.server 8000
# then open http://localhost:8000/oneinvest.html
```

## Personas

- **Aarav (New, 24)** — first ₹10K bond. Plain English, calm waits.
- **Priya (Moderate, 34)** — ₹1L allocations. Comparisons, alternatives, control.
- **Rohan (Advanced, HNI, 47)** — ₹25L tickets. ISIN, YTM, modified duration, raw data.

## Journeys

1. **Success** — Apply → UPI mandate → bank confirms → allotted → portfolio.
2. **Stuck** — UPI mandate sent, bank slow. Live tranche fill % + AI bank-health warning + Plan B card.
3. **Failed** — Tranche closed before confirmation. 2-hour refund, AI-ranked alternatives, priority queue for next.

## AI thesis

AI does: demand prediction, bank-health monitoring, fraud-cluster detection, alternative ranking, persona-aware copy.

AI does not: allotment, eligibility/KYC, interest-rate setting, refund processing, suitability gating.

> "AI is the ranking engine. Rules are the gate."

---

Drafted as an AI Product Manager artefact · 19 Jun 2026
