# 🏠 Inside Airbnb Berlin
### A collaborative marketing data analytics project

![Python](https://img.shields.io/badge/Python-3.10+-3776AB?style=flat&logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?style=flat&logo=jupyter&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-Data%20Wrangling-150458?style=flat&logo=pandas&logoColor=white)
![statsmodels](https://img.shields.io/badge/statsmodels-OLS%20Regression-4B8BBE?style=flat)
![Tableau](https://img.shields.io/badge/Tableau-Visualization-E97627?style=flat&logo=tableau&logoColor=white)

---

## 📋 Project Overview

> This project explores the Berlin Airbnb market using the Inside Airbnb dataset.
> Two independent marketing-focused analyses were conducted in parallel, covering
> suspected violations of Berlin's 90-day short-term rental cap and [Angle 2].

---

## 📦 Dataset

**Source:** [Inside Airbnb](https://insideairbnb.com/get-the-data/) — Berlin, Germany
**License:** [Creative Commons Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/)
**Snapshot date:** [September, 2025]

> The dataset contains **14,274** listings across 12 Berlin districts with **75** attributes
> covering pricing, host behavior, availability, reviews, and amenities.

---

## 📁 Repository Structure

```
inside-airbnb-berlin/
│
├── Dashboards
│   └──Inside_AirBnB.twbx
|
├── Data
│   └── [raw data files]            <- not pushed to GitHub
│
├── Notebooks
│   ├── 01_Selma_overview.ipynb
│   └── 02_Selma_90dayslimit.ipynb
|   └── berlin_airbnb_market_overview
│   └──booking_demand_analysis
│
├── Plotting_output
│   ├── berlin_airbnb_market_overview
│   └── booking_demand_analysis
│   └── SelmasPlots
│       └── 00_overviews
│       └── 01_occupancy
│
└── README.md
```

---

## 🔍 Analysis Angles

Two independent analyses were conducted on the same dataset, each approaching
the Berlin Airbnb market from a distinct marketing perspective.

---

### Angle 1 — Berlin's 90-day short-term rental cap
**Analyst:** Selma Esders

> This project investigates how many of Berlin's ~14,000 Airbnb listings likely violate the city's 90-day short-term rental cap (Zweckentfremdungsverbot). Using Inside Airbnb data, it combines room type, minimum stay, host portfolio, and estimated occupancy to flag suspected offenders and map where they cluster across the city's 12 districts. Built as an interactive Tableau dashboard, it turns open data into a practical lens on Berlin's housing shortage.<

| | |
|---|---|
| **Focus** | Regulatory compliance analysis |
| **Methods** | Cumulative distribution (ECDF), proportional analysis, box plots (log scale), geospatial mapping  |
| **Key tools** | Python · pandas · statsmodels · matplotlib · seaborn · Tableau Public |
| **Notebook** | 02_Selma_90dayslimit (\Notebooks) |
| **Tableau** | Inside_AirBnB.twbx (\Dashboards\) |

**Key findings:**
- Of all active listings, 24 % are booked beyond Berlin's 90-day limit, with entire homes run by multi-listing hosts forming the strongest violation suspects.
- Mitte, Pankow, and Friedrichshain-Kreuzberg show the highest share of suspected violations relative to their active listings — where inspections would most likely score a hit.
- Median estimated revenue rises as listings move closer to a suspected violation, partly reflecting higher-earning traits (entire homes, high occupancy) being filtered in.

---

### Angle 2 — [Analysis Title]
**Analyst:** [Colleague's Name]

> [2–3 sentences describing what this angle investigates, the marketing
> question it answers, and why it matters from a business perspective.]

| | |
|---|---|
| **Marketing focus** | [e.g. Demand generation / Pricing strategy / Brand equity] |
| **Methods** | [e.g. Method 1, Method 2, Method 3] |
| **Key tools** | [Tools used] |
| **Notebook** | [`[notebook-name].ipynb`]([path/to/notebook]) |

**Key findings:**
- [Placeholder finding 1]
- [Placeholder finding 2]
- [Placeholder finding 3]

---

## 👥 Contributors

| Analyst | Analysis Angle | Focus Area |
|---|---|---|
| Selma Esders | Berlin's 90-day short-term rental cap | Regulatory compliance analysis |
| [Colleague's Name] | [Angle 2 Title] | [Marketing focus] |