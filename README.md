
# pzza-take-private-model# Papa John's (PZZA) — Take-Private Model & Bid Post-Mortem

An 8-tab operating model, DCF and LBO built to answer one question: **why did Apollo Global's $64.00/share take-private bid disappear, and what is Papa John's equity actually worth without it?**

Built independently as a valuation exercise. Not investment advice.

---

## The short version

In October 2025, Apollo bid **$64.00 per share in cash** for Papa John's — a 33% premium to the undisturbed price and 13.8x the EBITDA the company was then guiding to. Apollo withdrew within weeks. As of 6 August 2026 the stock trades at **$27.47**.

That is a **$36.53 per share decline**. The model decomposes it:

| | $ / share |
|---|---|
| Equity value at Apollo's bid | **64.00** |
| EBITDA guidance cut ($205mm → $185mm), held at 13.8x | (8.36) |
| Multiple de-rating (13.8x → 8.9x) | **(27.64)** |
| Increase in net debt | (0.53) |
| Equity value today | **27.47** |

**Three quarters of the loss is multiple de-rating, not the earnings miss.** The market didn't just mark down the earnings — it withdrew a takeout premium and re-rated the asset from "franchised pizza platform in play" to "structurally challenged QSR with negative comps, no unit growth and no dividend."

## Reverse-engineering the bid

Run $64.00 through an ordinary sponsor structure at 5.5x leverage:

- Entry EV **$2,838mm**, debt raised $1,128mm, sponsor equity cheque **$1,805mm — 64% of enterprise value**
- At 13.8x you cannot lever the asset, so returns have to come almost entirely from EBITDA growth
- Clearing a 20% IRR over five years requires **FY2031 EBITDA of $649mm — a 25.9% CAGR, 2.8x the base case**
- Alternatively, at base-case EBITDA, Apollo needed a **22.5x exit**. No franchised pizza chain has ever traded there.

**Conclusion: the $64 bid was never underwritable as an LBO.** It was a strategic price against a turnaround thesis. When diligence showed North America deteriorating rather than stabilising, there was no financial floor to renegotiate down to — which is why Apollo walked rather than re-cut.

## What it's worth

| Methodology | Low | High |
|---|---|---|
| DCF — exit multiple, WACC 7.8%–9.8% | $19.43 | $23.09 |
| DCF — exit multiple 6.5x–7.5x at 8.8% WACC | $19.00 | $23.42 |
| DCF — perpetuity growth | $17.36 | $21.21 |
| Trading comps — 6.0x–8.0x FY27E EBITDA | $12.19 | $23.67 |
| LBO — max price at 20%–15% IRR | $17.72 | $20.38 |
| **Concluded range** | **$12.19** | **$23.67** |

Base-case DCF: **$21.20** (23% below market). Maximum a disciplined sponsor could pay for a 20% IRR: **$17.72** (35% below market).

The DCF and the LBO converge on the high teens to low twenties **from opposite directions** — the intrinsic value of the cash flows and the most a leveraged buyer could rationally pay land in the same place. That is the strongest signal in the work.

## Why no sponsor comes back

A 30% premium today ($35.71) is a **10.4x entry** against a stock already at 8.9x. Exit at 7.5x in five years and the sponsor earns **(0.9)%**. Even holding the multiple flat entry-to-exit, the IRR is only **10.4%** — the arithmetic, not the exit assumption, is the blocker. $1.0bn of debt at a blended ~8.4% consumes $85mm of a $190mm EBITDA base, so the asset deleverages from 5.3x only to 3.5x over five years.

---

## Repository contents

| File | Description |
|---|---|
| `PZZA_take_private_model.xlsx` | 8-tab model — ~700 live formulas, no hardcoded outputs |
| `PZZA_investment_memo.pdf` | 3-page investment memo |

### Model structure

| Tab | Contents |
|---|---|
| **Cover** | Summary, current price, concluded range |
| **Assumptions** | All drivers, with a Bear / Base / Bull scenario switch |
| **Operating Model** | FY2026E–FY2031E revenue, EBITDA, FCF |
| **DCF** | Unlevered FCF, WACC build, exit-multiple and perpetuity-growth methods, sensitivity grids |
| **LBO** | Sources & uses, debt schedule, returns, max-price solve |
| **Trading Comps** | Peer multiple framework |
| **Bid Bridge** | $64.00 → $27.47 decomposition |
| **Football Field** | Valuation range across all five methodologies |

Revenue is derived bottom-up from system-wide sales, unit counts and comparable sales rather than grown off a top-line — Papa John's is 92% franchised (5,509 of 5,978 units), so reported revenue is a capture rate on a sales base the company does not own. Modelling it any other way misstates the operating leverage.

Change the scenario cell on the **Assumptions** tab to flow Bear / Base / Bull through every downstream output.

### Key inputs

| | |
|---|---|
| Shares outstanding (diluted) | 33.1mm |
| Net debt (incl. finance leases) | $736.8mm |
| Net debt / FY26E EBITDA | 4.0x |
| WACC | 8.82% |
| Base-case FY2031E EBITDA | $230mm |

---

## Sources

All figures are drawn from primary filings:

- Papa John's Q2 FY2026 earnings release and Form 10-Q, 6 August 2026
- Papa John's Q4 and full-year 2025 earnings release, 26 February 2026
- Papa John's Form 10-Q for the quarter ended 29 March 2026 (SEC EDGAR)
- Semafor (11 June 2025), Reuters and Seeking Alpha coverage of the Apollo bid and withdrawal
- Hunterbrook, "$PZZA Gate" (November 2025), on the fabricated TriArtisan report

## Limitations

- **Terminal value dominance.** 71% of DCF value sits beyond FY2031. Small changes in the exit multiple move the answer materially.
- **Peer multiples are analyst judgement,** not a live median. The 6.0x–8.0x comps range should be refreshed from a data terminal before being relied on.
- **Deal risk cuts both ways.** Papa John's has attracted two credible approaches in eighteen months. A strategic buyer — who does not need the leverage math to work — breaks the thesis overnight.

---

**Mahmudul Hossain** · B.A. Finance and Management, The City College of New York
[LinkedIn](https://linkedin.com/in/mahmudul-hossain-ccny)

*Independent analytical exercise. Not investment advice. No affiliation with Papa John's International, Apollo Global Management or any party referenced.*
