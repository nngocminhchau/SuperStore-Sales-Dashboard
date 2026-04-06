# SuperStore Sales Dashboard (Power BI)

## 📌 What I built
A Power BI dashboard analyzing 4 years of sales data (2011-2014). The dataset has ~$12.6M in total sales across multiple regions.

![Interactive Dashboard Demo](images/dashboard_demo.gif)

## 📊 Dashboards
### Sales Overview
![Sales Overview](images/overview_dashboard.png)

- KPI cards: Total Sales, Total Profit, Profit Margin
- Sales trend line chart (2011-2014)
- Sales by region bar chart
- Year slicer for filtering

### Profit Analysis
![Profit Analysis](images/profit_analysis.png)

- Sales by region
- Profit margin by region

---

## Key things I found

| Finding | What it means |
|---------|----------------|
| Sales grew from $2.3M (2011) to $4.3M (2014) | Steady growth over 4 years |
| Central region has highest sales ($2.8M in 2014) | Volume leader |
| Canada has highest profit margin (26.6%) | Most efficient region |
| Peak sales shifted from Nov 2013 to Apr 2014 | Interesting pattern, needs investigating further |

---

## How I built it

| Step | Tool/Method |
|------|-------------|
| Data cleaning | Power Query (removed duplicates, fixed data types) |
| Calculations | DAX measures for profit margin |
| Interactivity | Year slicer, page navigation buttons |
| Formatting | Changed regional settings for decimal formatting ($2.3M not $2,3M) |

---

## Files in this repo

| File | What it is |
|------|-------------|
| `SuperStore_Sales_Dashboard.pbix` | Power BI file (download to interact) |
| `images/` | Screenshots and demo GIF |
| `README.md` | This file |

---

## How to use

1. Download `SuperStore_Sales_Dashboard.pbix`
2. Open with Power BI Desktop
3. Use year slicer and buttons

---

## Dataset

Source: Kaggle SuperStore Sales Analytics Dataset (simulated retail data)

| Field | Description |
|-------|-------------|
| `order_id` | Unique transaction ID |
| `segment` | Consumer / Corporate / Home Office |
| `market / region` | Geographic grouping |
| `category` | Product type (Technology, Furniture, Office Supplies) |
| `sales` | Revenue per order |
| `profit` | Net earnings per order |

---

## What I'd do next

- Add SQL queries to practice data extraction
- Build a Python version of this analysis (Pandas + Matplotlib)
- Try forecasting future sales using time series

---

## Author

Ngoc Minh Chau Nguyen — 2nd year Data Analytics student @ University of Waikato

[GitHub](https://github.com/nngocminhchau) | [LinkedIn](https://www.linkedin.com/in/ngocminhchaunguyen0103/)
