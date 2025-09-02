# 📊 Sales Dashboard (Power BI)

## 📌 Project Overview
This dashboard provides a **360° view of sales performance** using the Sample Superstore dataset.  
It highlights key metrics, profitability drivers, customer behavior, and regional insights to help stakeholders make data-driven decisions.

---

## 🔑 Key Business Questions Answered
- What are the **overall sales, profit, and margins** across the business?
- Which **categories, sub-categories, and products** drive the most sales?
- Who are the **top-performing products** and which are **loss-making**?
- How do **discounts impact profitability**?
- What are the **regional sales trends** and where are the hotspots?
- How efficient is **shipping performance** across modes?

---

## 📈 Key Metrics (KPIs)
- **Total Sales**  
- **Total Profit**  
- **Profit Margin %** = Profit ÷ Sales  
- **Total Quantity Sold**  
- **Orders Count**  
- **Average Discount %**  
- **Average Shipping Days**

---

## 📊 Dashboard Features
1. **Sales & Profit Overview**
   - Line chart: Sales & Profit trend by Order Date
   - Built-in forecast for next 2 quarters

2. **Category & Sub-Category Performance**
   - Treemap: Sales & Profit by Category

3. **Regional Performance**
   - Map: Sales by State
   - Profitability by region (bubble size)

4. **Shipping Analysis**
   - Avg Shipping Days by Ship Mode

5. **Discount vs Profit**
   - Scatter plot: Impact of discount % on profitability

6. **Top & Bottom Performers**
   - **Top 10 Products by Sales**
   - **Bottom 10 Products by Profit** (loss-making products)

---

## 🛠️ Tools & Techniques
- **Power BI Desktop**
- **Data Modeling** (Star schema, Relationships)
- **DAX Measures**
  - `Profit Margin %`
  - `Profit per Order`
  - `Avg Sales per Customer`
  - `Avg Shipping Days`
  - `RANKX` for Top/Bottom performers
- **Forecasting** (built-in Power BI feature)

---

