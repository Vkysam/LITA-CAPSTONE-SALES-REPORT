# LITA-CAPSTONE-SALES-REPORT


### DESCRIPTION.

THE DATASET CONTAINS RECORDS ON CAPSTONE SALES PERFORMANCE BY REGION, QUANTITY SOLD, UNIT COST, ORDERDATE AND PRODUCTS SOLD BETWEEN 2023-2024.

### PROJECT OVERVIEW

This data Analysis project aims to give insights on the sales performance pf the CAPSTONE DATASET AND THE SUBSCRIPTION DATASET
project for a period of two years. These analysis will help make informed decisions for a possible growth strategies.

### SUMMARY

This is an exploration of the CAPSTONE sales dataset to uncover key insights such as top-selling products, regional
performance, and monthly sales trends.

### GOAL

The goal is to produce an interactive and understandable analysis for an informed growth strategy for the Capstone and [ackage subscription company.

### DATA SOURCES
The primary source of Data used here is an Excel data file, CSV file.

### TECHNOLGY USED
Excel sheet
excel SUM and AVERAGE functions
Excel pivot table
SQL SERVER
POWER BI

### TOOLS USED
- Microsoft Excel [Download here](https://www.microsoft.com)
1. Data cleaning
2. Data Visualization
3. calculations
4. Analysis
- SQL-structured query language for data querrying
- Github- for porfolio Building

### SKILLS
1.Data Analysis
2.Data Visualization
3.Data Cleaning
4.Data EXPLORATION

### DATA CLEANING AND PREPARATION
- On the initial phase of Data cleaning and preparations, I performed the following action;
  1. Data loading and inspection
  2. Handling missing variables
  3. Data cleaning and formatting
      
### EXPLORATORY DATA ANALYSIS
EDA involved the exploration of the data to answer some questions about the Data such as:
-What product is the highest selling?
-what is the overall sales trend?
-what region has the highest sales?

### DATA ANALYSIS- SQL
```SQL
SELECT * FROM [LITA CAPSTONE DATASET_1]
WHERE CONDITION =
```

```SQL
select product, SUM(Quantity) as totalsales
from [LITA Capstone Dataset_1]
Group by Product 
order by 2 desc
```

```SQL
SELECT
  Region,
  MIN(Quantity) AS minsales,
  MAX(Quantity) AS maxsales,
  COUNT(Region) AS rowcount_,
  SUM(Quantity) AS Totalsales,
  AVG(Quantity) AS avgsales
FROM
  [LITA CAPSTONE DATASET_1]
GROUP BY
  REGION
ORDER BY
  REGION ASC;
```

```SQL
SELECT
  Product,
  SUM(Quantity) 
FROM
  [LITA CAPSTONE DATASET_1]
GROUP BY
  Product
ORDER BY
     SUM(Quantity) desc;
```

```SQL
SELECT TOP 5
  Customer_ID,
  SUM(Quantity) AS totalpurchaseamount
FROM
  [lITA CAPSTONE DATASET_1]
GROUP BY
  Customer_Id
ORDER BY
  SUM(quantity) DESC;
```


### DATA VISUALIZATION

### ANALYSIS
![Screenshot 2024-10-25 035030](https://github.com/user-attachments/assets/655589fb-7b8f-430c-9a2a-25bde47d5f56)

![Screenshot 2024-10-17 161255](https://github.com/user-attachments/assets/bbd08bb0-6f65-42d6-a477-645967dbcb5e)

![Screenshot 2024-10-17 161202](https://github.com/user-attachments/assets/63e37448-ed01-4df6-9749-f43d7f203572)

![Screenshot 2024-10-28 123532](https://github.com/user-attachments/assets/82c125c1-cb5d-4cfd-b9f9-725d7af9ce11)






### CUSTOMER DATA ON PACKAGE SUBSCRIPTION

![Screenshot 2024-10-21 104818](https://github.com/user-attachments/assets/cc6e434d-7726-4b3d-8946-a8c5eb18b6bc)

![Screenshot 2024-10-21 104833](https://github.com/user-attachments/assets/74019b63-abf0-4d2d-acf6-6a7dd1905bc7)

![Screenshot 2024-10-21 104347](https://github.com/user-attachments/assets/1cc4a4c0-3f1b-4eda-b243-8a9f8102b01d)

![Screenshot 2024-10-21 104333](https://github.com/user-attachments/assets/c6f3f258-97f6-4e72-9448-557f11ffe3a4)



💻
