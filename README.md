# AdventureWorks Dashboard

### Dashboard Link : https://app.powerbi.com/groups/me/reports/0f0245d0-8761-4ffc-9705-d8cd964d9b65?ctid=12b4fbf9-dea8-4490-bede-9cc40309ad61&pbi_source=linkShare


## Problem Statement

As a newly hired Business Intelligence Analyst at AdventureWorks, a global manufacturing company producing cycling equipment and accessories, you are tasked with providing the management team with a comprehensive way to track key performance indicators (KPIs), compare regional performance, analyze product-level trends, and identify high-value customers.

### Objective

_Using Power BI Desktop, the objective is to:_

Connect and transform the raw data
Build a relational data model
Create calculated columns and measures with DAX
Design an interactive dashboard to visualize the data

### Steps Followed

#### Step 1: Load Data into Power BI Desktop
Loaded multiple CSV files containing information about transactions, returns, products, customers, and sales territories.

#### Step 2: Open Power Query Editor
In the Power Query Editor, enabled "Column Distribution," "Column Quality," and "Column Profile" under the View tab.\
Set column profiling to be based on the entire dataset for a thorough analysis.

#### Step 3: Data Cleaning and Transformation
Identified and handled errors and empty values across different columns.\
Transformed and cleaned data to ensure consistency and accuracy.

#### Step 4: Build Relational Data Model
Created relationships between tables based on common fields such as Product ID, Customer ID, and Sales Territory ID.

#### Step 5: Create Calculated Columns and Measures
Used DAX to create calculated columns and measures for various KPIs such as total sales, revenue, profit, and return rates.

#### Step 6: Design the Dashboard
Added visual filters (Slicers) for fields like Region, Product Category, and Customer Segment.\
Created various visuals to represent KPIs, regional performance, product trends, and high-value customers.\
Bar charts for sales, revenue, and profit comparisons by region.\
Line charts for product-level sales trends over time.\
Pie charts for customer segmentation analysis.\
Card visuals for key metrics like total sales, revenue, profit, and return rates.\
Enhanced the dashboard with company branding elements like logo, color theme, and textual information.

#### Step 7: Publish the Report
Published the report to Power BI Service for access by the management team and other stakeholders.


Following inferences can be drawn from the dashboard;

### [1] Total Revenue: $24.9M
    Total Profit: $10.5M
    Total Orders: 25.2K
    Return Rate: 2.2%
### [2] Revenue Trending:

The graph shows revenue growth from January 2020 to January 2022\
There's a clear upward trend, with significant growth in the latter half of 2021

### [3] Orders by Category:

    Accessories: 17.0K orders
    Bikes: 13.9K orders
    Clothing: 7.0K orders

### [4] Top 10 Products:

    1. Water Bottle - 30 oz.: 
        3,983 orders, $39,755 revenue, 1.95% return rate

    2. Patch Kit/8 Patches: 
        2,952 orders, $13,506 revenue, 1.61% return rate

    3. Mountain Tire Tube: 
        2,846 orders, $28,333 revenue, 1.64% return rate

    4. Road Tire Tube: 
        2,173 orders, $17,265 revenue, 1.55% return rate

    5. Sport-100 Helmet, Red: 
        2,099 orders, $73,444 revenue, 3.33% return rate

    6. AWC Logo Cap: 
        2,062 orders, $35,882 revenue, 1.11% return rate

    7. Sport-100 Helmet, Blue:
        1,995 orders, $67,120 revenue, 3.31% return rate

    8. Fender Set - Mountain:
        1,975 orders, $87,041 revenue, 1.36% return rate

    9. Sport-100 Helmet, Black:
        1,940 orders, $65,270 revenue, 2.68% return rate

    10. Mountain Bottle Cage: 
        1,896 orders, $38,062 revenue, 2.02% return rate

### [5] Monthly Performance:

    Monthly Revenue: $1.83M (3.31% increase from previous month)
    Monthly Orders: 2,146 (0.88% decrease from previous month)
    Monthly Returns: 166 (1.78% decrease from previous month)

### [6] Product Insights:

    Most Ordered Product Types: Tires and Tubes
    Most Returned Product Types: Shorts

#### _Selected Product: Road Tire Tube_

#### Monthly Performance vs Target:

    Orders: 213 out of 234 target 
    Revenue: $1,668 out of $1,804 target
    Profit: $1,044 out of $1,129 target
    Price Adjustment: 0.20%

#### Profit Trends:

Graph shows Total Profit and Adjusted Profit from July 2021 to May 2022 \
Example data point: July 12, 2021 - Total Profit: $30, Adjusted Profit: $39.5484

