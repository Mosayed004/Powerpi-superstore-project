# 📊 Superstore Sales & Profitability Executive BI Dashboard (Power BI)

[![Power BI](https://img.shields.io/badge/Power_BI-Desktop%20%26%20Service-F2C811.svg?logo=powerbi&logoColor=black)](https://powerbi.microsoft.com/)
[![DAX](https://img.shields.io/badge/Analytics-DAX%20Measures-blue.svg)]()
[![Dataset](https://img.shields.io/badge/Data-Superstore%20Sales-green.svg)]()
[![License](https://img.shields.io/badge/License-MIT-brightgreen.svg)](LICENSE)

> An interactive Business Intelligence (BI) dashboard and executive reporting solution built in Microsoft Power BI. Translates raw retail transactional records into strategic financial KPIs, regional performance heatmaps, and product category profitability insights.

---

## 📌 Project Overview

In multi-regional retail operations, executives need real-time clarity on revenue, product returns, margin bleed, and logistics performance.

This project ingests the canonical **Sample Superstore** dataset (`Sample - Superstore.csv`) to model, clean, and visualize enterprise commerce data. Built in `Project Power Bimms.pbix`, the dashboard delivers dynamic cross-filtering across geography, product hierarchies, and customer cohorts.

---

## ✨ Dashboard Metrics & Core Visualizations

The report features multiple analytical perspectives powered by custom **DAX** calculated measures:

### 1. 📈 Executive Financial KPIs
- **Total Revenue / Sales:** Gross revenue trends with year-over-year (YoY) growth comparisons.
- **Net Profit & Profit Margin (%):** Identifies loss-making sub-categories despite high sales volumes.
- **Total Orders & Quantity Dispatched:** Order frequency metrics.

### 2. 🗺️ Geographic & Regional Performance
- Interactive choropleth map highlighting performance across regions (**Central**, **East**, **South**, **West**).
- State-level drill-down uncovering geographic revenue hubs and underperforming markets.

### 3. 📦 Product Portfolio & Category Profitability
- Deep dive into major categories: **Technology**, **Furniture**, and **Office Supplies**.
- Sub-category scatter matrix plotting Sales vs. Profit to isolate high-margin stars from margin detractors (e.g. Tables / Bookcases).

### 4. 👥 Customer Segmentation & Logistics
- Cohort analysis dividing orders into **Consumer**, **Corporate**, and **Home Office** segments.
- Shipping mode analysis (**Standard Class**, **Second Class**, **First Class**, **Same Day**) tracking delivery turnaround times and freight costs.

---

## 🏗️ Repository Layout

```
Powerpi-superstore-project/
├── Project Power BI/
│   ├── Project Power Bimms.pbix    # Full Power BI Desktop report with data models & visuals
│   └── Sample - Superstore.csv     # Source retail sales dataset
└── README.md                       # Project documentation
```

---

## 🚀 How to View and Interact

### Prerequisites
- Install [Microsoft Power BI Desktop](https://powerbi.microsoft.com/desktop/) (Free download on Windows).

### Opening the Report
1. Clone the repository:
   ```bash
   git clone https://github.com/Mosayed004/Powerpi-superstore-project.git
   ```
2. Navigate to the `Project Power BI/` directory.
3. Double-click **`Project Power Bimms.pbix`** to launch the dashboard in Power BI Desktop.
4. Interact with slicers (Year, Region, Segment, Category) to observe dynamic cross-filtering across all visual cards and graphs!

---

## 👤 Author

Developed by **Mohamed Sayed** ([@Mosayed004](https://github.com/Mosayed004)).
Licensed under the **MIT License**.
