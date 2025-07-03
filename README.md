# INCUBATOR HUB PROJECT
### TOPIC: AMAZON PRODUCT REVIEW ANALYSIS

This project is to present an indepth analysis of Amazon products,using Microsoft Excel to uncover insights related to pricing,reviews,ratings and potential revenue.The Dashboard provides key performance indicators (KPIs) and charts to guide business Decisions.

---

### Dataset Overview

- **Source**:Amazon product listing dataset 
- **Size**:1465 products
  
 #### OBJECTIVES

   - Average Discount Percentage per Product Category.
   - Numbers of Products Listed per Category.
   - Total Numbers of Reviews per Category.
   - Products with the highest Average Ratings.
   - Average Actual Price vs Discounted Price per Category.
   - Products with the Highestnumber of Reviews.
   - Products that have a discount >= 50%.
   - Distribution of Products Ratings.
   - Total Potential Revenue( Actual Price * Rating Count) by Category.
   - Number of Unique Products per Price Range Bucket .
   - Rating vs Level of Discount.
   - Numbers of Products with <1000 Reviews.
   - Categories with products that has Highest Discounts,
   - Top 5 Products in terms of rating and number of reviews combined.
   - An Excel Dashboard with cleaned Dataset and Pivot Output.
    
- **Columns Provided**:
   - Product ID
   - Product Name
   - Category
   - Discounted Price
   - Actual Price
   - Discounted Percentage
   - Rating
   - Rating Count
   - About Product
   - User ID
   - Review ID
   - Review Title
   - Review Content
   - Image Link
   - Product Link
 
  ---

  #### TOOLS USED

  - Microsoft Excel
  
- **Columns Analyzed**:
   - Product Name
   - Product ID
   - Category
   - Actual Prices
   - Discounted Prices
   - Ratings
   - Rating Counts
   - Discounts (%)

---

During cleaning of the provided dataset, I removed all duplicates from Product ID (Reducing my dataset size from 1465 to 1351) . I also split my Category into sub categories ( Main Category,Level 2 category,Level 3 Category,Level 4 Category).
  
Afterwards I deleted unnecessary columns from the provided dataset.
    
---

- **Columns Generated**:
   - Main Category
   - Level 2 Category
   - Level 3 Category
   - Level 4 Category
   - Price Range Bucket
   - Discount Range
   - Discount Range Bucket
   - Total Potential Revenue
   - Average Rating
   - Products with >= 50% Discounts
   - Number of Products by Rating + Number of Reviews
   - Top 5 Products
   - Average Discount % by Product Category
   - Products with Highest Reviews
   - Products with Highest Average Ratings

-  **Functions used** :

    - REMOVE DUPLICATE
    - COUNTIF
    - SUM
    - AVERAGE
    - MAX
    - COUNTA
    - IF
    - IFs
    - LARGE

##### Excel Dashboard with Charts and KPI cards.
    
 - **Charts used**:
   
    - Bar Charts
    - Clustered column Charts
    - Scatter plots
    - Pie Chart

- **Charts for**:
  
   - Rating vs Discount Level
   - Numbers of Products per Category
   - Product Distribution Rating
   - Average Discounted Price & Actual Price per Category
   - Number of Unique Product per Price Range Bucket
   - Categories with Products with Highest Number of Discounts
   - Total Potential Revenue per Category
   - Numbers of Products per Category
   - Number of Reviews per Category
   - Top 5 Products by Rating + Number of Reviews
     
- **KPI Cards for**:

   - Total Revenue
   - Average Rating
   - Number of Reviews
   - Average Discounts
   - Product Count
   - Count of Products >= 50% discount
   - Numbers of Products with <1000 Reviews
   - Top Product
   - Product with Highest Avg. Rating
   - Product with Highest No. of Reviews
   - Product with Highest Discount

---

- **Dataset Size after Analysis**:1351 products

#### AUTHOR

**KOLAPO ILERIOLUWA GREAT-GRACE**
 Data Analyst / Excel. Power BI .SQL /

---













### TOPIC: Palmoria Group HR Analysis

This project is to Analyze the company Data and generate insights Palmoria group management needs to address.Using PowerBI to uncover insights related to Employees Gender status,Filter employees that no longer work with the organization,Filter Departments that are no longer existing.The Dashboard provides charts to guide business Decisions on gender related issues within the organization and its Regions.

---

### Dataset Overview

- **Source**:Palmoria Group Dataset
- **Size**:1015 Rows

---
 
 #### OBJECTIVES

 - Gender distribution based on Region and Departments
 - Ratings based on Gender
 - Gender pay gap based on Department and Regions
 - Pay distribution of employees
 - Bonus to be Paid to Employees
 - Total Amount to be paid
 - Total Amount to be paid per Region and company wide
 
-  **Columns Provided**:
  
    - Name
    - Gender
    - Department
    - Salary
    - Rating
    - Location
 
  ---

  #### TOOLS USED

  - Microsoft PowerBI
  
- **Columns Analyzed**:
   - Name
   - Gender
   - Department
   - Salary
   - Rating
   - Location
   - Attributes
   - Values

---

 To begin the analysis ,I exported the dataset provided to microsoft excel worksheet. Where I replaced gender column that were blank with "Undisclosed".I imported my refined dataset from my excel workbook (CSV Mode) into PowerBI Power query editor field.During cleaning of the provided dataset, I removed all "NULL" from Department column.(Reducing my dataset size from 1015 to 946) . 
 
 While trying to apply the bonus Rules for the Dataset, and also imported the bonus rules (excel mode) into my powerBI query editor field.I Re-Arranged it by Unpivoting columns except the Department column .I created a unique relationship for both tables  by creating custom columns on both table (Department Rating). I merged both tables for transformation (Using the Merge Query). 

 Afterwards I cleaned datasets,checked the Data quality,Data Distribution,column profile,Rename column to suit my Requirements,Replaced blank numerical rows with (0),created custom columns and conditional columns to generate necessary required columns for the analysis.
 Then proceeded to creating Measures and Columns on my Model interface to generate fields needed for my visualization.
    
---

   - **Measures Created**:
      - Average Rating By Gender
      - Average Salary By Gender
      - Bonus Amount
      - Employee Count
      - Employees below Minimum Salary
      - Gender Count
      - Gender Percentage
      - Rating Count by Gender
      - Rounded Bonus Amount
      - Salary Count by Department

  - **Columns Created**:
     - Department Rating
     - Rating Score
     - Bonus Rate
     - Total Amount to be Paid

 - **Functions used** :

    - COUNT
    - CALCULATE
    - ALL
    - DIVIDE
    - AVERAGE
    - IF
    - SUMX
    - LARGE
    - FILTER
    - COUNTX
    - SWITCH

####  VISUALIZATION HIGHLIGHTS
    
 - **Charts used**:
   
   - Bar Charts
   - Column Charts
   - Scatter plots
   - Pie Chart
   - Table

- **Charts for**:
  
  - Gender Distribution Analysis
  - Ratings Insights based on Gender
  - Salary Structure and Gender Pay Gap Analysis
  - Minimum Salary Requirement Analysis
  - Bonus Payment Calculation
     
- **Slicers for**:

  - Region & Department
  - Gender
  - Region
  
---

- **Dataset Size after Analysis**: 946 Rows

#### AUTHOR

**KOLAPO ILERIOLUWA GREAT-GRACE**
Data Analyst / Excel. Power BI .SQL /





 
   
