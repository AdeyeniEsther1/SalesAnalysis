# SALES ANALYSIS 2019

## Table of Contents

- [Project Overview](#project-overview)
- [Problem Statement](#problem-statement)
- [Data Sourcing](#data-sourcing)
- [Skills Demonstrated](#skills-demonstrated)
- [Data Importation and Loading](#data-importation-and-loading)
- [Data Modeling and Transformation](#data-modeling-and-transformation)
- [Analysis and Insights](#analysis-and-insights)
- [Recommendations](#recommendations)
- [Conclusion](#conclusion)

## Project Overview

This project focuses on uncovering trends and patterns in the company’s sales data for the year 2019. The analysis generates key sales metrics and insights aimed at driving informed decision-making for future business strategies.

## Problem Statement
The accountant flagged potential sales downturns during the months of April, May, June, and July, prompting a deeper investigation into overall monthly sales performance. The key objectives of this analysis include:

### 1. Monthly Sales Performance:

- Assessing whether the company experienced losses in April, May, June, and July compared to other months.
- Identifying specific factors or patterns contributing to these potential losses.
- Analyzing overall monthly sales trends throughout the year.

### 2. City-Specific Revenue Analysis:

- Evaluating if Los Angeles, New York, Atlanta, San Francisco, and Seattle are the top revenue-generating cities.
- Comparing these cities to others in terms of sales performance.
- Verifying whether increased marketing efforts in these cities are supported by the data.

### 3. Key Sales Metrics:

- Calculating essential sales metrics for 2019, such as total revenue, average monthly sales, and identifying the highest and lowest performing months.
- Highlighting trends and patterns in sales that can inform future business strategies.

### 4. Actionable Insights:

- Providing recommendations to improve future sales performance.
- Offering suggestions on marketing adjustments, focusing on specific regions or cities.

## Data Sourcing

- The dataset used for this analysis was sourced from [here](https://files.gumroad.com/attachments/2558769275487/d9a06a6634d546d7813af169ed903e12/original/Sale_2019.bak?response-content-disposition=attachment&verify=1725703225-DS4XMkAFzU5Wlw0XpsHH50U88T30TcKmN4RSkzHdCkc%3D]
) and provided as a backup file.
  - After restoring the file, the database was organized with multiple tables containing monthly sales data from January to December 2019.
  - These tables were appended to facilitate easier analysis and visualization.

## Skills Demonstrated
Several skills and tools were utilized in the completion of this project:

### 1. Database Management (SQL Server):

-  Restored databases from .bak files.
  
  ![sales table in sql](https://github.com/user-attachments/assets/d44a6c20-ef3c-42bc-a39b-4b556ce1771f)

-   Managed database paths and settings during the restoration process.

### 2. SQL Querying:

- Developed queries to validate and retrieve data.
-  Interpreted table structures and database relationships.

### 3. SQL Server Management Studio (SSMS):

- Utilized SSMS to navigate, restore, and manage the database.

### 4. Power BI Integration:

- Connected Power BI to the SQL Server database.
- Selected appropriate data connection modes using Power Query.

## Data Importation and Loading

The dataset was successfully connected to Power BI using an SQL Server connection, selecting the appropriate data mode for analysis. This enabled further data modeling and visualization.

## Data Modeling and Transformation

- A total of five tables, 26 measures, and two relationships were created for this analysis.

![model](https://github.com/user-attachments/assets/53809714-cbb1-4f5c-b759-3e48f8edd647)

- Adjustments were made to the automatic model generated by Power BI to enhance performance and enable dynamic filtering.
- A calendar table was added to support time-based analysis, and DAX (Data Analysis Expressions) was extensively used for calculations and data aggregation.

## Analysis and Insights

The report consists of 2 pages, highlighting sales performance, top and bottom-performing products, and city-specific trends.

![dashboard sales analysis 2019](https://github.com/user-attachments/assets/62d9a797-d444-4022-a2c9-d06740a155f9)


### Key Insights:
### 1. Top Cities:

San Francisco, Los Angeles, and New York City emerged as the top revenue-generating cities.

### 2. Monthly Performance:
The highest sales occurred in December ($3.7M), while January recorded the lowest ($1.8M).

### 3. Top Product:
The MacBook Pro Laptop was the highest-selling product, generating over $8M in sales.

### 4. Least-Selling Product:
AAA Batteries (4-pack) was the lowest-selling product, generating only $92K in sales.
Screenshot of Dashboard

## Recommendations

Based on the analysis, here are my primary recommendations:

### 1. Focus on High-Performing Cities: 

San Francisco, Los Angeles, and New York City consistently outperformed others, confirming that marketing efforts should be intensified in these regions.

### 2. Address Underperforming Months: 

January, September, and February showed lower sales volumes, which indicates a need for stronger sales strategies during these months (e.g., promotions or targeted campaigns).

### 3. Product Diversification: 

Emphasize top-selling products while considering the phasing out of underperforming products like AAA Batteries.

## Conclusion

The insights generated from this analysis will guide the company in refining its sales strategy for future periods. egions for marketing efforts were derived based on the findings.

For a detailed view of the dashboards and further analysis, [click here to view the Power BI dashboard](https://app.powerbi.com/groups/me/reports/8b41838f-eef1-45ac-9155-4c13ab207836/79772120a00745809e8d?experience=power-bi)
