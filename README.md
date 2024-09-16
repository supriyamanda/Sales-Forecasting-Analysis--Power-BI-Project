# Sales Forecasting Analysis - Power BI Project

## Project Overview
This project involves the analysis and visualization of sales data using Power BI. The dataset contains sales information such as order details, customer demographics, product categories, and sales regions. The project aims to uncover key sales insights, trends, and forecast future sales.

## Dataset
The dataset used for this analysis is from [Kaggle: Sales Forecasting Dataset](https://www.kaggle.com/datasets/rohitsahoo/sales-forecasting), containing the following fields:
- **Row ID**: Unique identifier for each row
- **Order ID**: Unique identifier for each order
- **Order Date**: Date the order was placed (mm/dd/yy format)
- **Ship Date**: Date the order was shipped
- **Ship Mode**: Mode of shipment
- **Customer ID**: Unique customer identifier
- **Customer Name**: Name of the customer
- **Segment**: Customer segment (e.g., Consumer, Corporate, Home Office)
- **Country**: Country of the customer
- **City**: City of the customer
- **State**: State of the customer
- **Postal Code**: Postal code of the customer
- **Region**: Sales region (e.g., East, West, Central)
- **Product ID**: Unique product identifier
- **Category**: Product category (e.g., Furniture, Office Supplies, Technology)
- **Sub-Category**: Product sub-category (e.g., Chairs, Phones)
- **Product Name**: Name of the product
- **Sales**: Total sales value for the product

## Objectives
- **Sales Analysis**: Understand sales distribution across categories, regions, and customer segments.
- **Time Series Analysis**: Analyze sales trends over time.
- **Sales Forecasting**: Use historical data to forecast future sales performance.

## Key Metrics & Visualizations
1. **Total Sales**: Overall sales performance across the dataset.
2. **Sales by Category**: Bar chart displaying sales per product category.
3. **Sales by State**: Statewise sales performance visualized on a map.
4. **Sales by Customer Segment**: Pie chart showing the proportion of sales from different customer segments.
5. **Sales Over Time**: Line chart tracking sales across different years and months.
6. **Sales Forecasting**: 12-month sales forecast using historical data.

## Project Workflow
### 1. Data Cleaning and Preparation
- Verified data types for each column (e.g., `Order Date` as Date, `Sales` as Decimal).
- Removed duplicates based on `Order ID`.
- Extracted **Year** and **Month** from `Order Date` for time-based analysis.

### 2. Analysis
- **Sales by Category**: Created a bar chart showing sales distribution across `Category`.
- **Sales by State**: Visualized sales geographically using a map and bar chart.
- **Sales by Segment**: Analyzed sales per customer segment.
- **Sales Trend**: Created a time series analysis to show sales trends over years and months.
- **Sales Forecasting**: Applied Power BI's forecasting feature to predict sales for the next 12 months.

### 3. Visualization
Power BI was used to create interactive dashboards that included:
- Total Sales
- Sales by Product Category
- Sales by State (Map)
- Sales by Customer Segment
- Yearly and Monthly Sales Trends
- Sales Forecasting

## Tools & Technologies
- **Power BI**: Data visualization and dashboard creation.
- **Power Query**: Data cleaning and transformation.
- **DAX (Data Analysis Expressions)**: Used for calculated measures and columns.

## How to Run the Project
To run the project in Power BI:
1. Clone this repository to your local machine.
2. Open Power BI Desktop.
3. Load the dataset (`SalesForecastingData.csv`) into Power BI.
4. Open Power Query Editor to check data cleaning steps.
5. Create visualizations by dragging fields into the Power BI report canvas.
6. Apply DAX measures where necessary to calculate metrics such as `Sales by Category`.
7. Use the built-in forecasting feature to predict future sales trends.

## Future Improvements
- Incorporate additional datasets like marketing spend or customer demographics for more detailed analysis.
- Use advanced predictive models (e.g., R or Python) for more accurate sales forecasting.
- Automate data refresh for real-time updates of dashboards.

## Project Contributors
- **Supriya** - Power BI Developer and Data Analyst
- **Kalyani** - Power BI Developer and Data Analyst
