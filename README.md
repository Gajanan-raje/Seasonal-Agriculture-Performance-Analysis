# Seasonal-Agriculture-Performance-Analysis
VOIS AICTE Major Project - Seasonal Agriculture Performance Analysis
Seasonal Agriculture Performance Analysis
VOIS AICTE Major Project | Batch 1, 2026-2027

👤 Submitted By
Name: Gajanan Harinarayan Raje
College: MGM's College of Computer Science & IT, Nanded
Course: BCA (5th Semester), SRTMU University

📌 Project Overview
This project analyzes seasonal agricultural performance using a dataset of 4000 farm records spread across 8 states, 8 crops, and 3 farming seasons (Kharif, Rabi, Zaid). The goal is to identify meaningful patterns, trends, and relationships in agricultural performance across seasons using data analytics.

📂 Repository Structure


├── dataset/

│   ├── seasonal_agriculture_performance_dataset.csv   # Original dataset

│   └── cleaned_seasonal_agriculture_data.csv          # Cleaned dataset

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

│   └── VOIS_Major_Project_PPT_Submission.pptx

├── docs/

│   └── Major_Project_Seasonal_Agriculture_Performance_Analysis.pdf

└── README.md


🎯 Objective
Explore and clean the seasonal agriculture dataset
Compare agricultural performance (yield, profit, resource usage) across seasons
Identify seasonal patterns, trends, and relationships
Apply statistical testing to validate findings
Provide data-driven insights and recommendations

🛠️ Tools & Technologies
Language: Python
Platform: Google Colab (Jupyter Notebook)
Libraries: Pandas, NumPy, Matplotlib, Seaborn, SciPy

🔍 Methodology
Data Cleaning — Handled missing values (Rainfall, Soil Moisture, Yield) using season-wise median imputation; checked for duplicates
Exploratory Data Analysis (EDA) — Explored dataset structure and summary statistics
Seasonal Comparison — Compared yield, profit, water usage, fertilizer/pesticide use, and disease risk across seasons
Visualization — Created 9 visualizations (boxplots, violin plots, bar charts, heatmaps)
Statistical Testing — Applied ANOVA to test significance of yield differences across seasons

📊 Key Findings
Season
Avg Yield (t/ha)
Avg Profit (₹)
Disease Risk (%)
Kharif
5.63
1,78,915
54.47
Rabi
5.04
87,689
40.48
Zaid
4.64
-24,805
38.22
Kharif season shows the highest yield and profit
Zaid season runs at an average loss despite the highest water usage
Sugarcane is the top-yielding crop across all seasons
ANOVA test (F = 1.554, p = 0.212) shows the seasonal yield difference is not statistically significant

💡 Recommendations
Re-evaluate cost structure and crop choice for Zaid season farming
Review fertilizer/pesticide application efficiency, especially in low-yield seasons
Strengthen disease/pest management during Kharif season
Promote Sugarcane cultivation where feasible
Improve water-use efficiency in Zaid season
