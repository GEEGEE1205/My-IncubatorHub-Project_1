# DSA INCUBATOR HUB PROJECT
### TOPIC: AMAZON PRODUCT REVIEW ANALYSIS

This project is to present an indepth analysis of Amazon products,using Microsoft Excel to uncover insights related to pricing,reviews,ratings and potential revenue. The Dashboard provides key performance indicators (KPIs) and charts to guide business Decisions.

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

 I checked out cells with abnormal values and changed the numerical column blank cells to (0). I changed datatypes to the appropriate datatypes. Also I inserted some new calculated columns that are needed for my analysis. Afterwards I deleted unnecessary columns from the dataset.

  Then I proceeded to creating my pivot tables with the refined datasets. With the Pivot tables I created Dashboard consisting KPIs and Charts to summarize my Analysis.
    
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

- **Key Insights**:
 
- **Product Overview**
    - Products span multiple sub-categories under broader categories like Computers & Accessories, Mobiles, etc.
    - Majority of products fall into mid-range price buckets (₹200–₹500).

 -  **Discount Analysis**:
      - Average Discount % varies by category; some exceed 80%.
      - Over 60% of products have a ≥50% discount, indicating aggressive pricing.
      - Top categories with heavy discounts include accessories and cables.

-  **Customer Engagement**:
     - Rating values cluster heavily around 4.0 and 5.0, showing high satisfaction.
     - Some products have 0 reviews, suggesting either new entries or low visibility.
     - The product with the most reviews: B07KSMBL2H
     - The product with the highest average rating: B09ZHCJDP1

-  **Revenue Potential**:
     - Total Potential Revenue = Actual Price × Rating Count calculated for each product.
     - High-value categories: Electronics, Phone Accessories.
     - Several products with low prices and high review counts show significant potential.

-  **Top Performers**:
     - Top 5 products calculated using:= Average Rating + (Rating Count ÷ 1000)

-  **Dashboard Features**: 
     - Pivot Charts: Used to visualize discount vs rating, revenue by category, etc.
     - KPIs
       
- **Recommendations**:
    - Focus marketing on high-rating but low-review products to build momentum.
    - Invest in categories with high revenue potential but low visibility.
    - Consider bundling low-priced accessories with flagship products.

 -  **Pictorial information of the analysis process** :
   
<img width="1110" height="768" alt="Amazon product worksheet 3" src="https://github.com/user-attachments/assets/8c25204f-ffb7-46cd-9cd4-c9ba724f89f9" />
<img width="1279" height="761" alt="Amazon Product worksheet 2" src="https://github.com/user-attachments/assets/10133a92-f787-4410-a980-0d23eb20cc8f" />
<img width="1366" height="768" alt="Amazon product worksheet 1" src="https://github.com/user-attachments/assets/57ea1109-50d9-4c28-8ed4-12319e0706ea" />
<img width="590" height="671" alt="Amazon product pivot table 4" src="https://github.com/user-attachments/assets/f8d4d98c-2244-4645-80f9-4af15358c53a" />
<img width="1043" height="748" alt="Amazon product Pivot table 3" src="https://github.com/user-attachments/assets/808cf58d-8efb-4b66-8a9c-427712b82692" />
<img width="458" height="748" alt="Amazon product pivot table 2" src="https://github.com/user-attachments/assets/a59c97d1-5ceb-4ce9-a21a-2f394142bea9" />
<img width="1156" height="768" alt="Amazon product pivot table 1" src="https://github.com/user-attachments/assets/bc4bbc65-eaa1-41a9-a28d-fc45f44d875c" />
<img width="1259" height="445" alt="Amazon Product Dashboard" src="https://github.com/user-attachments/assets/023ddf4a-f2ee-459f-ac27-24a415847757" />
<img width="1126" height="748" alt="Amazon product worksheet 4" src="https://github.com/user-attachments/assets/3e7babbc-97da-40b4-86cf-434e4671b4e0" />


---

- **Dataset Size after Analysis**:1351 products

#### AUTHOR

**KOLAPO ILERIOLUWA GREAT-GRACE**
 Data Analyst / Excel. Power BI . SQL/










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
  
  - Power BI (for transformation,visualization, DAX)
  - Excel (for data cleaning and bonus rule setup)
  - Power Query Editor (data profiling and Merging)
     
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

 Afterwards I cleaned datasets,checked the Data quality,Data Distribution,column profile,Renamed column to suit my Requirements,Created custom columns and conditional columns to generate necessary required columns for the analysis.
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

-  **Key Insights**:
  
     - Gender Imbalance persists in several departments and locations
     - Evidence of a gender pay gap, especially in higher-paid roles
     - Ratings appear biased in some cases, affecting bonus allocations
     - Several employees earn below the minimum threshold
     - The bonus system needs refinement for fair and transparent distribution

-  **Recommendations**:

     - Promote Gender Equality Across Departments and Regions. Set measurable gender diversity targets in recruitment and internal promotions to ensure equal representation.

     - Address the Gender Pay Gap. Conduct a comprehensive salary audit and implement a standardized pay structure that eliminates disparity for roles with similar job grades and responsibilities.

     - Review Rating & Bonus Allocation Processes. Train supervisors on fair performance appraisal practices and introduce multi-rater (360°) evaluations to reduce bias. Also Automate bonus calculations using transparent rules integrated into HR systems.

     - Ensure Compliance with Minimum Wage Policies. Enforce a minimum salary policy across all regions and departments, and adjust non-compliant salaries accordingly.

     - Maintain Accurate and Updated Employee Records. Regularly audit and update HR databases to remove exited employees and obsolete departments.

     - Leverage Data for HR Decision-Making. Implement routine dashboard reporting for key HR metrics like gender parity, salary distribution, and employee performance.

-  **Pictorial information of the analysis process** :
  



- **Dataset Size after Analysis**: 946 Rows

#### AUTHOR

**KOLAPO ILERIOLUWA GREAT-GRACE**
Data Analyst / Excel. Power BI .SQL /





 
   
