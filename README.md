# Cognitively Intact & Happy Life Expectancy in the U.S.

**Authors:** Tony Bardo & Scott Lynch  
**Published in:** *The Journals of Gerontology: Psychological Sciences* (2021) • [Link to Paper](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7813190/)

---

## 🧠 Overview

This project examines the differences between **cognitively intact life expectancy** and **happy life expectancy** in the United States, showing that at age 65, happy life expectancy is ~25% longer and increasing to ~100% by age 85.

---

## 🎯 Objective

- Compare how long older adults live **cognitively intact** vs **happily**.
- Measure the **gap** and how it changes with age.
- Highlight implications for public health, elder care, and policy-making.

---

## 📥 Data

- **Source:** Health and Retirement Study (1998-2014)
- **Privacy:** Fully public and de-identified
- **Link to Data:** https://hrs.isr.umich.edu/about
---

## 🛠 Analytical Workflow

1. **Data Cleaning & Prep**  
   - Loaded age-stratified life tables  
   - Mapped cognitive and happiness categories

2. **Life-Expectancy Calculations**  
   - Calculated separate life expectancies using survival and health status data

3. **Comparative Analysis**  
   - Computed the *absolute and relative* difference in expectancy across age cohorts

4. **Visualization**  
   - Plotted expectancy curves (age 65 → 90) with both cognitive and happiness lines

---

## 📊 Results

- At age 65: **Happy expectancy ≈ 25% longer** than cognitively intact expectancy  
- By age 85: absolute gap remains significant (~X years), underscoring policy concern  
- Visualized in `figures/expectancy_gap.png` for age-specific comparison  

---

## 📂 Repo Structure

.
├── data/
│ └── clean_life_table.csv
├── analysis/
│ ├── calc_expectancy.R
│ └── compare_expectancy.R
├── figures/
│ └── expectancy_gap.png
└── README.md

yaml
Copy
Edit

---

## 🔍 Business Relevance

- Demonstrates end-to-end data pipeline: cleaning, analysis, and visualization  
- Insights support **evidence-based policy** decisions in health and aging  
- Clear example of translating public data into **actionable findings**

---

## 🧩 Tools Used

- R (data wrangling, life-table algorithms, plotting)
- ggplot2 for visuals
- **[Tableau]** (optional interactive dashboard)

