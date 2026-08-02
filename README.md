# GCC

# Food, Energy, and Water (FEW) Nexus Dashboard

A comprehensive Data Analytics and Visualization project built in **Power BI** to monitor and analyze critical indicators including **Food Security, Agricultural/Fisheries Production, Water Stress, Desalinated Water, Energy Share, and Economic Price Indices (CPI)** across GCC countries and global regions.

---

## 📌 Project Overview

Ensuring resource sustainability—specifically across the **Food-Energy-Water (FEW) Nexus**—is a vital challenge for developing and high-growth economies. This interactive dashboard provides a data-driven platform for policy analysts, researchers, and decision-makers to track key environmental and economic metrics.

### Key Metrics & Data Model Indicators:
- **Food Security & Price Dynamics:** Food Consumer Price Index (CPI), Food Insecurity Index, and Fisheries Production (in Kilotons).
- **Water Resource Management:** Water Stress Percentage (`Water_Stress_Pct`), Water Efficiency (`Water_Efficiency_USD_m3`), and Desalinated Water Production (`Desalinated_Water_MioM3`).
- **Energy & Macro Economics:** Renewable Energy Share (`Renewable_Energy_Share`), Dairy Production (`Dairy_Prod_ML`), and Total Resource Imports (`Total_Imports_USD_M`).

---

## 🎨 Key Features & Visualizations

- **Dynamic Interactive Slicers:** Country-level filtering (Saudi Arabia, UAE, Kuwait, Qatar, Bahrain, etc.) and Time Series selections.
- **Data Model & Schema:** Multi-table relational model with custom DAX measures, theme definitions, and clean layout structures.
- **KPI Visuals & Summary Gauges:** Real-time summary cards tracking fish production volumes, desalinated water production, and food price tracking.
- **Interactive Visuals:** 
  - Doughnut Charts for resource allocation and distribution.
  - Multi-axis Line Charts highlighting historical trends in water stress vs. desalinated water volume.
  - Granular Country Comparison Tables for detailed analytical inspection.

---

## 🛠️ Tech Stack & Tools

- **Power BI Desktop:** Report layout, DAX calculations, schema modeling, and theme formatting.
- **Power BI Service:** Interactive web publishing and cloud data refresh management.
- **Power Query (M):** Data extraction, transformation, cleaning, and missing-value (`Blank`) handling.
- **DAX (Data Analysis Expressions):** Custom aggregation measures, dynamic KPIs, and fallback handling.

---

## 📁 Repository Structure

```text
├── assets/
│   └── dashboard_preview.jpg         # Dashboard screenshot / visual preview
├── data/
│   └── raw_data.csv                  # Underlying dataset (if applicable)
├── Food_Energy_Water_Dashboard.pbix  # Primary Power BI Desktop File
└── README.md                         # Project documentation
