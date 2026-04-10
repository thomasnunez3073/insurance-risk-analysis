# Insurance Risk Analysis

> Identifying high-risk insurance profiles to understand the key drivers of medical cost.

## Stack
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat&logo=sqlite&logoColor=white)
![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=flat&logo=powerbi&logoColor=black)
![Pandas](https://img.shields.io/badge/pandas-150458?style=flat&logo=pandas&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat&logo=scikit-learn&logoColor=white)

## Key Findings
- **Smoking is the dominant factor**: smokers pay 4× more on average ($32,050 vs $8,434)
- **Obesity amplifies smoking**: obese smokers average $41,558 — the highest-risk segment
- **BMI alone has low impact**: correlation of 0.20 with charges vs 0.79 for smoking
- **Southeast is the most expensive region**: highest BMI average and 25% smoker rate
- **Linear Regression R² = 0.78**: smoker status adds ~$23,848 to predicted cost alone

## Dashboard
![Dashboard](Insurance%20Risk%20Analysis.png)

## Project Structure
- `01_EDA_insurance.ipynb` — exploratory data analysis (pandas, matplotlib, seaborn)
- `02_SQL_insurance.ipynb` — risk segmentation queries (SQLite)
- `03_modeling_insurance.ipynb` — predictive model (scikit-learn, Linear Regression)
- `Insurance Risk Analysis.png` — Power BI dashboard
- `insurance.csv` — raw dataset

## Dataset
[Medical Cost Personal Dataset](https://www.kaggle.com/datasets/mirichoi0218/insurance) — 1,338 records, 7 variables.
