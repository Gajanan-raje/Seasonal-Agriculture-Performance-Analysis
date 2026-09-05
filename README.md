# Seasonal-Agriculture-Performance-Analysis

**VOIS AICTE Major Project — Seasonal Agriculture Performance Analysis**

This project was completed as part of the **VOIS for Tech Program on Data Analytics**, a CSR initiative by **VOIS and Vodafone Idea Foundation** — a 4-Week Virtual Internship on Data Analytics.

Seasonal Agriculture Performance Analysis | Batch 1, 2026-2027

## 👤 Submitted By
- **Name:** Gajanan Harinarayan Raje
- **College:** MGM's College of Computer Science & IT, Nanded
- **Course:** BCA (5th Semester), SRTMU University

## 📌 Project Overview
**Dataset Size:** 4000 farm records × 28 columns, covering 8 states, 8 crops, and 3 farming seasons (Kharif, Rabi, Zaid).

This project analyzes seasonal agricultural performance data, covering environmental conditions, farming inputs, resource usage, and economic outcomes. The goal is to identify how agricultural performance varies across seasons and provide data-driven insights for farmers, agricultural officers, and policymakers.

## 📂 Repository Structure
```
├── dataset/
│   ├── seasonal_agriculture_performance_dataset.csv
│   └── cleaned_seasonal_agriculture_data.csv
├── notebook/
│   └── VOIS_Major_Project_Seasonal_Agriculture_Analysis.ipynb
├── graphs/
│   ├── 01_yield_boxplot.png
│   ├── 02_avg_profit_by_season.png
│   ├── 03_rainfall_temperature.png
│   ├── 04_water_usage_efficiency.png
│   ├── 05_fertilizer_pesticide_disease.png
│   ├── 06_crop_yield_heatmap.png
│   ├── 07_correlation_heatmap.png
│   ├── 08_irrigation_method_yield.png
│   └── 09_top_states_profit.png
├── presentation/
│   └── VOIS_Major_Project_Seasonal_Agriculture_Analysis_Gajanan_Raje.pptx
├── docs/
│   └── Major_Project_Seasonal_Agriculture_Performance_Analysis.pdf
└── README.md
```

## 🎯 Objective
- Explore and clean the seasonal agriculture dataset
- Compare agricultural performance (yield, profit, resource usage) across seasons
- Identify seasonal patterns, trends, and relationships
- Apply statistical testing to validate observed differences
- Provide data-driven insights and recommendations for seasonal planning

## 🛠️ Tools & Technologies
- **Language:** Python
- **Platform:** Google Colab (Jupyter Notebook)
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, SciPy

## 🔍 Methodology
1. **Data Cleaning** — Handled missing values (Rainfall, Soil Moisture, Yield) using season-wise median imputation; checked for duplicates
2. **Exploratory Data Analysis (EDA)** — Explored dataset structure and summary statistics
3. **Seasonal Comparison** — Compared yield, profit, water usage, fertilizer/pesticide use, and disease risk across seasons
4. **Visualization** — Created 9 visualizations (boxplots, violin plots, bar charts, heatmaps)
5. **Statistical Testing** — Applied ANOVA to test whether seasonal yield differences are statistically significant

## 📊 Key Findings
| Season | Avg Yield (t/ha) | Avg Profit (₹) | Disease Risk (%) |
|--------|------------------|-----------------|-------------------|
| Kharif | 5.63 | 1,78,915 | 54.47 |
| Rabi | 5.04 | 87,689 | 40.48 |
| Zaid | 4.64 | -24,805 | 38.22 |

- **Kharif** season shows the highest yield and profit among all three seasons
- **Zaid** season runs at an average **loss** despite the highest water usage (6419.89 m³)
- **Sugarcane** is the top-yielding crop across every season
- Yield declines consistently from Kharif → Rabi → Zaid for every crop in the dataset
- ANOVA test (F = 1.554, p = 0.212) shows the seasonal yield difference is **not statistically significant**

## 💡 Recommendations
- Re-evaluate cost structure and crop selection for Zaid season farming, given its net loss
- Review fertilizer/pesticide application efficiency, especially where yield is falling
- Strengthen disease and pest management efforts during Kharif season
- Promote Sugarcane cultivation in regions where it is feasible
- Improve water-use efficiency in Zaid season, where usage is high but returns are low
