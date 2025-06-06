
#### Data Analysis of Apple Sales Using SQL

![boliviainteligente-0rsjxD6Ai7Q-unsplash](https://github.com/user-attachments/assets/343cb0bd-8a2c-4edc-854f-92590808072e)

## Project Overview

This project highlights the use of advanced SQL querying techniques on a large-scale Apple retail sales dataset consisting of more than 1 million records. The dataset provides comprehensive details on products, store locations, sales transactions, and warranty claims from Apple outlets across the globe.

Through solving a variety of questions—ranging from basic to advanced—this project demonstrates the ability to write powerful SQL queries that uncover meaningful business insights from complex datasets.



## Database Schema

The project uses five main tables:

 **stores**: 
   - `store_id`: Unique identifier for each store.
   - `store_name`: Name of the store.
   - `city`: City where the store is located.
   - `country`: Country of the store.

 **category**: 
   - `category_id`: Unique identifier for each product category.
   - `category_name`: Name of the category.

 **products**: 
   - `product_id`: Unique identifier for each product.
   - `product_name`: Name of the product.
   - `category_id`: References the category table.
   - `launch_date`: Date when the product was launched.
   - `price`: Price of the product.

 **sales**: 
   - `sale_id`: Unique identifier for each sale.
   - `sale_date`: Date of the sale.
   - `store_id`: References the store table.
   - `product_id`: References the product table.
   - `quantity`: Number of units sold.

 **warranty**:
   - `claim_id`: Unique identifier for each warranty claim.
   - `claim_date`: Date the claim was made.
   - `sale_id`: References the sales table.
   - `repair_status`: Status of the warranty claim (e.g., Paid Repaired, Warranty Void).


## Project Focus

This project mainly aims to build and demonstrate the following SQL capabilities:

- **Complex Joins and Aggregations**: Showing proficiency in executing advanced SQL joins and aggregating data effectively.
- **Window Functions**: Applying advanced window functions for calculating running totals, analyzing growth, and handling time-based queries.
- **Data Segmentation**: Examining information over various periods to understand how products perform.
- **Correlation Analysis**: Using SQL functions to identify connections between factors like product cost and warranty requests.
- **Real-World Problem Solving**: Responding to business queries that represent practical situations encountered by data analysts.

## Dataset Overview

- **Size**: Over one million rows of sales records.
- **Time Range**: The dataset includes several years, enabling analysis of long-term trends.
- **Geographical Coverage**: ransaction records from Apple outlets in different nations.

