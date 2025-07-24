# DSA-Documentation-
This is where I started my Portfolio building while taking my Data Analysis class with the Incubator Hub
I have learnt quite a numeber of things ranging from Excel to SQL and now to my Portfolio building.

## Project Topic: Analysis of Business Transaction in DSA Mall from different Branches
## Table of Contents
- [Project Overview](#ProjectOverview)
- [Data Sources](#DataSources)
- [Tool Used](#ToolUsed)
- [Data Cleaning and Preparation](#DataCleaningandPreparation)
- [Explorative Data Analysis](#ExplorativeDataAnalysis)
- [Data Analysis](#DataAnalysis)

## Project Overview
This project aims to compile the report of various business transactions in DSA mall across three branches; Australia, Bosnia and London. At the end of this project we were able to deduct which branch had the highest revenue for our business, which gender purchased more in all branches and total sales per branch.

With this data, we could plan where and how to invest into our business to make more revenue for the company.


## Data Sources
The primary data source here is from the DSA Mall Transaction CSV file. This was generated from ChatGPT following a prompt I imputed. This file was exported to Excel, then SQL environment for data analysis.

### Tool Used

- Ms Excel for data collection [Download Here](https://www.microsoft.com)
   - for data cleaning
     1. Data Manipulation
     2. Data Munching
- SQL (for Query and Analysis)
- Power BI(for creating a report)
- MS Powerpoint(for presentation)

#### Data Cleaning and Preparation
In the initial stage of data cleaning and preparation , we perform the following functions

- Data loading and inspection
- Handling missing variables
- Data Cleaning and formatting

### Explorative Data Analysis
This involves exploring of the data to answer some questions about the data such as:

- What is the total sale for each branch?
- Which branch makes the highest revenue?
- Which gender purchase more items from the malls?

### Data Analysis
This is where we used some queries to get the result of the above questions from our data.
E.g

```  SQL
Select Branch, sum([Transaction Amount]) as [Total Sales]
from [dbo].vw_DSA_MALL_Transactions
group by Branch
Order by [Total sales] desc










