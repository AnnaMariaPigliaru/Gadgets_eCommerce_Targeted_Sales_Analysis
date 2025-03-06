# Gadgets eCommerce Targeted Sales Analysis
*Sales Trends and Patterns discovery of an undisclosed Gadgets eCommerce with Excel and Power BI*

## 1. Project Background

The dataset used for the following project is obtained from Kaggle and it comprises transactions carried out in 2023 from January till December of an  undisclosed eCommerce in the gadgets industry.
The Company’s Sales Department requests the Data Analysis Team to assist in answering to the following Business Questions/Problems:
- Which are the Top 2 Regions that generate the highest revenue?
- Once these have been identified, what are the sales trends which characterize each of the regions?
- Does discount have an impact on customer purchase decision?
- Develop a dashboard to monitor North Star KPIs and growth rates

The following types of analytics were used to discover and  carefully synthesize transactions patterns and trends:
- Exploratory Data Analysis (EDA)
- Descriptive Analytics

### 1.1 Data Structure
The dataset’s structure as seen below consists of an already clean single table of 10,000 rows which was transformed for the purposed of this study.

<img src="https://github.com/user-attachments/assets/e3507f00-bd34-45f2-91f8-ffc046c132d32" alt="Alt Text" style="width:60%; height:auto;">

The following attributes were  created and added  to the table:
- Revenue – Total Sales Revenue generated per transaction
Further transformations can be viewed in Power Query Editor [Here](e_commerce_sales_work.xlsx)

## 2. Executive Summary
The Top 2 revenue producing regions are Africa and North America with both generating approximately  $4.7 million in year 2023.

There is a  strong presence of seasonality in sales: in Africa higher purchases over the Christmas period (December & January) and in March. North American consumers also purchase substantially in March but do so the most in July with a total of 200 transactions.  In both regions the monthly growth rate decreases by approximately 15% in February. Clients in Africa favor acquiring on Sundays and Tuesday.

Age is a major component in the consumer decision making process for Africa and North America: Males of 18-30 years and Females over 60 in Africa generate the highest average revenue with $2,473 and $2,583 respectively, while in North America Females aged 30-40 and Males 40-50 take the lead with $2,451 and $2,386. Females aged 50-60 in Africa and Males over 60 in North America are the lowest generating average revenue clients with $2.1K and $2.2K respectively.

The African region observes discounts more than North America accompanied by the Gender variable. Males in Africa initiate 61% of the transactions with no discount and favor discount ranges 10%-15% and 25%-30%. North American Females on the other hand, are the gender which purchase the most with no discount with 59% of the total transactions in the discount range. The most popular discount in the region is 10%-15%.

Tables and Headphones are sold more in North America in terms of quantity and Africa deals more Smartwatches and Smartphones. In both regions, however, Smartphones and Headphones carry the greatest average revenue. The purchase of Laptops and Smartphones in Africa strongly depend on the discount value, while this applies for Smartphones and Tables in North America.
