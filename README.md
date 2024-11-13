# LITA INVENTORY ANALYSIS

[Project Overview](#project-overview) 

[Data Source](#data-source)

[Data Collected](#data-collected)

[Project Objective ](#project-objective)

[Tools used](#tools-used)

[Key Metrics](#key-metrics)

[Data Cleaning and Preparations](#data-cleaning-and-preparations)

[Dashboard Overview](#dashboard-overview)

[Exploratory Data Analysis](#exploratory-data-analysis)

[Data Visualization](#data-visualization)

[Tables](#tables)

    
### Project Overview
---
Collection and analysis of sales data across the company's various sales regions, markets and stores. The goal of the project is to provide insights into revenue, units sold and transaction category over a two year-period. The analysis focuses on understanding sales performance and revenue trends across various regions and calculating important performance indicators like average revenue and average unit sold per store/region. 
    
### Data Source
---    
Company Sales Data

### Data Collected
---    
This data contains some key columns.
1. Region : The geographical area where each store operates.
2. Market: Market segment/category under the regions
3. Store: Specific locations from which sales data is collated.
4. Unit sold: The number of units sold per transaction.
5. Revenue: The total monetary value generated from each sale.
6. Trade date: The date/time period the sales were made.
7. Model: The product model been sold.
8. Line of business: The business line/category under which the sales falls.
  
### Project Objective  
--- 
This project is to address the following analysis goals.
1. Revenue per Region: Determines the total revenue generated by each region
2. Units sold per Region: Determines the total units sold by each region
3. Average Revenue per Region: shows the average revenue generated by each region to assess performance.
    
### Tools used
---
- Microsoft Excel [Download here](https://github.com/user-attachments/files/17700021/LITA.Class.Inventory.xlsx)
  1. For Data cleaning
- Power BI [Download here](
  1. Analysis and
  2. Visualization
- Github for Portfolio Building

### Key Metrics
---
1. Revenue: calculated by multiplying the selling price of each item by the total units sold for the item.
2. Units Sold: Group the data by region and sum the units sold to identify how much each region sold per year/month/day/fiscal period.
3. Average Revenue: It is used to measure the amount of money a business earns, on average, for each unit of product it sells. It is calculated by dividing the total revenue(TR) a company makes from all its sales by the number of units sold.

### Data Cleaning and Preparations
---
1. Microsoft Excel: used for cleaning the dataset.
2. If function: was used to calculate transaction category using unit sold for each item.
   ```
   Formula: IF($J2<=20, "LOW", IF($J2<=50, "MEDIUM", "HIGH"))
   ```
3. Power BI :
   - for Summarisation of the dataset and
   - for Visualisations.
4. DAX functions :
   - Calculated Columns. e.g Monthly trade date
   ```
   Formula: 'Sheet1 (2)'[Trade Date].[Month]
   ```
   - Calculated Measure e.g Target
   ```
   Formula: 1,000,000,000
   ```
### Dashboard Overview
---



## Revenue by Region

### Exploratory Data Analysis 
---
The use of tables to organize, summarize, and analyze datasets, making it easier to discover patterns and insights in the dataset.

![Screenshot 2024-11-10 221128](https://github.com/user-attachments/assets/fbfc991e-e448-445c-a8c8-18e6ba4c2b4a)



### Data Visualization
---

1. Filtered chart for year 2014
   
![Screenshot 2024-11-11 154436](https://github.com/user-attachments/assets/6ebb90c4-4d7f-49e3-bcdc-0f1aeee56d19)



2. Filtered chart for year 2015

![Screenshot 2024-11-11 154620](https://github.com/user-attachments/assets/215977c7-98ac-4e60-b404-c2ea6f4f2971)



### Inferences
---
1. Overall Revenue Trends
   - Year 2014 had a total Revenue of 48,464,608,200 USD.
   - Year 2015 had a total Revenue of 24,567,382,080 USD.
   - The Total Revenue for Year 2015 dropped from that of Year 2014 by a margin of 49.31%.
   - In Year 2014, the month of MAY had the highest total Revenue of 4,213,543,680 USD WHILE the month of SEPTEMBER had the lowest Total Revenue of 3,876,659,640 USD.
   - In Year 2015, the month of MARCH had the highest total Revenue of 4,300,901,520 USD WHILE the month of FEBRUARY had the lowest Total Revenue of 4,017,994,560 USD.
    
2. Regional Performance
   - In 2014, North East brought in the the highest total revenue of 12,489,746,040 USD followed by South West. However, North Central brought in the lowest total revenue of 4,318,864,800 USD.
   - In 2015, North East brought in the the highest total revenue of 6,152,217,480 USD followed by South West. However, North Central brought in the lowest total revenue of 2,170,467,840 USD.

3. Revenue Distribution
   - The line of business that brought the bulk of revenue is the Service plan bringing in 71.02% of the total Revenue. While Printer sale brought in 8.29% which is the lowest % of total revenue.
   - Revenue is not evenly distributed among the regions. With North East and South West bringing in the bulk of revenue for the company compared to other regions.

4. Strategic Implication
   - The company generates more Revenue from the Service Plan compared to other line of businesses.
   - Printer sales generated the lowest total revenue.
   - The Top two best regions where the company generates the most revenue are North East and South West.
   - The lowest performing region is the North Central.
   - Data for Year 2015 is not complete, as we only have record of January to June so we cannot make concrete conclusion about the year's performance compared to Year 2014.
   
### Conclusion
---
These are my recommendations;
1. The Company should focus on ways of generating more sales from the Service plan since that is the best performing plan. More Sales will lead to greater Revenue for the Company.
## Region by Units Sold

### Exploratory Data Analysis 
---
- The use of tables to organize, summarize, and analyze datasets, making it easier to discover patterns and insights in the dataset.



### Data Visualization
---
Filtered chart for year 2014



Filtered chart for year 2015




### Inferences:
---
1. Overall Revenue Trends
   - 
2. Regional Performance
   -
3. Revenue Distribution
   -
4. Strategic Implication
   - 
### Conclusion
---

## Region by Average Revenue

### Exploratory Data Analysis 
---
- The use of tables to organize, summarize, and analyze datasets, making it easier to discover patterns and insights in the dataset.




### Data Visualization
---
Filtered chart for year 2014


Filtered chart for year 2015




### Inferences:
---
1. Overall Revenue Trends
   - 
2. Regional Performance
   -
3. Revenue Distribution
   -
4. Strategic Implication
   - 
### Conclusion
---


### Tables
🥇💻
1. TOTAL REVENUE

|2014|2015|TOTAL REVENUE|
|-----|-----|-----|
|48,464,608,200.00|24,567,382,080.00|73,031,990,280.00|

2. TOTAL AVERAGE REVENUE

|2014 DATA|2015 DATA|TOTAL AVERAGE REVENUE|
|-----|-----|-----|
|2,383,427.18|2,347,575.93|4,731,003.10|

3. Total Units Sold

|2014 data|2015 data|TOTAL UNITS SOLD|
|-----|-----|-----|
|517,013.00|269,665.00|786,678.00|



