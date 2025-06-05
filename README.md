# 💼 Financial Report Dashboard with Power BI

## 📊 Overview

This project presents an interactive **Financial Report Dashboard** created in Power BI, offering insights into key business metrics such as Total Sales, Profit %, Total Margin, Average Order Value, and sales distribution across countries, products, segments, and discount bands.

The report enables business stakeholders to analyze trends, optimize pricing strategies, and identify top-performing regions and customer segments.


---
## 📷 Dashboard Preview


<img width="697" alt="Financial Data Analysis" src="https://github.com/user-attachments/assets/2b7b6a62-00c8-42af-9634-f4549dc60932" />


---

## 🎯 Objectives

This report answers the following key business questions:

1. **Total Sales by Country**  
   - Identify top revenue-generating countries.

2. **Total Sales by Segment**  
   - Understand sales contributions by business segment (e.g., Government, Small Business, Enterprise).

3. **Total Sales by Discount Band**  
   - Evaluate how different discount strategies impact total revenue.

4. **Total Sales by Product**  
   - Discover top-performing products by sales volume.

5. **KPI Metrics Cards**  
   - Total Sales  
   - Total Cost of Goods Sold (COGS)  
   - Total Margin  
   - Profit Percentage  
   - Average Order Value

6. **Interactive Filters/Slicers**  
   - Filter the report by Country, Segment, Product, Discount Band, and Date range.


---

## 📂 Dataset 

- **File Used:** <a href="https://github.com/edinakanlic/Financial-Data-Analysis-Power-BI/blob/main/Financial%20Sample.xlsx">Financial dataset</a>
- **Key Fields:**
  - `Country`, `Segment`, `Product`, `Discounts`, `Sales`, `COGS`, `Margin`, `Profit %`, `Date`

---

## 🔍 Data Analysis Process

### 1. Data Cleaning & Loading
- Loaded the dataset in Power BI using xlsx format.
- Removed empty or duplicate records.
- Converted financial values and dates into correct formats.

### 2. Modeling & DAX Measures
- Created custom DAX measures for:
  - `Total Sales = SUM(Sales)`
  - `Total COGS = SUM(COGS)`
  - `Total Margin = SUM(Profit)`
  - `Profit % = [Total Margin] / [Total COGS]

### 3. Report Design
- **Bar and Column Charts** for country and product sales  
- **Donut Charts** for segment and discount distribution  
- **KPI Cards** for financial overview  
- **Slicers** for dynamic filtering  
- Applied consistent theme with business icons and visual clarity

---

## 💡 Key Insights

- The **United States** and **France** are the top sales contributors.
- **Government** and **Small Business** segments dominate revenue.
- Products like **Paseo** and **VTT** bring in the most income.
- Sales are heavily concentrated in the **High Discount Band**, suggesting strong customer response to discounts.

---

## 🛠 Tools Used

- **Power BI Desktop**
- Power Query Editor
- DAX for calculated metrics
- PNG screenshots for visual embedding

---

## ▶️ How to Use

1. Clone this repository.  
2. Open the `.pbix` file using Power BI Desktop.  
3. Ensure `Financial Sample.xlsx` is in the root or linked correctly.  
4. Explore the report using filters to answer different business questions.

---
