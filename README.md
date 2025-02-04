# Project Overview
This project focuses on the analysis and visualization of sales data for a fictional chocolate company using Power BI. The goal is to create an interactive and dynamic dashboard that effectively presents the findings of the sales data analysis, providing insights into product performance, salesperson performance, and other key metrics.

# Quick Link


# Data Collection and Cleaning
The analysis uses five main data tables, all contained in a single Excel file:
- Shipments Table: Contains detailed information about each shipment, including date, salesperson, product, geography, sales amount, and boxes shipped.
- Salesperson Dimension Table: Provides information about the salespersons.
- Product Dimension Table: Contains cost and category information for each product.
- Geography Dimension Table: Contains information about the geographical locations.
- Calendar Dimension Table: Lists all the dates used in the analysis.

Data cleaning steps:
- Data Import: Import all five data tables from the Excel file into Power BI Desktop.
- Data Relationship Establishment: Create relationships between the tables in the Power BI data model using a star schema to ensure accurate data association for analysis.
- Data Type Conversion: Ensure all data columns are in the correct format, such as date and numerical formats.

Tools Used: Microsoft Excel for data storage, and Power BI Desktop for data modeling, calculations, and dashboard development.

# Data Integration and Modeling
In Power BI:
- Data Integration: Relate the five tables through common columns such as "Salesperson", "Product", "Geography", and "Date".
- Data Modeling: Use a star schema to ensure data accuracy and comprehensiveness of the analysis.

# Dashboard Development
This Power BI dashboard includes the following main sections:
1. Summary:
   - Displays key metrics like total sales, total boxes shipped, total shipments, total cost, and total profit.
   - Provides month-on-month changes for these metrics to quickly understand business performance.
   - Uses the new card visual with reference labels to show month-on-month changes.
   - Uses a gauge chart to display profit percentage.

2. Trend Analysis:
   - Uses a line chart to show trends for total sales, total boxes shipped, total shipments, total cost, and total profit.
   - Allows users to switch between different metrics using a slicer to enable in-depth analysis.
   - Uses tooltips to show detailed data breakdowns by geography.

3. Low Box Shipments Analysis:
   - Uses a column chart to show the distribution of shipments across different box ranges.
   - Uses a gauge chart to display the percentage of low box shipments.
   - Uses a zoom slider to control the display range of the column chart.

4. Salesperson and Product Performance:
   - Uses tables to display detailed performance metrics for salespersons or products, including sales, profit, profit percentage, and low box shipment information.
   - Uses icons to indicate if a salesperson has met the profit target.
   - Uses data bars to display the profit percentage.
   - Uses bookmarks to switch between salesperson and product details.

5. Filters:
   - Allow users to filter data by product category or geographical location.
   - Dynamically view different sales analyses by adjusting filters.

Interactive Features:
- Filters: Allow users to filter data by time frame, product category, or geography, for deeper analysis.
- Hover Actions: Provide detailed information when hovering over data points, enhancing user interaction and insight discovery.
- Bookmarks: Allow users to switch between salesperson and product views.
- Zoom Sliders: Allow users to adjust the display range of the column chart.

# Key Insights
- Product Performance: Identifies high and low profit products, aiding in product strategy adjustments.
- Salesperson Performance: Identifies top-performing and underperforming salespersons, helping in sales team management.
- Shipment Analysis: Identifies patterns and impacts of low box shipments, guiding improvements to shipment strategy.
- Month-on-Month Changes: Observes trends of sales and profit over time and provides percentage changes month-on-month.
- Geographical Insights: Provides insights into the distribution of sales by region, highlighting best-performing areas.

# Conclusion
This project demonstrates the ability to perform data cleaning, integration, and visualization techniques in Power BI. The resulting dashboard offers valuable insights into sales metrics, supporting data-driven decisions to enhance business performance.