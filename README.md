# 📊 Global Superstore Sales & Profitability Analysis

## 📌 Project Overview

This project analyses the Global Superstore dataset to understand the company's sales performance, profitability, customer segments, product performance, regional performance and operational efficiency.

It was updated to capture more business questions that was missed in the previous analysis.

The project was developed as a Business Intelligence and Data Analytics project using Microsoft Power BI, with supporting analysis and documentation completed using Microsoft Excel, Microsoft Word and Microsoft PowerPoint.

The goal was to transform raw transactional data into an interactive dashboard that can help management understand business performance, identify areas of concern and make data-driven decisions.

---

## 🎯 Business Objective

The analysis was designed to answer the following business questions:

1. What is the overall sales performance of the company?
2. Which regions generate the highest sales and profit?
3. Which customer segments contribute the most revenue?
4. Which product categories perform best?
5. Which products are the most profitable?
6. What trends can be observed over time?
7. What recommendations should management implement to improve business performance?

---

## 🗂️ Dataset

The project uses the Global Superstore dataset, which contains transactional information relating to customers, products, sales, profit, discounts, shipping and geographic performance.

### Key areas analysed

- Sales
- Profit
- Profit Margin
- Orders
- Customers
- Customer Segments
- Markets
- Regions
- Countries
- Categories
- Sub-Categories
- Products
- Discounts
- Shipping
- Order Dates
- Ship Dates

The dataset was cleaned and transformed in Power BI using Power Query before analysis.

---

# 🛠️ Tools Used

### Microsoft Power BI

Used for:

- Data transformation
- Data modelling
- DAX measures
- KPI development
- Interactive dashboards
- Sales and profitability analysis
- Regional and product analysis
- Business performance analysis

### Microsoft Excel

Used for supporting analysis, calculations and data exploration.

### Microsoft PowerPoint

Used to present key findings, business risks, opportunities and recommendations.

### Microsoft Word

Used to prepare the Business Intelligence and Business Analysis documentation.

---

# 🧹 Data Preparation

Before developing the dashboard, the dataset was reviewed and prepared for analysis.

The preparation process included:

- Reviewing the dataset structure
- Checking data types
- Reviewing missing values
- Checking for duplicate records
- Validating date fields
- Creating calculated fields and measures
- Creating profit margin calculations
- Creating shipping duration calculations
- Creating discount bands
- Creating month and year fields for time-based analysis

---

# 📊 Dashboard Overview

The Power BI report consists of three main pages.

## Page 1: Executive Sales Overview

This dashboard provides a high-level view of overall business performance.

### KPIs

- Total Sales
- Total Profit
- Total Orders
- Average Sales
- Profit Margin

### Analysis

- Sales and Profit Trend by Year
- Sales and Profit by Customer Segment
- Sales and Profit by Category
- Overall business performance

### Purpose

This page answers:

> **How is the company performing overall?**

---

# 🌍 Page 2: Regional & Product Performance

This page focuses on geographic and product performance.

### Regional Analysis

- Sales and Profit by Region
  
### Geographic Analysis

- Geographic sales distribution

### Product Analysis

- Top Products by Sales
- Top Products by Profit
  
----------

# 🔎 Page 3: Detailed Business Analysis

The third dashboard focuses on factors that may influence profitability and operational performance.

### Key analyses

- Sales and Profit by Sub-Category
- Profit Impact of Discount Levels
- Shipping Cost by Region
- Average Shipping Days by Ship Mode
- Sales and Profit by Ship Mode

### Discount Analysis

Discount levels were grouped into bands to investigate their relationship with profitability.

This analysis helps identify discount levels where profitability becomes weaker or negative.

### Shipping Analysis

Shipping duration was calculated using:

**Ship Date - Order Date**

This was used to analyse average shipping days across different shipping modes.

---

# 📈 Key Business Insights

The analysis revealed several important patterns.

### 1. Sales and Profit Growth

Sales and profit increased over the period covered by the dataset, indicating overall business growth accompanied by an increase in profitability.

### 2. Category Profitability Differs

Sales volume does not always translate into higher profitability.

Some categories generate substantial sales but operate at significantly lower profit margins than others.

This highlights the importance of analysing both revenue and profitability when evaluating business performance.

### 3. Higher Discounts Are Associated With Weaker Profitability

The discount analysis showed that higher discount levels are associated with weaker profitability.

Order lines with high discounts collectively contributed negatively to profit, highlighting the need for better discount monitoring.

### 4. Regional Performance Varies

Sales and profitability differ significantly across markets and regions.

Some geographic areas generate strong sales but comparatively lower profit margins, indicating opportunities to investigate pricing, product mix, discounting and operating costs.

### 5. Customer Segments Contribute Differently

The Consumer, Corporate and Home Office segments do not contribute equally to total sales and profit.

This highlights the importance of segment-level analysis when developing sales and customer strategies.

---

# ⚠️ Business Risks

Based on the analysis, three key risks were identified.

## 1. High Discounting Can Reduce Profitability

Higher discount levels are associated with negative profitability across some order lines.

Without appropriate monitoring, aggressive discounting could reduce overall margins.

## 2. Low-Margin Products and Sub-Categories

Some products and sub-categories generate sales while producing relatively weak or negative profitability.

Continued focus on sales volume alone could therefore hide underlying profitability problems.

## 3. Regional Profitability Differences

Significant differences exist in profitability across geographic areas.

Regions or markets with relatively low margins may require further investigation into pricing, product mix, discounting and operational costs.

---

# 💡 Business Opportunities

## 1. Focus on High-Margin Products

Management can increase focus on products and sub-categories that consistently generate stronger profit margins.

## 2. Improve Discount Management

Discounting can be reviewed by product, category, region and customer segment to identify where discounts are generating sufficient sales value and where they are unnecessarily reducing profit.

## 3. Apply Best Practices Across Geographic Areas

High-performing markets and regions can be investigated to understand the factors contributing to stronger profitability.

Relevant practices can then be assessed for application in lower-performing areas.

---

# 🚀 Recommendations

Based on the analysis, the following actions are recommended:

1. **Introduce stronger discount controls** for high-discount transactions and evaluate whether additional discounts generate enough sales value to justify the reduction in margin.

2. **Review loss-making products and sub-categories** to determine whether pricing, product costs or discounting should be adjusted.

3. **Prioritise high-margin products** when developing sales campaigns and promotional strategies.

4. **Investigate low-margin markets and regions** to identify the underlying causes of weaker profitability.

5. **Monitor sales and profitability continuously** using Power BI dashboards to support faster management decision-making.

---

# 📁 Project Structure

```text
Global-Superstore-Analysis/
│
├── Dataset/
│   └── Global_Superstore_Dataset.xlsx
│
├── Power BI/
│   └── Global_Superstore_Dashboard.pbix
│
├── Excel/
│   └── Global_Superstore_Analysis.xlsx
│
├── Report/
│   └── Business_Intelligence_Report.docx
│
├── Presentation/
│   └── Global_Superstore_Insights.pptx
│
└── README.md
