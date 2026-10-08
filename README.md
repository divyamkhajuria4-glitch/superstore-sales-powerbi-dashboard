# superstore-sales-powerbi-dashboard
An interactive Power BI dashboard designed to analyze **sales, profitability, quantity, regional performance, and the relationship between discount and profit** using four years of Superstore sales data.

## Project Objective

The goal of this project was to transform raw Superstore sales data into an interactive business intelligence dashboard that helps identify:

* Overall sales and profit performance
* Most and least profitable product categories
* Regional and segment-level performance
* Sales and profit trends over time
* The relationship between discounts and profitability
* Loss-making sub-categories requiring attention

## Dashboard Pages

### Page 1 — Executive Summary

Key KPIs and overall business performance:

* **Total Sales:** 13M
* **Total Profit:** 1.47M
* **Profit Margin:** 11.61%
* **Total Quantity:** 178K

Visuals include:

* Sales by Sub-Category
* Sales & Profit trend over time
* Sales by Customer Segment
* Sales by State using a map
* Region and Year slicers for interactive filtering

### Page 2 — Profit & Discount Analysis

Focused on understanding profitability and discount behavior.

Visuals include:

* Profit by Sub-Category
* Discount vs Profit scatter analysis
* Sales represented through bubble size
* Sub-Category comparison

## Key Insights

* **Technology** is the strongest profitability contributor, particularly through products such as Phones, Copiers, and Accessories.
* **Tables and Bookcases** are loss-making sub-categories despite generating sales.
* Higher discount levels are associated with weaker profitability, with the strongest negative impact visible in certain Furniture sub-categories.
* The **West Region** has the highest sales contribution.
* The **Consumer segment** contributes the largest share of total sales.

## Tools & Technologies

* **Power BI**
* **Power Query**
* **DAX**
* Data Modeling
* Interactive Data Visualization

## Data Preparation

The dataset was prepared using Power Query by:

* Inspecting the dataset structure
* Handling data-quality issues
* Correcting column data types
* Preparing date fields for time-based analysis
* Building relationships within the Power BI data model

## DAX Measures

```DAX
Total Sales = SUM(Sales)

Total Profit = SUM(Profit)

Total Quantity = SUM(Quantity)

Profit Margin = DIVIDE([Total Profit], [Total Sales])
```

## Business Recommendations

1. **Review discount policies** for products where higher discounts are associated with negative profitability.
2. **Re-evaluate Tables and Bookcases pricing/discount strategies** because these sub-categories are generating losses.
3. **Protect high-performing Technology products** and investigate opportunities to expand profitable product lines.
4. **Analyze regional performance further** to understand why the West Region generates the highest sales.
5. Use profitability, rather than sales alone, when evaluating product and discount decisions.

## Project Outcome

This project demonstrates the complete BI workflow from **data preparation and modeling to DAX-based analysis, interactive visualization, and business insight generation**.

The dashboard can be used by sales and management teams to monitor performance and identify areas where pricing, discounting, and product strategy may need improvement.
