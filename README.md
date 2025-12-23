# City Size vs Restaurant Success

## Overview
This project examines whether **city size affects restaurant success** using Zomato restaurant data merged with Indian city population data. Restaurant performance is evaluated through **ratings** and **customer engagement (votes)** across different city tiers.

---

## Objective
To compare restaurant success across:
- Tier 1 (large cities)
- Tier 2 (mid-sized cities)
- Tier 3 (small cities)

and determine which city size offers the most favorable conditions for success.

---

## Data & Methodology
- Cleaned and standardized both datasets
- Categorized cities into tiers based on population
- Merged datasets using cleaned city names
- Defined success levels using rating thresholds
- Conducted tier-wise statistical and visual analysis

---

## Key Findings
- Tier 2 cities achieve the highest average ratings and customer engagement
- Tier 1 cities show reduced average success due to high competition
- Tier 3 cities display lower engagement and inconsistent performance

---

## Conclusion
City size has a measurable impact on restaurant success.  
**Mid-sized (Tier 2) cities offer the best balance between demand and competition**, making them the most favorable for restaurant performance.

---

## Project Structure
city-size-vs-restaurant-success/
│
├── notebooks/
│ ├── 01_city_cleaning.ipynb
│ ├── 02_zomato_cleaning.ipynb
│ └── 03_city_size_vs_success_analysis.ipynb
│
├── data/
│ ├── raw/
│ └── cleaned/
│
└── README.md

---

## Tools Used
- Python
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## Author
**Aditya Sharma**
