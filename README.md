# Canadian Big Six Banks: CEO Compensation Benchmarking (FY2025)

An independent benchmarking study of fiscal 2025 CEO compensation at Canada's six largest banks, built from each bank's 2026 management proxy circular and 2026 shareholder voting results.

**Author:** Yuxin (Cindy) Wang  
**Date:** August 2026

## Deliverables

| File | Description |
| --- | --- |
| `Big_Six_CEO_Compensation_FY2025_Yuxin_Wang.pdf` | 12-slide board-style presentation of findings |
| `Big_Six_CEO_Compensation_FY2025_Model.xlsx` | Excel benchmarking model: raw inputs with page references, live calculations, P25/P50/P75 peer summary, chart data and verification log |

## Key findings

1. **Pay level vs. scale.** RBC's CEO earned the highest actual total direct compensation (TDC) at $22.1M, 1.52× the $14.6M peer median, yet ranked second-lowest on pay per $1B of adjusted net income. National Bank ranked highest on that measure (~2.7× RBC).
2. **What drives year-over-year change.** BMO's CEO TDC rose 60.5%, driven largely by a deliberate increase in target pay to $15.0M effective May 1, 2025, not performance alone. RBC's change was −9.5% as reported but +8.2% excluding a $4.0M FY2024 special award.
3. **Design converges, discretion diverges.** All six banks deliver CEO long-term incentives only through performance share units and stock options (no RSUs), and at-risk pay is 91–94% of TDC. Yet annual incentive decisions range from fully formulaic (BMO) to a committee adjustment (TD, +7.1 pp) to non-formulaic (RBC).

## Methodology

- **Population:** FY2025 CEOs of RBC, TD, Scotiabank, BMO, CIBC and National Bank (fiscal year ended October 31, 2025).
- **Actual TDC:** salary + annual incentive + share-based awards + option-based awards, from each bank's Summary Compensation Table. Excludes pension and other compensation.
- **Peer statistics:** P25 / P50 / P75 calculated with `PERCENTILE.INC`.
- **Scale measure:** CEO TDC per $1B of FY2025 adjusted net income.
- **Year-over-year:** same incumbent only; shown as reported and excluding disclosed special awards.
- **Data treatment:** TD's CEO was appointed February 1, 2025 (partial year, year-over-year not meaningful); National Bank uses adjusted net income attributable to shareholders; BMO's target pay changed mid-year.
- **Checks:** every Summary Compensation Table row reconciles to the disclosed total; every input carries a printed-page reference.

## Workbook structure

| Sheet | Contents |
| --- | --- |
| `1_README` | Scope, units, definitions and footnotes |
| `2_Raw_Data` | Inputs only, with source page references |
| `3_Calc` | Live formulas: TDC, reconciliation checks, pay mix, year-over-year, pay per $1B |
| `4_Peer_Summary` | Peer comparison with P25 / P50 / P75 and percentile ranks |
| `5_Charts` | Chart source tables and charts |
| `6_QA_Log` | Data-point verification log |
| `7_Issues` | Methodology decisions and disclosure caveats |

## Sources

- 2026 management proxy circulars: [RBC](https://www.rbc.com/investor-relations/_assets-custom/pdf/2026englishproxy.pdf), [TD](https://www.td.com/content/dam/tdcom/canada/about-td/pdf/td-investor-2026-proxy-en.pdf), [Scotiabank](https://www.sec.gov/Archives/edgar/data/9631/000119312526101156/d121533dex991.htm), [BMO](https://www.bmo.com/ir/files/F26%20Files/BMOProxy_March2026.pdf), [CIBC](https://www.cibc.com/content/dam/cibc-public-assets/about-cibc/investor-relations/pdfs/annual_meetings/management-proxy-circular-2026-en.pdf), [National Bank](https://www.nbc.ca/content/dam/bnc/a-propos-de-nous/relations-investisseurs/assemblee-annuelle/2026/nbc-circular-2026.pdf)
- 2026 annual meeting voting results for each bank
- Laulima Consulting, *TSX60 Research – Executive Pay Insights* (June 2026), used for TSX60 RSU prevalence

## Disclaimer

Independent analysis based solely on public disclosures. Not affiliated with, or endorsed by, any of the companies named. All amounts in CAD.
