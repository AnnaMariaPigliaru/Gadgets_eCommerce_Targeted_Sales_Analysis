# Gadgets eCommerce Targeted Sales Analysis
*Sales Trends and Patterns discovery of an undisclosed Gadgets eCommerce with Excel and Power BI*

## Table of Contents
- [1. Project Background](#project-background)

  - [*1.1 Data Structure*](#data-structure)

- [2. Executive Summary](#executive-summary)

- [3. Analysis](#analysis)

  - [*3.1 Time Series Orientated*](#time-series-orientated)
    
  - [*3.2 Age Range Orientated*](#age-range-orientated)
    
  - [*3.3 Discount Range Orientated*](#discount-range-orientated)
    
  - [*3.4 Product Orientated*](#product-orientated)

- [4. Recommendations](#recommendations)

- [5. Assumptions](#assumptions)


## Project Background

The dataset used for the following project is obtained from Kaggle and it comprises transactions carried out in 2023 from January till December of an  undisclosed eCommerce in the gadgets industry.
The Company’s Sales Department requests the Data Analysis Team to assist in answering to the following Business Questions/Problems:
- Which are the Top 2 Regions that generate the highest revenue?
- Once these have been identified, what are the sales trends which characterize each of the regions?
- Does discount have an impact on customer purchase decision?
- Develop a dashboard to monitor North Star KPIs and growth rates

The following types of analytics were used to discover and  carefully synthesize transactions patterns and trends:
- Exploratory Data Analysis (EDA)
- Descriptive Analytics

### Data Structure
The dataset’s structure as seen below consists of an already clean single table of 10,000 rows which was transformed for the purposed of this study.

<img src="https://github.com/user-attachments/assets/e3507f00-bd34-45f2-91f8-ffc046c132d32" alt="Alt Text" style="width:60%; height:auto;">

The following attributes were  created and added  to the table:
- Revenue – Total Sales Revenue generated per transaction

Further transformations can be viewed in Power Query Editor [Here](e_commerce_sales_work.xlsx)
The requested dashboard can be viewed


## Executive Summary

The Top 2 revenue producing regions are Africa and North America with both generating approximately  $4.7 million in year 2023.

There is a  strong presence of seasonality in sales: in Africa higher purchases over the Christmas period (December & January) and in March. North American consumers also purchase substantially in March but do so the most in July with a total of 200 transactions.  In both regions the monthly growth rate decreases by approximately 15% in February. Clients in Africa favor acquiring on Sundays and Tuesday.

Age is a major component in the consumer decision making process for Africa and North America: Males of 18-30 years and Females over 60 in Africa generate the highest average revenue with $2,473 and $2,583 respectively, while in North America Females aged 30-40 and Males 40-50 take the lead with $2,451 and $2,386. Females aged 50-60 in Africa and Males over 60 in North America are the lowest generating average revenue clients with $2.1K and $2.2K respectively.

The African region observes discounts more than North America accompanied by the Gender variable. Males in Africa initiate 61% of the transactions with no discount and favor discount ranges 10%-15% and 25%-30%. North American Females on the other hand, are the gender which purchase the most with no discount with 59% of the total transactions in the discount range. The most popular discount in the region is 10%-15%.

Tables and Headphones are sold more in North America in terms of quantity and Africa deals more Smartwatches and Smartphones. In both regions, however, Smartphones and Headphones carry the greatest average revenue. The purchase of Laptops and Smartphones in Africa strongly depend on the discount value, while this applies for Smartphones and Tables in North America.

## Analysis

North America and Africa have been identified as the top 2 revenue generating regions with Africa leading Globally with $4,739,841.32 and North America following with $4,727,213.53.

<img src="https://github.com/user-attachments/assets/ffb8fd8b-4e2c-40eb-b7bf-7026abf12af7" style="width:50%; height:auto;">

There is a relatively even distribution in transaction count based on membership and gender, as in both cases the ratio is approximately 1:1. Additionally, in both regions 80% of purchases fall under electronics and only 2% of transactions did not reflect a discount application (ref. [Here](e_commerce_sales_work.xlsx) for further details).

### Time Series Orientated
Africa leads in  quarters 1 and 4 in terms of transactions count, whereas  Nort America has the highest in quarter 3 with 551 counts.

<img src="https://github.com/user-attachments/assets/09736d54-ce9b-48ba-9e99-b2f99c935470" style="width:50%; height:auto;">

More specifically, Africa has the peak number of sales in the months of March and December with 192 and 190 orders respectively, while July and December are the best performing months in North America with 200 and 188 transactions.

<img src="https://github.com/user-attachments/assets/5256c7fa-ba57-44b1-ace0-f4ee0466a16b" style="width:50%; height:auto;">

For both regions the least performing month is February with a drop in transactions count compared to the previous month of 13.4% in Africa and 16.7% in North America.

<img src="https://github.com/user-attachments/assets/3cafde2f-145d-48d6-9e54-7572d8e4f5a1" style="width:50%; height:auto;">

However, it can be noticed that there is a considerable spike in purchases (compared to June) of 21% in July in North America.

<img src="https://github.com/user-attachments/assets/0a96e718-e59f-498f-a705-2d18f4f2d179" style="width:50%; height:auto;">

Customers in Africa tend to purchase more on Sunday with 15.5% of its population, followed by Tuesdays. The largest share of clients in North America also purchase on Sundays but favor Mondays as well with 14.9%. Mondays, on the other hand, is the day least chosen by customers in Africa.

<img src="https://github.com/user-attachments/assets/1af39e66-8cdc-4763-82ed-5004705f890b" style="width:50%; height:auto;">

It is observed that, though a weak one, there is a correction between the days of the week and the number of transactions in the African Region. In North America the days of the Week does not have an impact on the transaction frequency.

### Age Range Orientated
Africa shows a perfect negative correlation between Age and Transaction count, while North America showcases a very strong correlation. In other words, for both Regions, the younger customers generate overall higher revenues, particularly those in the age range18-30.

<img src="https://github.com/user-attachments/assets/1250d98b-712a-4469-8670-c5736caceb8e" style="width:30%; height:auto;">

At a closer look, it is noticed that in North America the age range with the greatest Average Revenue is 30-40 with $2,402, followed by $2,345 belonging to range 40-50. The African Region on the other hand, holds its highest average revenue in the >60 age range with $2,479 and range 18-30 with $2,407.

<img src="https://github.com/user-attachments/assets/d4484f83-31e9-41b8-9215-807f9420af61" style="width:50%; height:auto;">

More specifically, Female above 60 and Males between 18 and 30 generate the greatest average revenue in Africa, while Females of age 50-60 generate the lowest average revenue of the region. In North America, on the other hand, Females of age 30-40 and Males in 40-50 are the top average revenue producers.

<img src="https://github.com/user-attachments/assets/534264be-f2aa-4a1f-bf0a-57eac81e24cf" style="width:50%; height:auto;">

<img src="https://github.com/user-attachments/assets/1f57ec09-abe0-474c-b24e-f84fa63668fa" style="width:50%; height:auto;">

### Discount Range Orientated
There is moderate positive relationship for both regions between the discount range and the total sales revenue. As illustrated in the graph below, the higher the discount the greater the revenue, though Africa appears to be affected by this pattern slightly more than North Africa  (ref. [Here](e_commerce_sales_work.xlsx) for further details).

<img src="https://github.com/user-attachments/assets/8e747617-a0ab-4fac-bbbb-8d871a2b7889" style="width:50%; height:auto;">

Customers in Africa tend to opt more for discounts ranging 5%-10% and 20%-30%.

<img src="https://github.com/user-attachments/assets/f9282cb0-9abd-4ccf-9655-ea55f454323c" style="width:30%; height:auto;">

In addition, it is noticed that 61% of the total transactions which have no discount are of Male clients. Females on the other hand, lead in the discount range 15%-20%.
                 
<img src="https://github.com/user-attachments/assets/80e5f28d-1951-4fa4-ae86-b2e72fc0d758" style="width:50%; height:auto;">

The discount range with the maximum count in North America is 10%-15% with 374 transactions, of which 57% initiated by Males. Also, 59% of the transactions with no discount are carried out by Females.

<img src="https://github.com/user-attachments/assets/8903a077-3e19-40d5-a301-c00841360cd1" style="width:50%; height:auto;">

Proceeding with the analysis, it is important to highlight that the sudden spike in North America in the month of July was most likely caused by 15%-20% and 20%-25% discounts applied  on the products.

### Product Orientated
A total of 1,274 Tablets and 1,231 Headphones are sold in North America; in  Africa Smartwatches and Smartphones are the highest selling in terms of quantity. 

<img src="https://github.com/user-attachments/assets/b838e722-7fad-4970-b6e4-21822d3a6809" style="width:50%; height:auto;">

Yet, for both regions the products with the highest average revenue are Headphones and  Smartphones.

<img src="https://github.com/user-attachments/assets/54c8e3b0-f1df-438e-ab45-4cf56c1b070a" style="width:30%; height:auto;">

Furthermore, following a correlation analysis, it is revealed that, in Africa, the possibility of laptops and smartphones being purchased (more than other products) very strongly depend on the value of the discount. Similarly in North America (tough with an inferior influence compared to Africa), customers closely observe discount values when it come to Smartphones and Tablets.

## Recommendations
Based on the uncovered insights, the following recommendations have been provided.

A Marketing strategy should be developed to entices  customer engagement and, consequently, customer purchase in the lowest transactions generating months: February, November and April for Africa, February, October and April for North America.

Expand target market by incorporating more clients over 50 as the analysis observes a considerable spending power in the older consumer, especially in Africa. Furthermore, additional products should be included to the selection to the likes of Females aged 30-40 and Males aged 40-50 in North America.

Considering that Males in Africa purchase more at full price, more products preferred by Males should be included and placed at no discount in order to increase sales profitability. The same should be applied in North America for Female consumers.

Further capitalize on Smartwatches  in both regions, Tablets in North America and Laptops in Africa.

Focus target and personalized adds with the aim to increase the number of Premium clients transactions.

## Assumptions
The Price records are not stated to be either before or after discount: for the purposed of this analysis, it is assumed that the values are to be considered as after discount.






