# Masterclass 2 — Tableau Basics

## What I Learned

### Tableau Interface
- Drag and drop — Columns & Rows shelf
- Green data = Quantitative (measures)
- Blue data = Qualitative (dimensions)
- Globe icon = Geographical data
- \# icon = Numeric data
- ABC icon = String/text data
- Naming conventions are crucial in professional settings

### Chart Selection Rule
> Correct chart > Beautiful chart — always!

### Charts & When to Use

| Chart | Use When |
|-------|----------|
| Bar Chart | Comparison between categories |
| Line Chart | Trends over time |
| Pie Chart | Part of a whole |
| Scatter Plot | Relationship between two variables |
| Box Plot | Distribution, outliers, median |
| Treemap | Data too complex for bar/line |
| Bullet Chart | Comparing two variables against a target |
| Heat Map | Large complex data |
| Dual Axis | Two measures on same chart |

### Key Tips
- Double click geographical column → map auto-created
- Filters, Color, Size, Label, Shape, Detail → all customizable
- Synchronized axis → aligns both axes to same scale
- Treemap: larger box = higher value, smaller box = lower value
- Bullet chart uses two variables to compare against target
- Tree map & Heat map → used when data is very complex

---

## Dataset Used
Sample Superstore

**Columns:**
Order ID, Shipping Mode, Shipping Date, Customer ID, Name, Segment, Country, Region, City, State/Province, Postal Code, Product ID, Category, Sub-Category, Product Name, Sales, Quantity, Discount, Profit

---

## Practice Charts

### 1. Region vs Profit
- Type: Stacked Bar Chart
- X-axis: Region | Y-axis: SUM(Profit) | Color: Category
- **Insight:** West region highest overall profit

![region_profit](../screenshots/region_profit.png)

---

### 2. Region Average Profit
- Type: Pie Chart
- Size & Color: AVG(Profit) by Region
- **Insight:** Profit share distribution across regions

![region_avg_profit](../screenshots/region_avg_profit.png)

---

### 3. Profit vs Sales
- Type: Line Chart
- X-axis: SUM(Profit) | Y-axis: SUM(Sales) | Color: Category
- **Insight:** Technology shows highest sales jump with profit

![profit_sales](../screenshots/profit_sales.png)

---

### 4. Monthly Profit & Discount
- Type: Dual Axis Line Chart
- X-axis: Month(Ship Date)
- Y-axis 1: SUM(Discount) | Y-axis 2: SUM(Profit)
- **Insight:** Higher discount months tend to have lower profit

![monthly_profit_discount](../screenshots/monthly_profit_discount.png)

---

### 5. Profit per Category
- Type: Scatter Plot
- X-axis: Category | Y-axis: SUM(Profit) | Shape: Sub-Category
- **Insight:** Furniture has negative profit in several states

![cat_profit](../screenshots/cat_profit.png)

---

### 6. Sales by Sub-Category per State
- Type: Scatter Plot
- X-axis: Sub-Category | Y-axis: SUM(Sales) | Color: State
- **Insight:** Chairs and Phones have highest sales variance

![sub_cat_sales](../screenshots/sub_cat_sales.png)

---

### 7. Sales Distribution by Sub-Category
- Type: Box Plot
- Upper Whisker: 80,166 | Upper Hinge: 35,523
- Median: 13,384 | Lower Hinge: 4,105 | Lower Whisker: 132
- **Insight:** Copiers have highest median, many outliers in Chairs

![box_plot](../screenshots/box_plot.png)

---

### 8. Sales by Ship Date
- Type: Treemap
- Size: SUM(Sales) | Color: Week(Ship Date)
- **Insight:** September 22, 2024 highest sales week

![treemap](../screenshots/treemap.png)
