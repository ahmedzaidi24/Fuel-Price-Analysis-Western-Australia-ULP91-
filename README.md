# Fuel Price Analysis – Western Australia (ULP91)

## 🧠 Overview
This repository presents a full-scale **data analytics capstone project** exploring **fuel price fluctuations** in **Western Australia**. Conducted as part of the **Predictive Analytics major at Curtin University**, the project analyzes how metropolitan fuel pricing is affected by local and external factors such as brand positioning, public holidays, weather, economic indicators, and population density.

---

## 🎯 Objective
To identify patterns and determinants of **ULP91 fuel price volatility** across metropolitan regions by integrating multi-dimensional datasets, performing geospatial analysis, and visualizing relationships across temporal and socio-economic variables.

---

## 📁 Project Structure
```
Fuel-Price-Analysis-WA/
├── N1_Cleaning_data.ipynb           # Initial data wrangling and merging
├── N2_Data_Statistics.ipynb         # Descriptive statistics and distributions
├── N3_Trend_Analysis.ipynb          # Price trend over time (year, month, weekday)
├── N4_Regional_Differences.ipynb    # Zone-wise price differences
├── N5_Cluster_Brand_Analysis.ipynb  # Price clustering and spatial brand patterns
├── N6_Brand_Analysis.ipynb          # Brand-wise price comparison and clustering
├── N7_Public_Holidays.ipynb         # Holiday-based price fluctuation analysis
├── N8_Weather_Conditions.ipynb      # Weather patterns vs price variation
├── N9_Interest_Rates.ipynb          # Interest rate trend impact
├── N10_Inflation.ipynb              # CPI vs average fuel prices
├── N11_Taxes.ipynb                  # Fuel excise and taxation analysis
├── N12_Population.ipynb             # Price correlation with population density
├── North of River_station_cluster_map.html # Interactive cluster map
├── SyedZaidi_20972008_Report.pdf    # Final analytical report
├── README.txt                       # Initial project notes
└── Assignmnet_2024S2_SpecificationV1.pdf   # University assessment brief
```

---

## 📍 Key Analyses

### 🧼 Data Cleaning & Setup (N1)
- Merged raw fuel price datasets
- Cleaned nulls, removed duplicates
- Reshaped long-to-wide format for trends and station metrics

### 📊 Descriptive Statistics (N2)
- Computed means, medians, min/max for each year and brand
- Boxplots revealed substantial brand pricing variation

### 📈 Trend Analysis (N3)
- Explored year-to-year and weekday trends
- Found systematic dips on Mondays and peaks before weekends

### 🗺️ Regional Differences (N4)
- Created region-wise breakdown by station
- Used visual heat maps to detect consistent high-price zones

### 🧭 Cluster & Brand Analysis (N5 & N6)
- KMeans clustering used to group similar brands and locations
- Spatial clustering highlighted monopolistic pricing pockets

### 🗓️ Public Holidays (N7)
- Compared week-before, week-of, and week-after average prices
- Statistical testing showed pre-holiday surges and post-holiday drops

### 🌦️ Weather Correlation (N8)
- Evaluated if temp or rainfall influence fuel demand and pricing
- Weak correlation but notable anomalies on peak-temperature days

### 📉 Economic Indicators (N9–N11)
- CPI, interest rates, and excise tax trends visualized
- Found fuel prices adjust slower to economic shifts

### 🧑‍🤝‍🧑 Population Factors (N12)
- Visualized fuel price distributions by suburb population density
- Used geospatial overlays to identify outliers in pricing zones

---

## 🌐 Interactive Map
📍 [North of River Station Cluster Map (HTML)](North%20of%20River_station_cluster_map.html)
- Shows station-wise price grouping by brand and suburb
- Clickable markers with price values
- Geospatial clustering demonstrates branding hotspots

---

## 📊 Tools & Technologies
- Python (Pandas, Matplotlib, Plotly, Seaborn)
- Geopandas, Folium, HTML mapping
- Jupyter Notebooks
- Excel, ABS Data, FuelWatch WA API

---

## 📄 Deliverables
| File | Description |
|------|-------------|
| `N1–N12_*.ipynb` | Jupyter notebooks with complete code and visual outputs |
| `*_cluster_map.html` | Interactive map export |
| `Report.pdf` | Final university report with insights, charts, and references |
| `README.txt` | High-level summary & planning notes |
| `Specification.pdf` | Assessment specification |

---

## 👤 Author
**Syed Muhammad Ahmed Zaidi**  
Curtin University – Predictive Analytics Capstone Project  
Student ID: 20972008

---

## 📄 License
For academic and educational showcase only. Use with citation.

---

## 🚀 Status
✅ Complete | 📊 Multi-faceted | 🧠 Insight-rich | 🌏 Industry relevant
