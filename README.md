# 📊 Northline Sales & Profitability Dashboard

An interactive and executive-ready **Power BI Dashboard** engineered to track sales performance, evaluate product profitability, analyze regional distribution, and deliver actionable insights for business decision-makers.

---

## 🌟 Key Features & Pages

### 1. 📈 Performance Overview
* **Executive KPIs:** Real-time tracking of **Revenue YTD ($25.2M)**, **Total Profit ($58.7M)**, **Profit Margin (78.28%)**, and **Total Units Sold (90K)** with YOY/MoM growth indicators[cite: 1].
* **Trend Analysis:** Line and column charts comparing current MTD revenue vs. previous month trends[cite: 1].
* **Product & Regional Breakdowns:** Bar chart visuals for top revenue-generating products (e.g., HP Spectre, Dell XPS 13, MacBook Pro) and regional performance (West, East, South, North)[cite: 1].
* **Category Breakdown:** Donut visual illustrating revenue proportions across Laptops, Smartphones, Tablets, and Accessories[cite: 1].

### 2. 💰 Profitability Analysis
* **Discount vs. Profit/Revenue:** Detailed bar visual evaluating the direct impact of discount percentages on total profit and revenue.
* **Product Ranking & Matrix:** Full breakdown of product performance showing Total Revenue, Total Profit, YOY Growth %, and Top Product Rank.
* **Scatter & Distribution Plots:** Visualizing total profit vs. total revenue distribution across category clusters[cite: 2].

### 3. 🔍 Drillthrough & Detailed Reporting
* **Customer-Level Insights:** Granular table showing customer performance, YTD revenue, YOY growth, and category engagement[cite: 3].
* **Historical Trends:** Multi-year line chart evaluating historical growth patterns across fiscal years (2022–2024)[cite: 3].

---

## 🛠️ Data Modeling & DAX Measures

The report utilizes custom **DAX measures** to compute key performance metrics dynamically:
* **Time Intelligence:** `Revenue YTD`, `Prev Month`, `MoM Growth %`, `YOY Growth %`[cite: 2, 3, 4]
* **Ranking & Metrics:** `Top Product Rank`, `Profit MTD`, `Diff Revenue`, `Diff MoM`[cite: 2, 3, 4]

---

## 📁 Repository Structure

```text
├── Data/                       # Raw or cleaned datasets (CSV/Excel)
├── Dashboards/                 # Power BI (.pbix) file
├── Screenshots/                # High-resolution visual screenshots
└── README.md                   # Project documentation
