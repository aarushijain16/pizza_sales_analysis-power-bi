# pizza_sales_analysis-power-bi
This repository features a Power BI report for a comprehensive analysis of pizza sales. The report visualizes crucial business metrics, including total revenue, total quantity sold, &amp; AOV. The dashboard is designed to provide actionable insights by breaking down sales data across various dimensions. 

# Pizza Sales Performance Report
## Executive Summary:
This report analyzes key performance indicators (KPIs) for a pizza sales business, focusing on sales performance, customer trends, and product effectiveness. By visualizing data on total revenue, order volume, and top-selling pizzas, the analysis aims to provide actionable insights for optimizing business operations and sales strategies. The insights derived from such a dashboard are crucial for making data-driven decisions to increase profitability and customer satisfaction.

## Problem Statement:
The primary objective is to transform raw pizza sales data into a clear, interactive dashboard that answers critical business questions, such as:

- What is the total revenue and the average order value?

- Which pizzas are the best-sellers, and which are the least popular?

- What are the peak sales periods (daily, weekly, monthly)?

- How do sales perform across different pizza categories and sizes?

- What is the distribution of orders over time, and what is the total number of pizzas sold?

By addressing these questions, the dashboard provides a foundation for strategic planning, including menu optimization, marketing campaigns, and resource allocation.

## Data Sources and Engineering:
The analysis is based on a structured dataset that includes a set of related tables, with data cleaning and preparation performed in Power BI's Power Query Editor. The core tables contain:

- Order Details: A table with a unique order_details_id for each transaction, and columns for order_id, pizza_id, and quantity.

- Pizzas: A table that links a pizza_id to its pizza_name, pizza_type_id, size, and price.

- Orders: A table with a unique order_id, and columns for date, and time

- Pizza Type: A table with unique pizza_type_id, and columns for name, category, and ingredients.

The data engineering process within the .pbix file would involve establishing relationships between these tables and creating calculated measures (DAX) to derive key metrics. For instance, Total Revenue is calculated by summing unit_price multiplied by order_quantity, and Average Order Value is the result of dividing Total Revenue by the total number of unique orders. These measures form the foundation for all the visualizations.

Methodology:
The Power BI dashboard is designed to provide a comprehensive, multi-layered view of the business. The report follows a logical flow, starting with a high-level overview and progressively drilling down into specific areas.

Summary View: The main page would feature a summary of top-line metrics such as Total Revenue, Total Orders, and Pizzas Sold. This provides an immediate understanding of the business's overall health.

Trend Analysis: Visualizations like line charts track Total Revenue over time (by day, month, or year) to identify seasonal trends and peak sales periods.

Product Performance: Bar charts and tables are used to show the Top 5 best-selling pizzas, categories, and sizes. This helps identify the most popular products and potential areas for menu refinement.

Operational Insights: The dashboard would also include metrics like Average Order Value and the Distribution of Orders by Time of Day, which are crucial for optimizing staffing and store operations.

Key Findings and Impact:
Based on the typical data in a pizza sales dashboard, we would expect to find several key insights:

Sales Performance: The business generates a significant total revenue, with a high volume of orders. The average order value provides a benchmark for sales team performance and promotional effectiveness.

Peak Demand: There is a clear and distinct increase in sales on weekends (e.g., Friday and Saturday) and during peak hours (e.g., lunch and dinner rushes). This finding is essential for optimizing staffing and inventory.

Popular Products: Pizzas in the Classic or Supreme categories are often the most popular, while the Medium or Large sizes contribute the most to total revenue. This indicates strong customer preference for specific products and sizes.

Operational Efficiency: The total number of unique orders reveals the volume of business, while the number of pizzas sold highlights production capacity needs.

Strategic Recommendations:
Based on these findings, here are some actionable recommendations to drive growth:

Optimize Promotions: Offer special promotions or discounts during off-peak hours (e.g., early afternoon on weekdays) to smooth out demand and increase sales.

Menu Engineering: Promote top-performing pizzas more heavily. Consider offering special limited-time versions of the best-sellers or creating combo deals to increase the average order value.

Staffing & Operations: Use the peak demand data to schedule staff more effectively, ensuring sufficient personnel during the lunch and dinner rushes to maintain service quality and speed.

Targeted Marketing: Run targeted marketing campaigns focusing on the most popular pizza categories and sizes. For example, a social media campaign highlighting your Classic pizzas could be highly effective.

Tools and Technologies:
Data Visualization & Analysis: Power BI (using the Pizza_Sales.pbix file)

Data Source: Assumed CSV or Excel files containing order and product information.
