# MIT 805 — Big Data Semester Project (2026)

Group project for MIT 805, analyzing the **NY Yellow Taxi** dataset.

## Overview

This project works through the full big-data pipeline dataset:
- Collecting and describing a large public dataset
- Exploratory data analysis and evaluation against the 7 Vs of Big Data
- MapReduce-style distributed processing implemented in PySpark
- Visualization of results and discussion of business/societal value

## Dataset

- **Source:** New York City Taxi and Limousine Commission (TLC), via the official TLC Trip Record Data page (https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page)
- **Contents:** Yellow Taxi trip records covering the period 2014-2026, including vendor ID, pickup/dropoff timestamps and locations, passenger count, trip distance, fare and payment details, and rate code. Two derived variables — trip duration (hours) and average trip speed (mph) — were added during cleaning.
- **License:** Data provided by the TLC is publicly available as open data
- **Note:** This analysis used a 30% random sample of the cleaned dataset (seed=42) for computational feasibility
  
## Repository Structure

```
project/
│
├── README.md             # This file
├── requirements.txt      # Python / PySpark dependencies
├── data/
│   └── README.md         # Dataset source, license, download & reproduction instructions
├── notebooks/            # EDA and processing notebooks
├── src/                  # Reusable scripts and modules
├── output/               # Generated tables and intermediate results
├── figures/              # Plots and visualizations used in the report
└── report/               # Written report(s) — Part 1 and Part 2 PDFs
```


## Project Status

| Part | Description | Due Date | Status |
|---|---|---|---|
| Part 1 | Data Collection & Analysis | 03-09-2026 | In progress |
| Part 2 | MapReduce & Visualization | 08-10-2026 | Not started |

## Group Members

- [Name 1] — Savannah Canto
- [Name 2] — Mekayle Rajoo
