# Customer Segmentation & Sales Performance Analysis
   E-commerce, within a in very short time span has became one of the most powerful channel to support businesses development and has revolutionized the way businesses operate. Through e-commerce, businesses can get access and establish a wider market presence by providing cheaper and more efficient distribution channels for their products or services.
In this project we analyzes the e-commerce sales data of an UK based online retail stores to uncover critical insights that will improve the store's performance in this platform.

The company has ample amounts of data on its sales, product offerings and customer details for a period of dec-2010 to dec-2011, which can be utilized to identify the customer segments and sales performance.

Insights and recommendations are provided on the following key areas:
- **Sales Trends Analysis**: Evaluation of historical sales pattern by month, region and different customer segments.
- **Product Level Performance**: An analysis of top selling products, understanding their impact on sales.
- **Customer Segmentation**: An assesment on the customers based on RFM scores. 
- **Regional Comparison**: An evaluation of sales and orders by region.

An interactive PowerBI dashboard can be found here.

The python-pandas script used to inspect, clean, and perform EDA can be found here.

# Data Structure 
The retail stores e-commerce data consists of 8 columns: InvoiceNo, StockCode, Description, Quantity, InvoiceDate, UnitPrice, CustomerID and Country with a total row count of 541909 entries.



# Executive Summary

## Overview of findings

The analysis shows that the store was able to acheive a sales of 10 million with more that 4K unique customers within a period of 13 months. This shows that the utilization of online platform is a great success for the retail store.



**Sales Trends**

- Despite a small decline in the first half of 2011, the stores's sales gradually rises in the second half, peaking at november 2011 with 751K orders making a monthly revenue of 1.5M$ which is followed by a sudden drop in december 2011. This corresponds with the upcoming holiday season at the year end.
- The monthly sales trend is hugely depended on the customer count and the number of orders placed at the month.
- Almost 80% of the sales contribution was from UK, where as other countiries contributing less that 3%.
- It is found that there is no particular pattern in Average Order Value across months.

**Product Performance** 

- Out of products, almost 47% of the company revenue are from just three products: Dotcom Postage, Regency Cake Stand 3 tier and Paper Craft Little Birdie, with the later being the most sold in quantities(81K).
- The Dotcom Postage with an order quantity of 1K was able to generate almost 18% of the total revenue.

**RFM Analysis**

- The customers were grouped into 5 different segments based on their RFM Scores. The RFM scores are calulated based on Recency, Frequency and Monetary from their purchases.
- It is found that all 5 groups have contributed almost equally to the store's revenue.
- The group which contributed the highest (almost 23%) to the sales and largest group with most members is found to be at risk.
- Those who comes under 'at risk' and 'cannot lose' can be attributed due to their lack of frequency in their purchase.
  
   ## Recommendations

  Based on the uncovered insights, the following recommendations have been provided:

  - With 83% of the orders and 90% of the revenue coming from UK alone, and others being contributing less than 3% necessitates the need of expanding marketing strategies to other countires.
  - Eventhough the Dotcom Postage generates 18% of the revenue, it falls to 10th postion in terms of order quantity. Enhancing marketing efforts to gain more buyers to this particular product could boost sales significantly.
  - For eg:, other least selling products can be given with great discounts if purchased with the top selling products.
  - The number of 'Champians' customers being less than those 'At Risk' is alarming and more efforts should be done in raising the number of champians. Introducing targeted and personilized ads with offers and discounts can reduce the potential customer churn.
  - To convert customers into 'Champians', can consider offering one time sign-up discount paired with increased general marketing of membership benefits and savings.
  - Inorder to reduce the great fall of sales during December, implement flash sales and bundle offers with the least selling products.
