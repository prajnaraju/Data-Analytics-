# Retail Dataset Dashboard (Excel)
This dashboard provides a high-level overview of retail performance using a sample dataset. It is designed to be interactive and easily digestible for quick analysis.

## Key Features:

Top 5 Products by Revenue: A bar chart displaying the top five products based on sales revenue.

## Revenue by Occasion:
 A bar chart showing total revenue attributed to different occasions (e.g., Birthday, Diwali, Valentine's Day).

## Total Revenue by City:
 A table and slicer showing the number of orders and total revenue for various cities.

## Slicer Functionality:
 The dashboard includes a slicer to filter data based on the city, which is supported in Excel 2010 or later.

## How to Use:

The "orders," "customers," "products," "Sheet1," and "Sheet2" tabs contain the raw data used to create the dashboard.

The "Dashboard" tab is the primary view for analysis.

Use the slicer to view data for specific cities.
![image_alt](https://github.com/prajnaraju/Data-Analytics-/blob/aaa7798fcceef5335267077ee7713e1d2e0629ff/17549069279113403515152876110870.jpg)

# Road Accident Analysis Dashboard (Power BI)
This Power BI dashboard provides a comprehensive analysis of road accidents, focusing on casualties, accident types, locations, and year-over-year comparisons.

## Key Features:

## Overall Casualty Summary: 
Displays key metrics such as Total Current Year Casualties, Count for CY Casualties, and Current Year Casualties of fatal, serious, and slight injuries. It also shows the percentage change from the previous year.

## Casualties by Road Type: 
Shows the number of casualties categorized by road types like single carriageway, dual carriageway, roundabout, etc.

## Casualties by Location: 
A map visualizes the geographic distribution of accidents, highlighting hotspots.

## CY Casualties vs. Previous Year:
 A line graph compares current year casualties to the previous year on a monthly basis, allowing for trend analysis.

## Urban/Rural and Dark/Light Conditions:
 Donut charts illustrate the proportion of accidents occurring in urban vs. rural areas and during daylight vs. dark conditions.

## How to Use:

This is a read-only dashboard for viewing.

Clicking on specific visuals (e.g., a bar in a chart or a location on the map) will cross-filter other visuals on the page.

Use the slicers at the top of the dashboard to filter the data by specific criteria if available.
![image_alt](https://github.com/prajnaraju/Data-Analytics-/blob/aaa7798fcceef5335267077ee7713e1d2e0629ff/17549068361687396575428165759349.jpg)

# Pizza Sales SQL Queries
This document contains a set of SQL queries designed for a pizza sales data analysis project. These queries are categorized into Key Performance Indicators (KPIs) and various trends and performance metrics, providing a comprehensive overview of the pizza sales data.

A. Key Performance Indicators (KPIs)
These queries calculate essential metrics to understand overall business performance.


Total Revenue: Calculates the sum of the total_price column from the pizza_sales table.


Result: 817,860.05.


Average Order Value: Divides the total revenue by the number of unique orders.


Result: 38.31.


Total Pizzas Sold: Sums the quantity of all pizzas sold.


Result: 49,574.


Total Orders: Counts the number of distinct order_ids to find the total number of orders placed.


Result: 21,350.


Average Pizzas Per Order: Calculates the average number of pizzas in each order.


Result: 2.32.

B. Daily & Hourly Trends
These queries analyze sales trends based on time.


Daily Trend for Total Orders: Groups orders by the day of the week to show the number of orders on each day.


Hourly Trend for Orders: Groups orders by the hour of the day to identify peak ordering times.

C. Sales Breakdown
These queries break down total sales by different categories and sizes.


% of Sales by Pizza Category: Calculates the percentage of total revenue for each pizza category.


Categories: Classic, Chicken, Veggie, and Supreme.


% of Sales by Pizza Size: Determines the revenue percentage contributed by each pizza size (L, M, S, XL, XXL).


Result: Large pizzas account for the highest percentage of sales at 45.89%.

D. Top & Bottom Performing Pizzas
These queries identify the best and worst-selling pizzas.


Total Pizzas Sold by Pizza Category (for February): Shows the total number of pizzas sold per category specifically for the month of February.


Result: The Classic category sold the most pizzas in February with 14,888 units.


Top 5 Best Sellers: Identifies the top 5 pizza names with the highest quantity sold.


Result: "The Classic Deluxe Pizza" is the top seller.


Bottom 5 Best Sellers: Finds the 5 pizzas with the lowest quantity sold.


Result: "The Brie Carre Pizza" is the lowest seller with 490 units sold.
