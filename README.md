# AICTE-IBM-SkillsBuild-Big-Data-and-Business-Management-Internship
its a Big Data and Business Management Internship by BharatCares(CSRBOX Group) &amp; IBM SkillsBuild under IBM SkillsBuild Academic Internship Program, in association with AICTE.  This 6-week virtual internship will help you develop skills in Big Data, Business Analytics, AI, Data Visualization, and Data-Driven Decision Making. 


# 📊 Sales & Customer Performance Dashboards | Tableau Project

Interactive Tableau dashboards built to help sales managers and executives analyze
year-over-year sales performance and understand customer behavior — from raw CSV
data to a fully interactive, published product.

🔗 **[View Live Dashboard on Tableau Public](https://public.tableau.com/app/profile/jagruthi.sachin.poondrrikaksha/viz/SalesandCustomerDashboard_17845796128870/SalesDashboard)**

---

## 📌 Background

This project was completed as part of a self-initiated assignment under an
educational internship with **Bharat Cares**, in association with **IBM** and
**AICTE**. The brief was to independently design and build a working Tableau
dashboard solution end-to-end, from raw data to a polished, interactive product.

## 🎯 Objective

Build two dashboards that let sales managers and executives:

- Monitor high-level KPIs at a glance
- Compare current year performance against the previous year
- Spot trends, highs, and lows quickly
- Understand customer behavior and identify top contributors to profit

## 🗂️ Data & Tools

- **Dataset:** Sales and Customers Dashboard dataset — four related CSV files
  (`Products`, `Orders`, `Customers`, `Location`)
- **Tool:** Tableau, used for data viewing and exploration directly (no separate
  Excel step needed)
- **Calculated fields:** built using SQL logic within Tableau

## 🔧 Process

1. Built the data source by joining/relating the four CSV files
2. Performed data cleaning to handle inconsistencies
3. Conducted data analysis to identify key metrics and trends
4. Designed and built two interactive dashboards with cross-filtering

---

## 📈 Sales Dashboard

**Purpose:** Give a year-over-year view of sales, profit, and quantity trends.

| Requirement | Delivered As |
|---|---|
| KPI overview (sales, profit, quantity) | Three BAN (Big Ass Number) cards with % vs. prior year and sparkline trend |
| Monthly trend, highlight highs/lows | Sparklines with color-coded highest (teal) and lowest (pink) points |
| Product subcategory comparison | Diverging bar chart: 2022 vs 2021 sales, plus profit/loss by subcategory |
| Weekly trend vs. average | Dual area/line charts for weekly sales & profit, with an average reference line and above/below shading |

**Result:** 2022 totals of **$609K** sales (+29.5%), **$82K** profit (+32.7%), and
**10K** units (+23.3%) vs. the prior year.

## 👥 Customer Dashboard

**Purpose:** Surface customer segments, engagement, and top-value customers.

| Requirement | Delivered As |
|---|---|
| KPI overview (customers, sales/customer, orders) | Three BAN cards with sparklines |
| Monthly trend, highs/lows | Same sparkline treatment as Sales Dashboard |
| Distribution by order count | Bar chart showing customer counts across order frequency (1–7 orders) |
| Top 10 customers by profit | Ranked table with rank, name, last order date, profit, sales, and order quantity |

**Result:** **638** total customers (+23.1%), **$1.0K** sales per customer
(+16.3%), and **1,315** total orders (+26.7%) vs. the prior year.

---

## 🎨 Design Approach

- Consistent visual language across both dashboards (same header style, filter
  icons, teal/pink for highest/lowest)
- BAN + sparkline pattern used to combine KPI value and trend in a single
  component
- Global filters used throughout for interactivity

## 🧩 Challenges

- Structuring containers correctly to keep the dashboard layout responsive and
  clean
- Building the customer distribution chart, which required careful bucketing of
  customers by order count

## ✅ Outcome

Both dashboards give stakeholders a single-screen view of performance,
replacing manual report pulls, and make year-over-year comparisons and outliers
immediately visible.

---

## 📁 Repository Contents

├── Sales_Customers_Dashboard.twbx # Packaged Tableau workbook (data + dashboards)
├── data/ # Source CSV files (Products, Orders, Customers, Location)
├── Concept_Note.docx # Project concept note
├── Presentation.pptx # Project presentation
└── README.md



![Sales Dashboard](https://github.com/jagruthi315/AICTE-IBM-SkillsBuild-Big-Data-and-Business-Management-Internship/blob/main/screenshots/sales%20dashboard.JPG)


![Customer Dashboard](https://github.com/jagruthi315/AICTE-IBM-SkillsBuild-Big-Data-and-Business-Management-Internship/blob/main/screenshots/customer%20dashboard.JPG)
---

## 🏷️ Credits

Built as a self made project in the  educational internship with **Bharat Cares**, in
association with **IBM** and **AICTE**.





## 🔗 Live Dashboard

👉 [https://public.tableau.com/app/profile/jagruthi.sachin.poondrrikaksha/viz/SalesandCustomerDashboard_17845796128870/SalesDashboard](https://public.tableau.com/app/profile/jagruthi.sachin.poondrrikaksha/viz/SalesandCustomerDashboard_17845796128870/SalesDashboard)

No login or software required — opens directly in a web browser.



