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
- Power BI [Download here](https://github.com/Oluwakemi-moyin/LITA_DB-DATA-ANALYSIS/blob/0756a86d2c9868b3f3c3ab6bdbfa9ade1973f43e/LITA%20INVENTORY%20ANALYSIS.pbix)
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

![Screenshot 2024-11-13 190114](https://github.com/user-attachments/assets/c1ca987e-a33b-4d77-8f6d-9453532dc8a0)


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
   - In 2014, North East brought in the the highest total revenue of 12,489,746,040 USD followed by South West. However, North Central brought in the lowest total revenue of 
     4,318,864,800 USD.
   - In 2015, North East brought in the the highest total revenue of 6,152,217,480 USD followed by South West. However, North Central brought in the lowest total revenue of 
     2,170,467,840 USD.

3. Revenue Distribution
   - The line of business that brought the bulk of revenue is the Service plan bringing in 71.02% of the total Revenue. While Printer sale brought in 8.29% which is the lowest % 
     of total revenue.
   - Revenue is not evenly distributed among the regions. With North East and South West bringing in the bulk of revenue for the company compared to other regions.
   - In 2014, the Company's total revenue was 4746.46% more than the Target of 1billion usd for the year.  It met the target and exceeded by 2356.74% in Year 2015.
4. Strategic Implication
   - The company generates more Revenue from the Service Plan compared to other line of businesses.
   - Printer sales generated the lowest total revenue.
   - The Top two best regions where the company generates the most revenue are North East and South West.
   - The lowest performing region is the North Central.
   - Data for Year 2015 is not complete, as we only have record of January to June so we cannot make concrete conclusion about the year's performance compared to Year 2014.
   
### Conclusion
---
These are my recommendations;
1. The Company should focus on ways of generating more sales from the Service plan since that is the best performing plan. More Sales will lead to greater Revenue for the 
   Company. These could be through Sales Promos, Discounts,etc.
2. Implementation of ways to increase sales in the North Central region which can help boost the region's total revenue.
3. The company needs to decide if Printer sales as a line of business is profitable to the company and if it is worth continuing, as it brought in the lowest revenue in both 
   years in review.

## Region by Units Sold

### Exploratory Data Analysis 
---
The use of tables to organize, summarize, and analyze datasets, making it easier to discover patterns and insights in the dataset.

![Screenshot 2024-11-10 221303](https://github.com/user-attachments/assets/780e7192-f829-48e9-962c-e9a05e67f80d)



### Data Visualization
---
Filtered chart for year 2014

![Screenshot 2024-11-13 192239](https://github.com/user-attachments/assets/f050e477-f5e0-4b87-9136-98dcf4b29356)



Filtered chart for year 2015

![Screenshot 2024-11-13 192302](https://github.com/user-attachments/assets/d1b619a0-7819-41c6-bbbe-f5a0ca4d5618)




### Inferences:
---
1. Overall Total Sales Trends
   - In 2014, Total sales was 517,013units.
   - In 2015, the figures dropped lower by 47.8% to 269,665units which is almost half of the value for the previous year.
   - In 2014, June had the highest total sales of 46,045units of which majority was from Parts and the month with the lowest total sales is January with 39,350units
   - In 2015, March  had the highest total sales of 46,656units and the month with the lowest total sales is February with 43,738.
2. Regional Performance
   -In 2014, the region with the highest total units sales of 138,582units was the North East, closely followed by South west with 110,502units.While the region with lowest 
     total sales was North Central with 35,887units.
   - In 2015,North East had the highest total sales of 70,401units, closely followed by South west with 59,228units sold. North central brought in the lowest sales of 
     18,365UNITS.
3. Sales Distribution
   - The line of business that brought in the bulk of total sales is Parts with 62.77% of the total units sold closely followed by Service plan with 32.77% of total sales. The 
     least performing line of business of the company is Printer sales with 1.63%$ of total sales.
    - Although Parts has the bulk of total sales, overall, it still has a much lower contribution to total revenue compared to Service plan.
    - Ekiti Market has the highest sales of 51,386 which is 6.53% of the overall total sales for both periods. Osun Market had the lowest sales of 1.35%of the overall total 
      sales.
    - Number of stores reduced from 132 in Year 2014 to 128 in Year 2015. KWALI, BOKI, Chibok and Isiala Ngwa SOUTH have the lowest sales in Year 2014. However, in 2015 , the 4 
      stores recorded no sales at all.
      recorded no sales at all.
    - Kwali sold 4units of Model: 4500P in April 5, 2014. No sales was recorded in Year 2015.
    - Isiala Ngwa South sold 54 units of Model: 4500P in July 18 of year 2014. No sales was recorded in Year 2015.
    - Boki store sold 1 unit of Model: 4500Pin February 9, 2014 and 1unit in June 17 2014. No sales was recorded in Year 2015.
    - Chibok store sold 42units of Model 4500C in December 8, 2014.  No sales was recorded in Year 2015.
    - Akinyele store had no record of sales from Month April to June in Year 2015.
4. Strategic Implication
   - Although Parts has the bulk of total sales, overall, it still has a much lower contribution to total revenue compared to Service plan.
   - This could be as a result of lower prices for PARTS compared to SERVICE PLAN.
   - The month of January is an overall low sales month for the company for both periods in review.
   - 4 stores have consistent low sales. No sales was recorded for these stores(KWALI, BOKI, Chibok and Isiala Ngwa SOUTH) in Year 2015. These brought in no revenue for the 
     Company in the year 2015.
     
### Conclusion
---
These are my recommendations;
1. The company should introduce January special sales with lower prices to increase total sales in that period going forward. As a higher total sales leads to higher revenue for 
   the company.
2. There should be a price review for PARTS. Higher prices will lead to higher total Revenue.
3. The company should introduce other Models from both Service Plan and other Line of business to the Stores that have low sales like Boki , Kwali, Isiala Ngwa South and Chibok. 
   This should help increase total sales in these stores. Their progress should be closely monitored for feedback.
4. Boki and Kwali stores should be considered for closure as they are bringing little or no sales to the Company.
   
## Region by Average Revenue

### Exploratory Data Analysis 
---
The use of tables to organize, summarize, and analyze datasets, making it easier to discover patterns and insights in the dataset.

![Screenshot 2024-11-10 221414](https://github.com/user-attachments/assets/234f7ce3-9347-4006-9033-24e58836492a)


### Data Visualization
---
- Filtered chart for year 2014

![Screenshot 2024-11-13 204149](https://github.com/user-attachments/assets/45494090-8db5-4978-9b2b-4766cfe3bee6)


- Filtered chart for year 2015

![Screenshot 2024-11-13 204310](https://github.com/user-attachments/assets/3e32fad0-1b72-4787-9e8b-2e8f8b3b41f2)


### Inferences:
---
1. Overall Revenue Trends
   - In 2014, The average revenue was 2,383,427.2USD.
   - In 2015, The average revenue was 2,347,575.9 USD .
   - When Sum of units sold is more than 60units, the average revenue is 11,759,565.90 USD higher compared to other values.
   - When sum of units sold is 2units or less, the average revenue is 1,941,176.79 USD lower tha other values.
2. Regional Performance
   - In 2014, North central had the highest average revenue of 3,525,603.9USD While South East had the lowest average revenue of 2,146,641.3USD.
   - In 2015, North central had the highest average revenue of 3,500,754.6 USD While North East had the lowest average revenue of 2,127,322.8USD.
3. Revenue Distribution
   - Service plan brought in the highest % of average revenue of 39.19% while Parts brought in 5.08% of the overall average revenue.
4. Strategic Implication
   - There is a positive relationship between Sum of units sold, average revenue and revenue. A higher Total sales leads to a higher average revenue and consequentially, a 
     higher total revenue.
   - The company generates more Revenue on the average from the Service Plan compared to other line of businesses.
   - Printer sales generated the lowest revenue on the average.
   - North central had the highest average revenue due to the fact that it has the lowest number of stores under the region (8 stores)
### Conclusion
---
These are my Recommendations;
1. The Company should focus on ways of generating more sales from the Service plan since that is the best performing plan. More Sales will lead to greater Revenue for the 
   Company. These could be through Sales Promos, Discounts,etc.
2. Implementation of ways to increase sales in the North Central region which can help boost the region's total revenue.
3. The company needs to decide if Printer sales as a line of business is profitable to the company and if it is worth continuing, as it brought in the lowest revenue in both 
   years in review.


### Tables
🥇💻
1. TOTAL REVENUE

|2014|2015|TOTAL REVENUE|
|-----|-----|-----|
|48,464,608,200.00|24,567,382,080.00|73,031,990,280.00|

2. TOTAL AVERAGE REVENUE

|2014|2015|TOTAL AVERAGE REVENUE|
|-----|-----|-----|
|2,383,427.18|2,347,575.93|4,731,003.10|

3. Total Units Sold

|2014|2015|TOTAL UNITS SOLD|
|-----|-----|-----|
|517,013.00|269,665.00|786,678.00|



