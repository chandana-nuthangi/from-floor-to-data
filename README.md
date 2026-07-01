# From Floor to Data — Warehouse Operations Analytics

End-to-end analytics pipeline for warehouse operations, built on simulated data
modeling real-world logistics patterns. Combines data quality validation,
short-term demand forecasting, and an interactive dashboard.

🔗 **Live dashboard:** [from-floor-to-data-5l6icpyuuxapolnh9i6qtk.streamlit.app](https://from-floor-to-data-5l6icpyuuxapolnh9i6qtk.streamlit.app/)

👩‍💻 Part of my **from-floor-to-data** portfolio — warehouse operations experience
(Amazon, Kuehne+Nagel) meets data analytics.

---

## What it does

Warehouse operations generate a constant stream of volume, shift, and event data —
but raw data is rarely analysis-ready. This project simulates that environment and
builds the full pipeline from messy data to decision-ready output:

1. **Data quality pipeline** — automated validation checks (missing values, outliers,
   schema consistency) before any analysis runs on the data.
2. **28-day volume forecasting** — Holt-Winters exponential smoothing to forecast
   warehouse volume, capturing trend and seasonality.
3. **Interactive operations dashboard** — live, explorable view of volume trends,
   forecasts, and data quality metrics.

## Data

This project uses **simulated warehouse data**, generated to reflect realistic
operational patterns (shift cycles, volume seasonality, event-level granularity)
rather than a public dataset or real company data.

## Tech stack

Python · Pandas · Statsmodels (Holt-Winters) · Streamlit · Matplotlib/Plotly

## Repository structure
