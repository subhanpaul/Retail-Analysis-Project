This repository contains the code and data for performing a comprehensive analysis of a retail dataset. The dataset includes various details about sales transactions, such as order information, product details, and pricing. The primary goal of this analysis is to gain insights into sales performance, identify top-performing products, and observe trends over time.
# Dataset
## The dataset contains the following columns:
Order Id: Unique identifier for each orderOrder
Date: Date when the order was placed
Ship Mode: Shipping method used for the order
Segment: Customer segment (e.g., Consumer, Corporate, Home Office)
Country: Country where the order was placed
City: City where the order was placed
State: State where the order was placed
Postal Code: Postal code of the delivery location
Region: Region where the order was placed
Category: Product category (e.g., Furniture, Office Supplies, Technology)
Sub Category: Product sub-category (e.g., Chairs, Paper, Phones)
Product Id: Unique identifier for each product
Cost Price: Cost price of the product
List Price: Selling price of the product
Quantity: Quantity of the product ordered

 ## Analysis Goals
The analysis is structured to address the following key objectives: Top 10 Highest Revenue Generating ProductsIdentify the products that generate the most revenue.Top 5 Highest Selling Products in Each RegionDetermine the highest selling products in different regions.Month Over Month Growth Comparison for 2022 and 2023 SalesCompare sales growth on a month-over-month basis between 2022 and 2023.Highest Sales Month for Each CategoryIdentify the month with the highest sales for each product category.Sub Category with Highest Growth by Profit in 2023 Compared to 2022Determine which sub-category had the highest growth in profit in 2023 compared to 2022

## Project Structure 
The project is organized as follows:data_cleaning_and_transformation.py: Python script for data cleansing and transformation.load_data.sql: SQL script for loading the cleaned data into a SQL database.analysis_queries.sql: SQL script containing the queries for the analysis.README.md: This file, providing an overview of the project.

## Data Cleansing and Transformation
Data cleansing and transformation were performed using Python to ensure the dataset is clean and suitable for analysis. The following steps were taken:Removed duplicates and irrelevant data.Filled missing values where applicable.Converted data types to appropriate formats.Added calculated fields such as revenue and profit.

## SQL Analysis
The transformed data was loaded into a SQL database for further analysis. The analysis was performed using a series of SQL queries to address the objectives mentioned above. The SQL scripts are provided in this repository for reference and reuse.

## Results
The results of the analysis will provide valuable insights into the sales performance, helping to make data-driven decisions for improving sales strategies and identifying growth opportunities.
