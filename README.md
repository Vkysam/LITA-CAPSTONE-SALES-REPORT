# LITA-CAPSTONE-SALES-REPORT

### DESCRIPTION
THE DATASET CONTAINS RECORDS ON CAPSTONE SALES PERFORMANCE BY REGION, QUANTITY SOLD, UNIT COST, ORDERDATE AND PRODUCTS SOLD BETWEEN 2023-2024.

### OVERVIEW

### SUMMARY
This is an exploration of the CAPSTONE sales dataset to uncover key insights such as top-selling products, regional
performance, and monthly sales trends.

### GOAL
The goal is to produce an interactive and understandable analysis for an informed growth strategy for the Capstone company.

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
3. calcutions
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

### ANALYSIS- EXCEL




### DATA VISUALIZATION
![Screenshot 2024-10-21 010406](https://github.com/user-attachments/assets/4da46a9d-72a4-4d7a-94cf-c4d5c56e0c20)

![Screenshot 2024-10-21 012250](https://github.com/user-attachments/assets/4f98a0f2-6515-4408-afd9-6d47e2853032)

![Screenshot 2024-10-21 012326](https://github.com/user-attachments/assets/0de97086-00c3-46d9-ac53-03ad16156b09)

![Screenshot 2024-10-21 013013](https://github.com/user-attachments/assets/a3de15fb-24dd-4f18-aa66-6473ca090421)

![Screenshot 2024-10-21 013250](https://github.com/user-attachments/assets/87868a84-4387-4e8f-ad0c-600e0377d649)

![Screenshot 2024-10-21 013551](https://github.com/user-attachments/assets/bde88f18-379e-4558-9616-ff41ad93e3ee)





