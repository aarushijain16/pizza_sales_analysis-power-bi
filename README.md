# pizza_sales_analysis-power-bi
This repository features a Power BI report for a comprehensive analysis of pizza sales. The report visualizes crucial business metrics, including total revenue, total quantity sold, &amp; AOV. The dashboard is designed to provide actionable insights by breaking down sales data across various dimensions. 

# Pizza Sales Performance Report
## Executive Summary:
This report provides a comprehensive analysis of pizza sales data to identify key trends and business opportunities. The analysis reveals that total revenue reached $817.9k from 21k total orders. Sales are strongest during the afternoon and evening and peak on Fridays. The "Classic" category is the to performer, and specific piizas like "The Classic Pizza" and "The Thai Chicken Pizza" drive significant revenue and quantity sold. Strategic recommendations focus on leveraging these insights to optimize operations and marketing efforts, particularly during peak times. 

## Problem Statement:
The objective of this project is to perform a detailed analysis of pizza sales data to gain insights into customer behaviour and sales performance. The core businesss questions to be answered are as follows:

- What is the peak time of day for orders, and when are orders at their lowest?

- Which day of the week generates the most orders?

- What is the total sales amount?

- Which pizza is ordered the most?

- Which pizza is generating the most sales revenue?

- During which time of day (morning, afternoon, evening, night) do people order more pizzas?

- Which pizza category is the hottest selling?

- What is the average order value (AOV)?

- What is the total number of orders?

- What is the total quantity of pizzas sold?

By addressing these questions, the dashboard provides a foundation for strategic planning, including menu optimization, marketing campaigns, and resource allocation.

## Data Sources and Engineering:
The primary data source for this analysis was a dataset from Kaggle, which was provided as a CSV file. 

- Order Details: A table with a unique order_details_id for each transaction, and columns for order_id, pizza_id, and quantity.

- Pizzas: A table that links a pizza_id to its pizza_name, pizza_type_id, size, and price.

- Orders: A table with a unique order_id, and columns for date, and time.

- Pizza Type: A table with unique pizza_type_id, and columns for name, category, and ingredients.

The data was first subjected to a rigorous cleaning process, including:

- Removing any duplicate entries.

- Renaming the first row to be the column headers for clarity and usability.

- Checking for and handling any null values across all columns.

- Verifying and correcting the data types of each column to ensure accurate calculations.


## Methodology:
The analysis was performed using Power BI and a set of DAX (Data Analysis Expressions) formulas to derive key performance indicators. The following steps were taken:

- **DAX Formulas**: New measures were created using DAX to calculate the Average Order Value (AOV), total sales, total quantity sold, and total number of orders.

- **Calculated Columns**: Additional columns were added to the orders table to categorize data for more granular analysis. These included order hour, day of week, time of day (using bins for morning/ afternoon/ evening/ night), month and month number (to ensure proper sorting of month names).

- **Data Modeling**: Relationships (cardinality) were established between the tables to enable seamless filtering and interaction between different parts of the report.

## Key Findings and Impact:
The analysis provided clear answers to the project's objectives, revealing actionable insights into the business's performance.

- **Time of Day**: Orders are highest in the afternoon and evening, with the lowest orders occuring in the morning and at night. The peak order hour is around 12PM and 1PM, while the quietest hours are from 4AM to 10AM.

- **Day of Week**: Friday is the busiest day, with the hihest number of orders.

- **Total Sales**: The total revenue generated was $817.9k.

- **Most Ordered Pizza**: The most frequently ordered pizza is The Classic Deluxe Pizza.

- **Top Sales-Generating Pizza**: The top-selling pizza by revenue is The Thai Chicken Pizza.

- **Time of Day**: People order more pizzas in the afternoon and evening.

- **Hot-Selling Category**: The Classic pizza category is the top-selling category by revenue.

- **Average Order Value (AOV)**: The AOV for this dataset is approximately $38.31.

- **Total Orders**: The total number of orders placed was 21,350.

- **Total Quantity**: The total quantity of pizzas sold was 49,534.

## Strategic Recommendations:

Based on the key findings, the following recommendations are made:

- **Optimize Staffing and Operations**: Increase staffing levels during peak hours, particularly in the afternoon and evening, and on Fridays, to handle the high volume of orders efficiently and maintain customer satisfaction.

- **Targeted Promotions**: Implement special offers or promotions during low-traffic periods, such as mornings and nights, to encourage orders and boost sales during those times.

- **Menu and Marketing Focus**: Highlight the top-selling pizzas, such as The Thai Chicken Pizza and The Classic Deluxe Pizza, in marketing campaigns. Consider using these successful items to upsell other pizzas or promotions.

- **Category Focus**: Leverage the success of the Classic category by developing new classic-style pizzas or running campaigns specifically for this category to capitalize on its popularity.

Tools and Technologies:

- **Tool**: Power BI

- **Data Analysis Language**: DAX

- **Data Source**: Kaggle

## Visualizations:

The Power BI report includes a variety of visualizations to represent the data effectively:

- **KPI Cards**: Displayed key metrics such as Total Sales, AOV, Total Orders, and Total Quantity.

- **Bar Charts**: Illustrated top-performing pizzas by revenue and quantity, and showed the distribution of orders by day of the week and time of day.

- **Donut Chart**: Showcased the breakdown of sales by pizza category.

- **Area Chart**: Visualized order trends over time, highlighting peak order hours


