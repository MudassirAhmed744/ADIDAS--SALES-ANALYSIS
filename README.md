# ADIDAS  SALES ANALYSIS
 This repository contains the code and documentation for a comprehensive sales analysis of Adidas' product portfolio. Using historical sales data, the project identifies key trends and patterns to help optimize sales strategies and resource allocation.
# README: Retail Sales Analysis

## Overview

This project involves analyzing a dataset of retail sales to address various business problems. The dataset consists of 9,648 records with 13 columns, detailing sales information for a retail company. The primary goals of this analysis are to identify key insights into sales performance, regional market trends, profit margins, sales method efficiency, price optimization, product portfolio optimization, market expansion opportunities, time series trends, and predictive sales analysis.


     
             
![Designer](https://github.com/MudassirAhmed744/ADIDAS--SALES-ANALYSIS/assets/73222691/9d9acd30-445c-40cd-82ce-49ba6e8be025)


## Dataset Description

The dataset contains the following columns:

1. **Retailer**: Name of the retailer.
2. **Retailer ID**: Unique identifier for the retailer.
3. **Invoice Date**: Date of the sales invoice.
4. **Region**: Geographic region where the sale occurred.
5. **State**: State where the sale occurred.
6. **City**: City where the sale occurred.
7. **Product**: Type of product sold.
8. **Price per Unit**: Price per unit of the product.
9. **Units Sold**: Number of units sold.
10. **Total Sales**: Total sales amount (Price per Unit * Units Sold).
11. **Operating Profit**: Profit made from sales after operating expenses.
12. **Operating Margin**: Ratio of Operating Profit to Total Sales.
13. **Sales Method**: Method of sales (In-store, Online, Outlet).

## Analysis Objectives

1. **Sales Performance Analysis**:
    - Identify which products are excelling in sales and which are underperforming.
    - Insights: Men's Street Footwear are the highest selling products. Women's Athletic Footwear is the most underperforming product.

2. **Regional Market Analysis**:
    - Determine which stores are experiencing strong sales and which ones are lagging.
    - Insights: New York has the highest sales for multiple products. Omaha consistently shows the lowest sales across various products.

3. **Profit Margin Analysis**:
    - Assess the impact of profit margin on sales.
    - Insights: There is a strong positive correlation between Total Sales and Operating Profit, indicating that higher sales lead to higher profits.

4. **Efficiency of Sales Methods**:
    - Compare the effectiveness of different sales methods (In-store, Online, Outlet).
    - Insights: In-store sales have the highest total sales and operating profit, while online sales have the highest operating margin, indicating better efficiency in profitability.

5. **Price Optimization**:
    - Identify the price range that achieves better sales.
    - Insights: The price range of $40 to $70 achieves the highest sales. Very low and very high prices show significantly lower sales.

6. **Product Portfolio Optimization**:
    - Determine the most profitable products segmented by location.
    - Insights: 'Women's Apparel' and 'Men's Street Footwear' are highly profitable in Albany. New York excels in sales of multiple products.

7. **Market Expansion Opportunities**:
    - Assess the best and worst performing stores based on their locations.
    - Insights: 'West Gear' in Albany and 'Kohl's' in Albuquerque are top performers. Significant regional variations in store performance suggest location-specific strategies.

8. **Time Series Analysis**:
    - Investigate monthly sales trends over time.
    - Insights: Sales show seasonal patterns with peaks in December and April, likely due to holidays and promotions.

9. **Predictive Sales Analysis**:
    - Develop a forecast for monthly sales.
    - (Forecasting model development and implementation details can be added here.)

## Instructions for Using the Analysis

1. **Prerequisites**:
    - Python 3.x
    - Pandas
    - Matplotlib
    - Seaborn
    - Scikit-learn (for predictive analysis)

2. **Data Loading**:
    - Ensure the dataset file (e.g., `retail_sales_data.csv`) is in the working directory.
    - Load the data using pandas: `df = pd.read_csv('retail_sales_data.csv')`

3. **Running Analysis**:
    - Execute the Jupyter notebook or Python script containing the analysis code.
    - Follow the analysis steps to generate insights and visualizations.

4. **Interpreting Results**:
    - Review the insights generated for each business problem.
    - Use visualizations to understand trends and patterns in the data.
    - Apply findings to make data-driven decisions for improving sales strategies and performance.

5. **Extending the Analysis**:
    - Modify the code to include additional analyses as needed.
    - Implement the predictive sales analysis using machine learning models to forecast future sales.

## Conclusion

This analysis provides valuable insights into retail sales performance, regional market trends, profit margins, sales methods efficiency, price optimization, product portfolio optimization, market expansion opportunities, and time series trends. By leveraging these insights, businesses can enhance their sales strategies, optimize pricing, improve product offerings, and make informed decisions for market expansion and profitability.

---
