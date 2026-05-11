# Flowbit — Financial Control Architecture for Cash

**Every ERP overstates cash by 25–35%. We prove them wrong first.**

Flowbit is a financial control architecture that gives CFOs real-time visibility into their actual cash position — not what the accounting system says, but what's really spendable.

## Live Demo

Open `index.html` in any browser — no build step needed.

Or deploy to GitHub Pages:
1. Push this repo
2. Go to Settings → Pages → Source: `main` / `root`
3. Your dashboard is live at `https://yourusername.github.io/flowbit/`

## What This Shows

### ◉ Executive Layer
- **Cash Position** — Actual (cashflow) vs. Book (ERP) side by side, per category
- **$30M Cash Gap** — breakdown of where the money is trapped
- **Revenue Quality Score** — 0-100 composite (margin, DSO, collection probability, concentration, trend)
- **Prediction Accuracy** — learning feedback loop tracking ±22% → target ±5%
- **Days of Survival** — normal / stress / perfect storm with interactive degradation slider
- **Stress Test** — 3 interactive shock sliders × covenant breach × off-balance-sheet liabilities

### ◎ Analytical Layer
- **Customer Intelligence** — risk scoring 0-100, whale curve, true margin per contract, pricing power
- **Supplier Intelligence** — free credit optimization, payment timing, concentration risk
- **Dead Money** — 5 categories of trapped capital + recovery recommendations
- **P&L** — accrual vs. cash-adjusted (52% gap), CCC optimization per segment, inventory DIO, variance feedback

### ◌ Specialist Layer
- **Balance Sheet & Ratios** — full breakdown with 16 financial ratios across 4 categories
- **Growth Capacity** — sustainable rate modeling, true cost per $1 revenue per segment
- **Decision Simulator** — "Hire 20 people?" → instant liquidity impact + recommendations
- **Control Engine** — 5 automated pre-approval checks (like CI/CD gates for finance)
- **Causal Graph** — visual chain: customer delay → liquidity drop → covenant breach → payroll risk

## Data Sources

Dashboard shows sync badges for connected data sources:
- **ERP Synced** — reads from your accounting system (Odoo, SAP, NetSuite, etc.)
- **Bank Connected** — real-time bank feed for actual cash position

## Tech Stack

Zero build step — pure React + Recharts loaded from CDN via Babel standalone.

- React 18.3
- Recharts 2.12
- DM Sans (Google Fonts)

## The Core Thesis

> Domain knowledge without engine = spreadsheet.
> Engine without domain knowledge = ChatGPT for finance.
> Both = Flowbit.

Built by a CFO with 40 years across 4,000+ companies who got tired of every tool giving him the wrong numbers.

---

**Flowbit** · [flowbit.io](https://flowbit.io)
