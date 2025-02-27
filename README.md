# Financial-Analysis-using-Power-BI

**Aim**

To preprocess and transform the data for creating interactive dashboards that cater 
to the Finance, Sales, Marketing, and Supply Chain teams, enabling 
deeper analysis, insights generation, and informed decision-making.

**Description**

**Atliq** is a hardware company which manufactures electronic hardware items like PC, Laptop, Hard Drive, mouse, Keyboards, pendrives etc. 
It has operations all over the globe. 

It sells to consumers through the following distribution **channels**:

              1. Direct Channel (Atliq E-stroe, Atliq Exclusive)
              2. Retailer (Croma, amazon)
              3. Distributer (Eg- Neptune in China)
              
It has two **platforms**:

              1. Brick and Mortar (like Croma, BestBuy)
              2. E-commerce (like Amazon, Flipkart)
              
Here Amazon, Croma, AtliQ Exclusive etc are the customers

markets are country names. Country names come under 4 regions. APAC, EU, NA, LATAM.

The product hierarchy is a structured classification from broad to specific: Division → Segment → Category → Product Name → Variant.

product divisions are Peripheral and Accessories (P & A), PC, N & S (Networking and storage) 

========================================================

**Data Cleaning**

Data Cleaning and transformation in Power Query

Removed duplicate values

Removed data with missing values (only 3 rows)

Identified, replaced spelling mistakes in customer names

Replaced nan category in market table to NA (North American Region) ater confirming with business owners

Few rows have negative quantity , Replaced with positive after clear confirmation

Named all the data transformation steps

===================================================================

**Steps**

1. Data Collection
2. Data cleaning
3. To create a Dim_date table (date, month, fiscal_year columns for all the transactions in fact_sales_monthly)
4. Data Modelling
5. Data validation against Bench mark numbers to make sure that the data is loaded correctly for further transformations.
6. Building fact_actual_estimates table
7. Data Modelling
8. Calculated columns for P & L Metrics using Power Query
9. Calculated columns for P & L Metrics using DAX
10. Optimization of the file size

====================================================================================
Creating **Mockup of the Dashboard** we needed help us in 

•	Visual communication of what we need

•	Early feedback

•	Enchanced user experience

**Note** mockup.ai is one of the tool

======================================================







