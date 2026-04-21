# 📊 India CPI Inflation Analysis (2013–2023)

## 📌 Project Overview
This project analyzes India's Consumer Price Index (CPI) data published by the National Statistical Office (NSO). The goal was to uncover key inflation trends, identify the impact of major events like COVID-19 and the Russia-Ukraine war, and understand how global oil prices influence domestic inflation.

---

## 🛠️ Tools Used
- Microsoft Excel
  - SUMIF, AVERAGEIFS, CORREL formulas
  - Pivot-style analysis
  - Line, Bar and Pie charts

---

## 📂 Dataset
- **Source:** National Statistical Office (NSO), India
- **Period:** January 2013 – May 2023
- **Rows:** 372 | **Columns:** 30
- **Sectors:** Rural, Urban, Rural+Urban

---

## ❓ Problem Statements Solved

### Q1 — CPI Basket Contribution Analysis
- Grouped 24 sub-categories into 6 broader buckets
- Calculated contribution % of each bucket to CPI basket
- **Finding:** Food = 49.61% — highest contributor

### Q2 — Year-on-Year Inflation Trend (2013–2023)
- Calculated yearly average CPI and Y-o-Y growth %
- Created line chart to visualize inflation trend
- **Finding:** 2022 had highest inflation at 6.62% due to Russia-Ukraine war

### Q3 — Food Inflation Trend (Jun 2022 – May 2023)
- Analyzed month-on-month food price changes
- Identified biggest individual food category contributor
- **Finding:** October 2022 had highest MoM inflation (+1.01%) | Spices had biggest absolute change (+30.9)

### Q4 — COVID-19 Impact on Inflation
- Compared Pre COVID, COVID Onset and Post COVID inflation
- Focused on Food, Health and General index
- **Finding:** Health inflation rose 25.47% post COVID — highest among all categories

### Q5 — Oil Price & CPI Correlation Analysis
- Analyzed Fuel & Light index MoM changes (2021–2023)
- Used CORREL function to find which category moves most with oil prices
- **Finding:** Footwear had strongest correlation (0.987) — petroleum based raw materials

---

## 📈 Key Findings Summary

| Finding | Value |
|---|---|
| Highest CPI contributor | Food (49.61%) |
| Highest inflation year | 2022 (6.62%) |
| Highest MoM food inflation month | October 2022 (+1.01%) |
| Biggest food sub-category change | Spices (+30.9 points) |
| Most COVID impacted category | Health (+25.47%) |
| Strongest oil price correlation | Footwear (0.987) |

---

## 📁 File Structure
```
CPI-Inflation-Analysis/
│
├── CPI_Case_Study.xlsx        # Main Excel analysis file
├── README.md                  # Project documentation
└── screenshots/               # Charts and visuals
    ├── Q1_contribution_pie.png
    ├── Q2_yoy_trend.png
    ├── Q3_food_mom_trend.png
    ├── Q4_covid_impact.png
    └── Q5_oil_correlation.png
```

---

## 💡 Learnings
- Data cleaning using Find & Replace
- Cross-sheet formula referencing in Excel
- Contribution % analysis
- Time-series trend analysis
- Statistical correlation using CORREL function
- Professional data visualization

---

## 🙋 About Me

 
Data Analyst passionate about turning raw data into meaningful insights.
Currently learning: Excel | SQL | Python | Power BI

📧 Connect with me on LinkedIn: www.linkedin.com/in/sourabh-sharma-17b706246
# CPI-Inflation-Analysis-Excel
