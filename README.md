# Bank Marketing — EDA & Storytelling Dashboard

Individual project: an interactive R/Shiny report auditing and cleaning a bank marketing
campaign dataset, then turning the findings into two concrete business recommendations.

## Open this first
- [`bank_marketing_eda.Rmd`](./bank_marketing_eda.Rmd) — the R Markdown source (interactive,
  `runtime: shiny`).
- [`bank_marketing_eda.html`](./bank_marketing_eda.html) — the rendered report; open
  directly in a browser (download it first — GitHub doesn't render `.html` files inline).

## What it covers
1. **Data quality & preprocessing** — missing values, duplicates, inconsistent categories,
   and outliers (3×IQR rule), then cleaned (capping, median/mode imputation).
2. **Relationship analysis** — correlation, cross-tabulation, and feature engineering
   (age groups, contact recency, call-duration buckets).
3. **Storytelling & recommendations** — interactive Plotly charts plus two targeting
   recommendations grounded in the numbers below.

## Key findings
- Clients with a prior campaign **success** convert at **72%**, vs 23% (prior failure) and
  13% (never contacted).
- Calls **over 5 minutes** convert at **29.4%** — nearly 3x the 10.9% rate for 3–5 minute
  calls.

No dataset is committed here.
