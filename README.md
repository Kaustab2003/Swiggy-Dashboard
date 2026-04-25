# 🍔 Swiggy Food Delivery Analytics Dashboard

> A Power BI dashboard built to analyze Swiggy's food delivery performance across sales, customer satisfaction, and order trends.

---

## 📌 Problem Statement

Swiggy, one of India's leading food delivery platforms, generates vast amounts of transactional and customer data. The goal of this dashboard is to transform that raw data into actionable business insights — enabling stakeholders to monitor revenue trends, understand customer behavior, evaluate city/state-level performance, and optimize delivery and restaurant strategies.

---

## 📊 Key Performance Indicators (KPIs)

| KPI | Description | Value (Sample) |
|-----|-------------|----------------|
| **Total Sales** | Overall revenue generated from all food orders | ₹53.01M |
| **Average Rating** | Mean customer satisfaction score across all restaurants | 4.34 |
| **Average Order Value** | Revenue per individual order placed | ₹268.51 |
| **Rating Count** | Total number of customer reviews submitted | 5.59M |
| **Total Orders** | Cumulative count of food orders received | 197.43K |

---

## 📈 Charts & Visualizations

### 1. 📅 Monthly Sales Trend
- **Type:** Line / Area Chart
- **Purpose:** Shows how total sales fluctuate month by month.
- **Insight:** Helps identify seasonal patterns, growth months, and sales dips across the year (Jan–Aug tracked).

---

### 2. 📆 Daily Sales Trend
- **Type:** Bar Chart
- **Purpose:** Highlights order and revenue variations across days of the week.
- **Insight:** Identifies peak days (e.g., Saturday at ₹7.78M) vs. slower days to optimize staffing and promotions.

---

### 3. 🥗 Sales by Food Type (Veg vs Non-Veg)
- **Type:** Donut / Pie Chart
- **Purpose:** Compares revenue contribution by cuisine type.
- **Insight:** Non-Veg dominates at ~94% of total sales, offering clarity on menu preference and inventory focus.

---

### 4. 🗺️ Total Sales by State (Map Visualization)
- **Type:** Choropleth / Filled Map
- **Purpose:** Displays state-wise revenue distribution across India.
- **Insight:** Highlights high-revenue states (darker shading) to guide regional expansion and marketing efforts.

---

### 5. 📋 Quarterly Performance Summary
- **Type:** Matrix / Table
- **Purpose:** Combines Sales, Ratings, and Orders segmented by Quarter.
- **Insight:** Q1 leads in sales (₹19.67M), with consistent ratings (4.34) across all quarters.

| Quarter | Sales | Rating | Orders |
|---------|-------|--------|--------|
| Q1 | ₹19.67M | 4.34 | 73.1K |
| Q2 | ₹19.90M | 4.34 | 74.2K |
| Q3 | ₹13.44M | 4.34 | 50.2K |

---

### 6. 🏙️ Top 5 Cities by Sales
- **Type:** Horizontal Bar Chart
- **Purpose:** Identifies the leading cities contributing the most revenue.
- **Insight:** Bengaluru tops the chart at ₹35.46M, followed by Lucknow, Hyderabad, Mumbai, and New Delhi.

---

### 7. 📊 Weekly Sales Trend
- **Type:** Column Chart
- **Purpose:** Monitors weekly fluctuations in sales across ~35 weeks to identify consistency or peak periods.
- **Insight:** Enables trend spotting for promotional planning and demand forecasting.

---

## 🔍 Filters & Slicers

The dashboard includes the following interactive filters:

- **Months** — Filter data by specific months (Apr–Dec)
- **Restaurant** — Drill down by individual restaurant names
- **Category** — Filter by food category (e.g., Chinese, Pasta, Roll, Desi Ghee Sweets)

---

## 🧭 Dashboard Navigation

| Page | Description |
|------|-------------|
| **Dashboard** | High-level KPIs and visual summary |
| **Analysis** | Detailed trend and breakdown charts |
| **Data** | Raw/tabular data view |

---

## 🛠️ Tools & Technologies

- **Visualization Tool:** Microsoft Power BI
- **Data Source:** Swiggy transactional & customer dataset
- **Map Integration:** Bing Maps (state-level India map)

---

## 📁 Project Structure

```
swiggy-dashboard/
│
├── README.md                   # Project documentation (this file)
├── Swiggy_Dashboard.pbix       # Power BI report file
├── data/
│   └── swiggy_data.csv         # Source dataset
└── assets/
    └── dashboard_preview.png   # Dashboard screenshot
```

---

## 🚀 How to Use

1. Open `Swiggy_Dashboard.pbix` in **Power BI Desktop**.
2. Use the left-side slicers (Months, Restaurant, Category) to filter data.
3. Navigate between **Dashboard**, **Analysis**, and **Data** tabs for different views.
4. Hover over charts for detailed tooltips and drill-through options.

---

## 👤 Author

**Kaustab Das**
Dashboard built as part of a data analytics project on food delivery performance insights using Swiggy data.

---

*Last Updated: April 2026*
