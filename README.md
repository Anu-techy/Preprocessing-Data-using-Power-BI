# Financial-Analysis-using-Power-BI

Define the Problem
Data Collection
Data Cleaning
Data Exploration
Data Analysis
Data Visualization
Model Building (if applicable)
Interpret Results
Communicate Findings
Monitor & Maintain (if needed)

**Aim**
To create a Dim_date table

To build a dashboard in Power BI for Comprehensive Financial Analysis

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

=======================================================================================================

There are total 10 tables

**Data Collection**

Data Catalog is given, where the details of DB servers, tables with description and on call person contact is given.

There are total 10 tables

**Dimension tables**

dim_customer (channel, customer, customer_code, market, platform)     209 rows * 5 columns

dim_market (market, sub_zone, region)          27 rows * 3 columns

dim_product (product_code, division, segment, category, product, variant)    397 rows * 6 columns    

**fact tables**

fact_forecast_monthly (date, division, category, product_code, product, market, platform, channel, customer_code, customer_name, forecast_quantity)    1885941 rows * 11 columns

fact_sales_monthly (date, division, category, product_code, product, market, platform, channel, customer_code, customer_name, sold_quantity)  1425706  rows * 11 columns

freight_cost (market, fiscal_year, freight_pct, other_cost_pct) 135 rows * 4 columns

gross_price (product_code, fiscal_year, gross_price) 1197 rows * 3 columns

manufacturing_cost (product_code, cost_year, manufacturing_cost)  1197 rows * 3 columns

post_invoice_deductions (customer_code, product_code, date, discounts_pct, other_deductions_pct)  2063076 rows  * 5 columns

pre_invoice_deductions (customer_code, fiscal_year, pre_invoice_discount_pct)    1045 rows * 3 columns    

===================================================================================================================













