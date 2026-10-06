# 📊 Retail Sales & Profit Dashboard

## 📌 Project Overview

The **Retail Sales & Profit Dashboard** is a data analytics project developed using **Microsoft Excel and Power BI**.

The project analyzes retail sales data to understand **sales performance, profit, product categories, regional performance, and sales trends**. Excel is used for data cleaning and analysis, while Power BI is used to create an interactive dashboard.

## 🎯 Objectives

- Analyze overall sales and profit.
- Identify top-performing product categories.
- Compare sales and profit across regions.
- Analyze monthly sales trends.
- Identify high-performing products.
- Track important business KPIs.
- Create an interactive dashboard for business decision-making.

## 🛠️ Tools Used

- **Microsoft Excel**
  - Data Cleaning
  - Data Formatting
  - Formulas
  - Pivot Tables
  - Pivot Charts

- **Microsoft Power BI**
  - Power Query
  - Data Transformation
  - Data Modeling
  - DAX
  - Interactive Dashboard
  - Charts and Slicers

## 📂 Dataset

The dataset contains retail transaction information such as:

- Order Date
- Product
- Category
- Region
- Quantity
- Sales
- Cost
- Profit

## 🔄 Project Workflow

```text
Retail Sales Dataset
        ↓
Data Cleaning in Excel
        ↓
Excel Analysis
        ↓
Pivot Tables & Charts
        ↓
Import into Power BI
        ↓
Power Query Transformation
        ↓
DAX Measures
        ↓
Interactive Dashboard
        ↓
Business Insights
```

## 📊 Excel Analysis

Excel was used to prepare and analyze the retail dataset.

### Activities Performed

- Removed duplicate records.
- Checked missing values.
- Formatted the dataset.
- Used Excel formulas.
- Created calculated fields.
- Created Pivot Tables.
- Created Pivot Charts.
- Analyzed sales and profit by category and region.

### Key Calculations

**Profit**

```text
Profit = Sales - Cost
```

**Profit Margin**

```text
Profit Margin = (Profit / Sales) × 100
```

## 📈 Power BI Dashboard

The cleaned Excel data was imported into Power BI to create an interactive **Retail Sales & Profit Dashboard**.

### KPIs

- **Total Sales**
- **Total Profit**
- **Total Quantity**
- **Profit Margin**
- **Total Orders**

### Dashboard Visuals

- Monthly Sales Trend
- Monthly Profit Trend
- Sales by Category
- Profit by Category
- Sales by Region
- Profit by Region
- Top Products by Sales
- Top Products by Profit

### Slicers

- Date
- Category
- Region
- Product

## 🧮 DAX Measures

### Total Sales

```DAX
Total Sales = SUM(Sales[Sales])
```

### Total Profit

```DAX
Total Profit = SUM(Sales[Profit])
```

### Total Quantity

```DAX
Total Quantity = SUM(Sales[Quantity])
```

### Profit Margin

```DAX
Profit Margin = DIVIDE([Total Profit], [Total Sales], 0)
```

## 🔍 Key Insights

The dashboard helps identify:

- Best-performing product categories.
- Most profitable products.
- High-performing regions.
- Monthly sales and profit trends.
- Products with low profitability.
- Overall business performance.

## 💡 Business Recommendations

- Focus on high-profit products and categories.
- Improve performance in low-performing regions.
- Monitor monthly sales trends.
- Review pricing and costs for low-profit products.
- Use dashboard insights for better business decisions.

## 📁 Project Structure

```text
Retail-Sales-Profit-Dashboard/
│
├── Excel/
│   └── Retail_Sales_Analysis.xlsx
│
├── PowerBI/
│   └── Retail_Sales_Profit_Dashboard.pbix
│
├── Screenshots/
│   └── Dashboard.png
└── README.md
```


```

## 🚀 Project Outcome

This project demonstrates practical skills in **Microsoft Excel and Power BI** for data cleaning, analysis, visualization, dashboard creation, and business intelligence.

The final dashboard converts raw retail sales data into meaningful insights that can support **sales and profit analysis and business decision-making**.

## 👨‍💻 Author

**Mayur Pawar**

**M.Sc. Computer Science**

**Skills:** `Microsoft Excel` `Power BI` `Power Query` `DAX` `Data Analysis` `Data Visualization`
