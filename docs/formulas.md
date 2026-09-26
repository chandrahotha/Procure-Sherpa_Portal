# Formulas & Benchmarks Reference

The math behind every Procure Sherpa calculator — in one place, with guidance on how to read each number. Handy when you need to defend a figure in a negotiation or review meeting.

---

## Cost & Quotes

| Formula / benchmark | Where it applies | How to read it |
|---------------------|------------------|----------------|
| **Landed cost = FOB + freight + duty + insurance + clearance + inland** | Landed Cost | Always compare quotes on landed, not FOB — a 3% cheaper FOB quote loses to a 1% cheaper all-in quote |
| **Should-cost = material + labour + overhead + margin** | Should Cost | Build it bottom-up from BOM weight × commodity rates. If the quote exceeds should-cost by > 15%, demand a cost breakdown |
| **TCO = acquisition + operations (energy, spares, maintenance) + downtime + disposal − residual** | TCO | For equipment, operations typically dominate — a machine 20% cheaper to buy is often 40% costlier to own over 5 years |
| **EOQ = √(2DS ÷ H)** | Order Quantity | D = annual demand, S = order/setup cost, H = holding cost per unit/year. Order above EOQ only with a price break — check discount vs added carrying cost |
| **Safety stock = Z × σd × √LT** | Order Quantity | Z = service level factor (90% → 1.28, 95% → 1.65, 99% → 2.33), σd = demand variability, LT = lead time in matching units. Higher service levels cost superlinearly — 99% is rarely worth it for C-class items |
| **Reorder point = (avg demand × lead time) + safety stock** | Order Quantity | The trigger line for replenishment. Reordering after stock-out instead of at ROP means paying for expediting twice |

---

## Negotiation

| Formula / benchmark | Where it applies | How to read it |
|---------------------|------------------|----------------|
| **Savings % = (baseline − actual) ÷ baseline × 100** | Negotiation Savings | Fix the baseline definition *before* the negotiation starts. Hard savings hit the P&L; soft savings (cost avoidance) don't — report them separately |
| **2/10 net 45 → annualized ≈ 37%** | Payment Terms | Discount % ÷ (100 − discount %) × 365 ÷ (net days − discount days). Early-payment discounts beat almost any credit line — take them if cash allows |
| **Price-variance = (new price − old price) × actual volume; volume-variance = (actual volume − budgeted volume) × old price** | Budget vs Actual | Separates "we paid more" from "we bought more" — the first is a negotiation issue, the second is a planning issue |

---

## Supplier & Risk

| Formula / benchmark | Where it applies | How to read it |
|---------------------|------------------|----------------|
| **HHI = Σ(market share %)²** | Supplier Concentration | HHI < 1,500 = unconcentrated; 1,500–2,500 = moderate; > 2,500 = highly concentrated. A single supplier above ~40% share is a dual-sourcing trigger regardless of HHI |

---

## Tax & Compliance (India)

| Formula / benchmark | Where it applies | How to read it |
|---------------------|------------------|----------------|
| **TDS under IT Act: 194C (works) 1%/2%, 194J (professional) 10%, 194I (rent) 10%** | Invoice review | Verify TDS section and rate on every vendor invoice before payment release — wrong section = notice later |

---

## Incoterms quick reference

Quote comparisons depend on the delivery term — never compare across different Incoterms on price.

| Incoterm | Buyer pays for | Quote comparison note |
|----------|----------------|----------------------|
| **EXW** | Everything from supplier's dock | Lowest headline price, highest hidden cost — always convert to landed before comparing |
| **FOB** | Ocean freight + insurance + import clearance | The standard comparison basis for imports |
| **CIF** | Only import clearance + inland | Supplier-chosen freight can be padded — request the freight invoice copy |
| **DDP** | Nothing until delivery | Highest headline price, lowest risk — best for comparing true total cost |

**Rule of thumb:** normalize to landed cost first, then compare.

---

*Part of [Procure Sherpa](https://procuresherpa.vercel.app) — free, no install, no login, your data never leaves your device.*
