# EXCEL-SALES-ANALYSIS-

 # Project Title: Coffee Shop Sales Analysis


## Project Overview
This data analysis project is aim to generate insights into the total sales and product performance from a coffee shop and its franchise. Using the various parameters given to analyze, we seek to gather various insights to make compelling insights to make decisions that will improve the performance of the coffee.

## Data Sources
The data source is an excel csv. file obtained from mavin analytic.io. This file contains information like, Transaction id, transaction time, transaction date, product id, product category, etc... 

## Tools Used
- Microsoft Excel for data gathering, data preparation and data analysis
- Git Hub for portfolio building

## Objectives

- Data Preparation: Profile and Prepare data for analysis.

- Exploratory Data Analysis (EDA): Perform basic exploratory data analysis with pivot tables.

- Visualizations: Build a dynamic dashboard to visualize patterns and trends

## Project Structure

1. Data Preparation

 ![Screenshot (29)](https://github.com/user-attachments/assets/a377644d-eb80-4ef9-a34f-d43487564678)

- Taking a moment to familiarize with the data.
- Add a new column to calculate Revenue (`price*quantity`)
- Add new columns to calculate Month and Day of Week based on the transaction date (`month function , week function`)
- Add a new column to extract Hour from the transaction time (`hour function`)


2. Data Exploration With Pivot Table
- Insert a PivotTable on a new tab to show revenue by month
- Add two more PivotTable to show the number of transactions by day of week and by hour of day
- Add a PivotTable  to show the number of transactions by product category sorted descending by transactions
- Add a PivotTable  to show the number of transactions and revenue byproduct type, sorted descending and filtered to the Top 15 by transactions


3. Visualizations
- Add Pivot Charts to show revenue by month as a line chart. Then transactions by day of week and hour of day as column charts, and transactions by product category as a bar chart.
- Assemble the charts into a rough dashboard layout, and include space for the PivotTableshowing Top 15 product types. 
- Add a slicer for store location, and connect it to all of the PivotTables on the sheet.
- Adjust formatting. alignment and polish to finalize the dashboard.



![Screenshot (34)](https://github.com/user-attachments/assets/ef8e25d9-dfd1-40a1-92d8-7602004d850f)


The dashboard shows reports which include:
- Total Revenue by Month
- Transaction by Day of Week 
- Transaction by Hour
- Transaction by Product Category 
- A pivot table showing top 15 product types 
- A slicer to filter by store location. 


## FINDINGS

![Screenshot (56)](https://github.com/user-attachments/assets/100e4409-5ccf-4575-bef6-31925970411c)

- The dashboard has a title **THE COFFEE STABLE**. 
- The general dashboard shows the month with the highest revenue to be June .
- Friday, Thursday and Monday appears to be the days of the week with the highest transaction. While Saturday seems to have the lowest transaction.
- 10AM has the highest transaction hour probably due to the rush hour. While the lowest transaction hour is 6AM.
- Coffee is the most purchased product category. While packaged chocolate has the lowest sales.
  
## Insight

###  Based on Store Location 
**ASTORIA**
![Screenshot (61)](https://github.com/user-attachments/assets/68a71286-0762-4c16-9a5f-106a75b55dba)

- The report shows the month with the highest revenue to be June.
-Thursday appears to be the day of the week with the highest transaction.While Saturday seems to have the lowest transaction. 
- 10AM has the highest transaction hour probably due to the rush hour.While the lowest transaction hour is 2PM(14:00).
- Coffee is the most purchased product category. 
- Coffee Beans, Loose Tea, Branded have low sales.and packaged chocolate has no transactions.
- The top 3 products are Brewed Chai tea, Gourmet brewed coffee and Barrister Espresso.While Biscotti, Regular syrup and sugar free syrup are the bottom 3 products being sold. 


**HELL'S KITCHEN**

![Screenshot (63)](https://github.com/user-attachments/assets/43cb97f5-af50-4f1d-9d5a-d73430ada169)

The top 3 products are Barista Espress
- The month June consistently appears to have the highest revenue. 
- Tuesday and Friday both have the highest transaction.While Sunday has lowest transaction.
- 10AM remains the highest transaction hour and is tightly followed by 9AM, 8AM and 7AM.While the lowest transaction hour is 8PM(20:00).
- Coffee is the most purchased product category. 
- Coffee Beans, Loose Tea  have low sale and packaged chocolate, Branded have no sales in this store. 
- The top 3 products are Barrister Espresso, Brewed Chai tea and Gourmet brewed coffee.While Biscotti, Regular syrup and sugar free syrup are the bottom 3 products being sold.

LOWER MANHATTAN 

![Screenshot (62)](https://github.com/user-attachments/assets/0ab1dc53-8e91-4538-9636-bbdb54f34f8e)

- The report shows June to be  the month with the highest revenue.
- Monday appears to be the day of the week with the highest transaction.While Sunday has lowest transaction.
- 10AM remains the highest transaction hour.While the lowest transaction hour  are 7PM (19:00) and 8PM (20:00).
- Coffee is the most purchased product category. 
- Coffee Beans, Loose Tea, Branded have low sales and packaged chocolate has no transactions.
- The top 3 products are Barrister Espresso, Gourmet brewed coffee and Brewed Chai tea.While Biscotti, Regular syrup and sugar free syrup are the bottom 3 products being sold. 

From this report, Hell's Kitchen has the highest revenue at the month of June at **$56,957**. Astoria follows suit at **$55,083**.
Lower Manhattan store's has a monthly revenue of **$54,446** in the month of June. 


## Conclusion/Recommendations 

This project has highlighted some insights into customers interest and time of purchase. Products like  Coffee Beans, Loose Tea, Branded have and packaged chocolate, should stop being sold so as to save money and channel the income in the purchase of more Coffee. 
Lower Manhattan and would have to close early in other to save up operations cost as less sales are made by 7PM AND 8PM. Lower Manhattan would have to produce less coffee or products during the weekend, and use more of the resources on monday.

This project shows how data analysis can project lapses from this coffee stores and provide ways the various stores can be more efficient and productive, by reducing liabilities and investing in more assets to boost sales. 
 

