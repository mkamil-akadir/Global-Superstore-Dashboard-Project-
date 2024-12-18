# Global Superstore Sales and Customer Insights Dashboard

## Project Overview

**Title:**  
Global Superstore Sales and Customer Insights Dashboard  

**Objective:**  
To create a Power BI dashboard that provides actionable insights into sales performance, customer demographics, and product trends. This project demonstrates end-to-end business intelligence skills, from data preparation to visualization, showcasing the ability to deliver solutions that improve decision-making for business leaders.

**Target Audience:**  
Business stakeholders such as sales managers, marketing teams, and supply chain leaders looking to identify key growth opportunities and areas for optimization.

---

## Problem Statement

1. **Fragmented Data:**  
   Business leaders struggle with fragmented and inconsistent sales and customer data across regions and product categories.

2. **Lack of Real-Time Insights:**  
   Stakeholders lack access to centralized, real-time dashboards to monitor performance metrics and trends.

3. **Missed Opportunities:**  
   Without in-depth customer segmentation and product analysis, businesses risk missing opportunities to improve sales, target specific customer groups, or optimize inventory.

---

## Dashboard Goals

### What This Dashboard Solves:
- **Sales Trends and Forecasting:**  
  Identify underperforming regions or products and forecast potential revenue growth.
  
- **Customer Segmentation:**  
  Understand customer demographics to tailor marketing efforts and improve customer engagement.

- **Product Analysis:**  
  Highlight top-performing and low-performing products to adjust inventory and focus on high-demand categories.
  
- **Operational Insights:**  
  Enable supply chain optimization by analyzing stock levels and sales velocity.

---

## Key Steps in the Project

### 1. Data Preparation
- **Source the Dataset:**  
  Download the Global Superstore Dataset from Kaggle.
  
- **Understand the Data:**  
  Explore dataset structure (e.g., tables for orders, customers, and products) and identify relationships.
  
- **Clean the Data:**  
  - Remove duplicates and null values.  
  - Standardize formats (e.g., dates, currency).  
  - Add calculated columns where necessary (e.g., `Profit Margin = Profit / Revenue`).  
  - **Tools:** Power Query in Power BI.

---

### 2. Data Modeling
- **Build Relationships:**  
  Link tables (e.g., Orders ↔ Customers ↔ Products).  
- **Star Schema:**  
  - **Fact Table:** Sales transactions.  
  - **Dimension Tables:** Customers, Products, Regions, Dates.

---

### 3. Dashboard Design
**Main Sections:**  
1. **Landing Page:**  
   - Key metrics: Total Sales, Profit Margin, Top Region, Top Product.  
   - Time slicer: Enable stakeholders to filter by date ranges.  
2. **Sales Analysis:**  
   - Bar chart: Sales by region.  
   - Line chart: Monthly sales trends.  
   - Matrix: Sales by product category and subcategory.  
3. **Customer Insights:**  
   - Donut chart: Customer demographics (e.g., age, gender).  
   - Table: Top 10 customers by revenue.  
4. **Product Performance:**  
   - KPI Cards: Top 3 products by sales.  
   - Column chart: Profitability by product category.  

**Tools Used:** Power BI visuals such as slicers, bar charts, line charts, and tables.

---

### 4. Advanced Features
- **DAX Measures:**  
  - Calculate year-over-year (YoY) sales growth.  
  - Dynamic profit margins based on selected timeframes.  
  - Rank top-performing regions/products.  
- **Interactive Elements:**  
  - Slicers for time, region, and product categories.  
  - Drill-through options for detailed views.

---

### 5. Insights and Reporting
- **Placeholder**
- **Insights Page:**  
  Highlight key findings, such as:  
  - "Region X experienced a 15% YoY decline in sales."  
  - "Product Category Y contributes to 40% of total profits."  
- **Recommendations:**  
  - Focus on high-demand regions.  
  - Reallocate inventory to improve supply chain efficiency.

---

### 6. Validation and Testing
- **Data Accuracy:**  
  Cross-check dashboard results with raw data.  
- **Testing:**  
  Ensure all interactive features function as expected.

---

