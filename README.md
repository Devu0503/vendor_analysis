 📊 Vendor Performance Analysis Dashboard

This project presents a complete end-to-end Vendor Performance Analysis using Python (EDA, SQLite) and Power BI (Dashboarding). It helps businesses identify low-performing vendors, optimize inventory, and improve profit margins through actionable insights.

🔍 Problem Statement

In large retail and distribution environments, managing vendor relationships and tracking performance is crucial for profitability. This project solves:

- Inefficient vendor performance tracking  
- Unused capital in inventory due to slow-moving stock  
- Unoptimized freight and excise tax planning  
- Lack of visibility on brand-level margins and purchases


 🛠️ Tools & Technologies Used

| Category         | Tools/Tech Used                             |
|------------------|---------------------------------------------|
| Language         | Python (Pandas, SQLite3, Matplotlib)        |
| Database         | SQLite (`inventory.db`)                     |
| Visualization    | Power BI                                    |
| File Types       | `.ipynb`, `.csv`, `.pbix`, `.png`            |


🚀 Key Features

- 📦 Vendor Sales Summary – Unified metrics across purchase, sales, profit, tax  
- 📈 Low Turnover Detection – Flag vendors/brands with below-threshold turnover  
- 💰 Profitability Analysis– Break down profit margins, gross profits, freight, tax  
- 📉 Capital in Inventory– View value locked in unsold stock  
- 🎯 Top-N Vendor Filtering– Easily slice views by top/bottom performers

🧮 Power BI Dashboard Layout

| Section              | Description                                                                       |
|----------------------|-----------------------------------------------------------------------------------|
| Overview Cards       | KPIs: Total Sales, Purchases, Avg Margin, Gross Profit, Unsold Capital           |
| Donut & Bar Charts   | Sales contribution, Profit margin, Turnover, Excise tax per Vendor                |
| Tables & Filters     | Drill-down tables, Top-N selector, Brand contribution by description              |
| Scatter/Line Charts  | Margin vs. Sales visualization, Purchase ratio analytics                         |

## 🔗 Workflow Overview

1. Load raw data from `inventory.db`
2. Merge & clean tables using SQL and pandas
3. Calculate key metrics: profit, margin, tax, turnover
4. Export clean dataset to `.csv`
5. Build interactive dashboard in Power BI


## 📦 Outputs

- `vendor_sales_summary.csv` – Cleaned, business-ready dataset
- Power BI `.pbix` file – Fully interactive dashboard
- Dashboard screenshots (`.png`) for quick preview

## 📚 Learnings

- Business impact of vendor decisions
- Power BI dashboarding best practices
- Real-world SQL + Python EDA integration
- Custom metrics design (StockTurnover, ProfitMargin, UnsoldCapital)

## 🤝 Acknowledgment

This project was developed as part of a business analytics portfolio focusing on supply chain performance.



