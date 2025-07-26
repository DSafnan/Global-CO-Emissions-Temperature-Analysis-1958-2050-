# 🌍 Global CO₂ Emissions & Temperature Analysis (1958–2050)

This project explores the relationship between rising carbon dioxide (CO₂) emissions and global temperature change using historical data and visual analytics. It includes complete data preprocessing, statistical analysis, and an interactive Power BI dashboard.

---

## 📊 Dashboard Overview

![Dashboard Preview](dashboard-preview.png)

### Key Features:
- CO₂ concentration and temperature trend analysis (1958–2023)
- Country-wise average temperature visualization
- Interactive filters by year and country
- Scatter plot showing the relationship between CO₂ levels and global temperature
- Period-wise comparison (Pre-1990 vs Post-1990)

---

## 📂 Project Structure
├── data/
│ ├── df_co2.csv # Monthly CO₂ ppm data (filtered for 'World')
│ └── df_temp.csv # Annual temperature anomaly data per country
├── notebooks/
│ ├── data_cleaning.ipynb
│ └── co2_temp_analysis.ipynb
├── powerbi/
│ └── CO2_Temperature_Analysis.pbix
├── README.md

## 📈 Tools & Technologies

- **Python** – Data preprocessing, analysis, and transformation
- **Pandas** – Data wrangling and merging
- **Power BI** – Dashboard creation and storytelling
- **Matplotlib & Seaborn** – Visual validation of insights
- **SQL (optional)** – For future database integration or querying

---

## 🧪 Methodology

1. **Data Cleaning**: Removed nulls, filtered inconsistent years, standardized columns.
2. **Feature Engineering**: Created new columns (e.g., `Avg_CO2_ppm`, `Period`).
3. **Statistical Insight**: Analyzed correlation between CO₂ levels and temperature rise.
4. **Visualization**: Built interactive Power BI dashboard with slicers, trends, and scatter plots.

---

## 🧠 Key Insights

- 📈 A steady increase in both global temperature and CO₂ levels post-1990.
- 🌐 Significant year-over-year correlation observed between emissions and warming.
- 🧪 Outlier detection reveals key climate change acceleration periods.
