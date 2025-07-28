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
   
![WhatsApp Image 2025-07-03 at 13 20 18_82e44ef8](https://github.com/user-attachments/assets/5b4b22df-3739-42f2-9534-a436d1a997ac)
![WhatsApp Image 2025-07-03 at 13 20 18_2ac790d8](https://github.com/user-attachments/assets/27bc1a56-22be-4717-aab8-12c80e7dc04d)
![WhatsApp Image 2025-07-03 at 13 20 17_fde05475](https://github.com/user-attachments/assets/639cad71-b5b8-4a53-aeca-b41fc1f7f66b)
![WhatsApp Image 2025-07-03 at 13 20 17_db51c3c5](https://github.com/user-attachments/assets/c2427920-cc56-4cb7-9cfe-f080549fff9d)
![WhatsApp Image 2025-07-03 at 13 20 17_72d682ca](https://github.com/user-attachments/assets/961f9407-58d3-4b64-89ab-85751debc931)
![WhatsApp Image 2025-07-03 at 13 20 14_818a918c](https://github.com/user-attachments/assets/f0fd24a3-e765-4a87-842a-1b9b11a8be5c)
![WhatsApp Image 2025-07-03 at 13 20 12_f81a339d](https://github.com/user-attachments/assets/eff59b65-99ca-4465-9054-a042f711389e)
![WhatsApp Image 2025-07-03 at 13 20 01_7087df03](https://github.com/user-attachments/assets/a9a94d96-f914-43d1-ab47-11e846c31d6a)
![WhatsApp Image 2025-07-03 at 13 19 46_9ef6cb2b](https://github.com/user-attachments/assets/e8dd1fb2-62a7-4095-bf3f-107a2515b20b)
![WhatsApp Image 2025-07-03 at 13 19 44_aa1a91f1](https://github.com/user-attachments/assets/c43223cb-7a85-47d6-af05-bc051477b85b)
![WhatsApp Image 2025-07-03 at 13 19 31_8c8ac3ff](https://github.com/user-attachments/assets/715f4525-7074-44cc-b36e-35438bde75f9)
![WhatsApp Image 2025-07-03 at 13 19 29_6f87050d](https://github.com/user-attachments/assets/3390c81a-ea56-4312-8297-9735dd074aeb)
![WhatsApp Image 2025-07-03 at 13 19 46_9ef6cb2b](https://github.com/user-attachments/assets/7533ae3d-2af2-48eb-99a7-b28ca437deb9)
![WhatsApp Image 2025-07-03 at 13 19 44_aa1a91f1](https://github.com/user-attachments/assets/9619c572-2bb3-4fda-91af-073664b926eb)
![WhatsApp Image 2025-07-03 at 13 19 29_6f87050d](https://github.com/user-attachments/assets/23d9e88f-0b54-436a-8df4-66167a8d24e1)

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
  
![WhatsApp Image 2025-07-03 at 14 30 51_86d76deb](https://github.com/user-attachments/assets/d7addbdf-c022-41d5-ad4d-f08293fde82a)
![WhatsApp Image 2025-07-03 at 14 30 46_5b9d0b72](https://github.com/user-attachments/assets/4eb371c5-5383-4127-af1f-1fac98049c63)
![WhatsApp Image 2025-07-03 at 14 30 59_caf32efe](https://github.com/user-attachments/assets/334c3a99-469d-46e0-a74a-49f18dd5b3c3)
![WhatsApp Image 2025-07-03 at 14 30 58_2b205f61](https://github.com/user-attachments/assets/72a13c38-bc1b-468c-b65d-464ae297ab31)
![WhatsApp Image 2025-07-03 at 14 30 59_0d0b77c7](https://github.com/user-attachments/assets/1c368e8a-9fb7-442b-b24e-1784bf711506)
![WhatsApp Image 2025-07-03 at 14 30 59_25c9bace](https://github.com/user-attachments/assets/60d3c740-261c-4464-bc66-3f716cca0ee5)
![WhatsApp Image 2025-07-03 at 14 31 07_48dad3bc](https://github.com/user-attachments/assets/93b9b93e-6ce6-4a3c-aa44-e697052eac13)
![WhatsApp Image 2025-07-03 at 14 31 07_2a518414](https://github.com/user-attachments/assets/05ae7648-3634-4a62-9c14-eea97fe1dc14)
![WhatsApp Image 2025-07-03 at 14 31 09_ac3b2196](https://github.com/user-attachments/assets/78eed29e-5a91-47f0-92df-6ce62764d63b)
![WhatsApp Image 2025-07-03 at 14 31 08_8a821075](https://github.com/user-attachments/assets/25ffaf5d-1c6f-49d3-9710-0a6ce8f92928)
![WhatsApp Image 2025-07-03 at 14 30 59_0d0b77c7](https://github.com/user-attachments/assets/8498b367-2483-4511-b54d-4a090b62c11f)
![WhatsApp Image 2025-07-03 at 14 30 58_2b205f61](https://github.com/user-attachments/assets/9725eb1a-ddc3-4cd1-97dd-9d998d502b93)
![WhatsApp Image 2025-07-03 at 14 30 59_caf32efe](https://github.com/user-attachments/assets/996d9f5c-6d43-44d7-9e68-5078407606b3)
![WhatsApp Image 2025-07-03 at 14 30 59_25c9bace](https://github.com/user-attachments/assets/f94c0c71-1176-4246-af59-d223d20731af)
![WhatsApp Image 2025-07-03 at 14 31 07_48dad3bc](https://github.com/user-attachments/assets/866c050a-4136-4c9c-b2c5-752bcb98163c)
![WhatsApp Image 2025-07-03 at 14 31 07_2a518414](https://github.com/user-attachments/assets/0403d109-16f8-477e-b302-24ff1e950517)
![WhatsApp Image 2025-07-03 at 14 32 34_bfb4bfb0](https://github.com/user-attachments/assets/777b7fe6-668c-4dd9-8468-6375a6269ca5)
![WhatsApp Image 2025-07-03 at 14 32 34_07a8f513](https://github.com/user-attachments/assets/071c170e-de79-475a-9d4f-722152d61f00)
![WhatsApp Image 2025-07-03 at 14 32 31_be350356](https://github.com/user-attachments/assets/1eeab198-3735-4fc3-bdb7-ac3fc99b1fe8)
![WhatsApp Image 2025-07-03 at 14 32 37_3b5f0a28](https://github.com/user-attachments/assets/0ae56fc4-edac-4c7d-b9f2-ade2271ad6bd)
![WhatsApp Image 2025-07-03 at 14 32 41_e5736bcc](https://github.com/user-attachments/assets/1576e118-a498-4ed5-be57-8b5855c0ebe9)
![WhatsApp Image 2025-07-03 at 14 32 41_432c94e6](https://github.com/user-attachments/assets/ee066ae0-dd96-4f08-8073-1272a5c616b3)
![WhatsApp Image 2025-07-03 at 14 32 39_5678f026](https://github.com/user-attachments/assets/cd45e46a-7a83-4a61-b7cf-a9b76e2f8c65)
![WhatsApp Image 2025-07-03 at 14 32 38_bfb53ab8](https://github.com/user-attachments/assets/6809ec64-67fc-4696-8122-828a2c046d24)
<img width="828" height="528" alt="Palmoria group dashboard 2" src="https://github.com/user-attachments/assets/ab3a7589-723d-4d37-b350-584727402e16" />
<img width="955" height="533" alt="Palmoria group dashboard 1" src="https://github.com/user-attachments/assets/2d43dbe3-a137-4269-aa27-366bf0444857" />


- **Dataset Size after Analysis**: 946 Rows

#### AUTHOR

**KOLAPO ILERIOLUWA GREAT-GRACE**
Data Analyst / Excel. Power BI .SQL /





 
   
