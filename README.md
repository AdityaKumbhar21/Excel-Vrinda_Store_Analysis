# Excel-Vrinda_Store_Analysis
This is an end-to-end analysis of the vrinda store for the year 2021 to 2022.

Excel Project: Analyzing Data of a store.

The dataset is of a superstore named “Vrinda” Store the requirement is that you need to analyze the data of the store from 06–01–2022 to 04–12–2022.

Business Problem: The Vrinda Store want to create an Annual Report of the sales from 06–01–2022 to 04–12–2022.So that they can understand their existing customers and help them grow their business in the year 2023.

Business Questions:

1.What is the sales month wise in the entire year?

2.Which is more willing to shop products(Men or Women)?

3.What is the percentage of the order status (Delivered, Returned, Refunded)?

4.Which are the top 5 states from which the store is having sales?

5.What age is more willing to buy the product and relation between age and Gender?

6.What are the top channels from which the sales is coming?

7.Which business type is more (B2B or B2C)?

Step 1:
Data Cleaning:
As a good data analyst the most necessary step is data cleaning. As we get the data from the client it is not always necessary that the data will be consistent and in a proper manner.

Cleaned Data:
In the gender section there was a inconsistent data like Men, M, Women, W.
First we will make this data consistent by replacing M by Men and W by Women.
And same in the Qty column the quantity was like One, 1, Two, 2. So Here replacing One with numeric 1 and Two with numeric 2.

Step 2:
Data Processing:
As the requirement states the client wants sales data month wise so we will be extracting the month from the date by adding a column named month
The fromula for extracting the data is the : =TEXT(cell_addr, ”mmmm”)
In the age column there are multiple age in the column so it will be a chaos while handling and analyzing data so we can create a age group as: 18–25 = teenager, 25–50 = Adult, >50 = Senior
The formula for it will be : =IF(E2>=50,”Senior”,IF(E2>=25,”Adult”,”Teenager”))

Step 3:

Creating pivot Tables and Charts

Pivot Tables:

1. Amount Vs Order

2. Sales comparison between: Men And Women

3. Top 5 states

4. Order Status

5. Top Channel

6. Relation between Age and Gender

Step 4:

Creating Dashboard

To make dashboard interactive you can insert slicer here I have inserted Slicers as Month, Product Category and Business type.


Insights:

1.The company has done the highest sale in the Month of March with amount of 1.92 Million and total number of orders as 2918.

2.Women are more likely to buy products form the shop.

3.The top 5 states are:

a. Maharastra- 2.99 Million Rupee Sales

b. Karnataka- 2.65 Million Rupee Sales

c. Uttar Pradesh- 2.10 Million Rupee Sales

d. Telangana- 1.71 Million Rupee Sales

e. Tamil Nadu- 1.68 Million Rupee Sales

5. The top channel is Amazon from which the sales is coming

6. And most of the business is from B2B.

Conclusion:

The Vrinda Store should target the audience of the age group of 25–50 and especially Women by showing them ads through Amazon. And also by giving them coupons of Amazon
