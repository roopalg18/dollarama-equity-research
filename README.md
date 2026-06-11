# Dollarama Inc. (TSX: DOL) - Initiating Coverage

An independent equity research initiating-coverage note on **Dollarama Inc. (TSX: DOL)**, built end to end: company analysis, financial model, DCF and comparable-company valuation, rating, price target, risks, and catalysts.

**Rating: MARKET PERFORM · Target: C$153 · Last close: C$179.57 (June 10, 2026, −14.6% implied) · Street consensus: C$197.81 (Buy)**

## What's in this repo
| File | Description |
|---|---|
| `Dollarama_Initiating_Coverage.html` | The full research note (open in a browser) |
| `dol_valuation_model.py` | Reproducible Python DCF + comps + sensitivity model |
| `README.md` | This file |

## Reproduce the valuation
```bash
python3 dol_valuation_model.py
```
This prints the financial summary, the DCF free-cash-flow build, the comps table, a WACC × terminal-growth sensitivity grid, and the blended target and rating.

## Methodology and sources
- **Historical financials:** Dollarama's publicly reported Q4 and full-year results (FY ended Jan 28 2024, Feb 2 2025, and Feb 1 2026) and SEDAR+ filings.
- **Market data:** last close C$179.57 on June 10, 2026, ~270.8M shares outstanding, and a C$197.81 mean consensus target, all from publicly reported quotes.
- **Forward estimates** (revenue growth, margins, 8.0% WACC, 3.0% terminal growth, 32x target multiple, 35/65 DCF/comps weighting) are the author's own assumptions and are labelled as such in the code.

## Summary of the call
1. Dollarama is the most profitable retail format in Canada (~45% gross / ~27% operating margin) with a long runway of new stores.
2. International (Dollarcity, Australia) is upside optionality, not base-case earnings, while Mexico and Australia are still loss-making.
3. The caution is valuation, not quality. At ~35x forward earnings there is little margin of safety, which is why the target sits below consensus.

> Educational project. Not investment advice.

Author: **Roopal

## Related work
See also: [`dollarama-wc-analysis`](https://github.com/roopalg18/dollarama-wc-analysis) — a separate working-capital efficiency study on the same company.
