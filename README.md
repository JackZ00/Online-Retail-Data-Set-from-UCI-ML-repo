# [Online-Retail-Data-Set-from-UCI-ML-repo](https://archive.ics.uci.edu/ml/datasets/online+retail#)

## Data Set Information:
This is a transnational data set which contains all the transactions occurring between 01/12/2010 and 09/12/2011 for a UK-based and registered non-store online retail.The company mainly sells unique all-occasion gifts. Many customers of the company are wholesalers.

## Content
* Data Set Characteristics: Multivariate, Sequential, Time-Series

* Number of Instances: 541909

* Area: Business

* Attribute Characteristics: Integer, Real

* Number of Attributes: 8

* Date Donated: 2015-11-06

* Associated Tasks: Classification, Clustering

* Missing Values? N/A

* Number of Web Hits: 159409

## Tool
Python

## Goal
1. Order dimension: What is the average order value and the average basket size? What is the relationship between order value and the number of items in each order?
2. Customer dimension: What is the average customer spend? What is the relationship between customer spend and the number of items purchased?
3. Product dimension: What is the price range of the products sold? Which price range sells the most products? Which price range generates the most revenue?
4. Time dimension: What is the trend in sales by month/day? What factors might be affecting sales?
5. Region dimension: Which countries do customers primarily come from? Which country is the main overseas market? Which country has the highest average customer spend?
6. Customer behavior: What is the customer lifecycle and retention rate?

## Result
Order Dimension:
There were a total of 19,960 valid orders with an average order value of 533.17 GBP and an associated items per order of around 279. Wholesale orders dominated, with significant variation in purchasing power among customers. Overall, the transaction amount and the number of items purchased were positively correlated.

Customer Dimension:
The average customer spend was 2,049 GBP, with significant differences in purchasing power among customers. The customer base was healthy, with the amount spent on purchases positively correlated with the number of items bought, and exhibited stronger patterns than the order dimension.

Product Dimension:
The unit price of products exhibited fluctuations, primarily focused on products with low prices, with most items priced between 1-2 GBP. Products priced below 5 GBP were the most popular among customers and accounted for the majority of sales revenue. Although high-priced products had high unit prices, they had low sales volumes and did not contribute significantly to sales revenue. It is recommended that the procurement department consider selecting more products priced under 10 GBP to further expand the low-priced category range.

Time Dimension:
The number of orders, sales volumes, and revenue followed similar trends and peaked in September to November 2011. As the main products were gifts, this peak period may have been influenced by holidays such as Halloween (November 1st) and Christmas (December 25th), or by "Black Friday" (the fourth Thursday in November). The sales revenue was mainly influenced by the changes in sales volume due to the low unit price and price concentration.

Geographic Dimension:
The vast majority of customers were from the UK, and most of the foreign income was also from neighboring countries. This pattern roughly followed a radius emanating from the UK, which may have been influenced by shipping costs, language, and the attenuation of influence with distance. It is recommended to increase overseas publicity and improve website adaptation for multiple languages.

Lifecycle:
The average lifecycle was 130 days, and the distribution of lifecycles was polarized. The average lifecycle of customers who made two or more purchases was 203 days, significantly higher than the overall average of 103 days. It is recommended to pay more attention to the customer experience of the first purchase and improve it through methods such as service evaluations and customer service inquiries. More effort should also be made to encourage customers to make repeat purchases, such as offering time-limited coupons.

Retention:
Customer purchases were not high-frequency behavior, but retained loyal customers were highly loyal. Customers who only made their first purchase accounted for 37.5% of the total customer base. Improving the retention rate of this group would lead to significant revenue growth.

Purchase Cycle:
Most retained customers had purchase cycles between 15-70 days. It is recommended to send out information about promotional activities every 30 days to encourage customers to make repeat purchases.


## Source
Dr Daqing Chen, Director: Public Analytics group. chend '@' lsbu.ac.uk, School of Engineering, London South Bank University, London SE1 0AA, UK.

## Attribute Information:
InvoiceNo: Invoice number. Nominal, a 6-digit integral number uniquely assigned to each transaction. If this code starts with letter 'c', it indicates a cancellation.
StockCode: Product (item) code. Nominal, a 5-digit integral number uniquely assigned to each distinct product.
Description: Product (item) name. Nominal.
Quantity: The quantities of each product (item) per transaction. Numeric.
InvoiceDate: Invice Date and time. Numeric, the day and time when each transaction was generated.
UnitPrice: Unit price. Numeric, Product price per unit in sterling.
CustomerID: Customer number. Nominal, a 5-digit integral number uniquely assigned to each customer.
Country: Country name. Nominal, the name of the country where each customer resides.

## Relevant Papers:
The evolution of direct, data and digital marketing, Richard Webber, Journal of Direct, Data and Digital Marketing Practice (2013) 14, 291â€“309.
Clustering Experiments on Big Transaction Data for Market Segmentation,
Ashishkumar Singh, Grace Rumantir, Annie South, Blair Bethwaite, Proceedings of the 2014 International Conference on Big Data Science and Computing.
A decision-making framework for precision marketing, Zhen You, Yain-Whar Si, Defu Zhang, XiangXiang Zeng, Stephen C.H. Leung c, Tao Li, Expert Systems with Applications, 42 (2015) 3357â€“3367.

## Citation Request:
Daqing Chen, Sai Liang Sain, and Kun Guo, Data mining for the online retail industry: A case study of RFM model-based customer segmentation using data mining, Journal of Database Marketing and Customer Strategy Management, Vol. 19, No. 3, pp. 197â€“208, 2012 (Published online before print: 27 August 2012. doi: 10.1057/dbm.2012.17).
