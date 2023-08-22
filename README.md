### TarGet-SQL

This particular business case focuses on the operations of TarGet in Brazil and provides insightful information about 100,000 orders placed between 2016 and 2018. The dataset offers a comprehensive view of various dimensions including the order status, price, payment and freight performance, customer location, product attributes, and customer reviews.

By analyzing this extensive dataset, it becomes possible to gain valuable insights into TarGet's operations in Brazil. The information can shed light on various aspects of the business, such as order processing, pricing strategies, payment and shipping efficiency, customer demographics, product characteristics, and customer satisfaction levels.

the task of analyzing the given dataset to extract valuable insights and provide actionable recommendations.

**structure & characteristics of the dataset:**
  1. Data type of all columns in the "customers" table.
  2. Getting the time range between which the orders were placed.
  3. Count the Cities & States of customers who ordered during the given period.

**Exploration:**
  1. Finding is there a growing trend in the no. of orders placed over the past years?
  2. Can we see some kind of monthly seasonality in terms of the no. of orders being placed?
  3.During what time of the day, do the Brazilian customers mostly place their orders? (Dawn, Morning, Afternoon or Night)
   * 0-6 hrs : Dawn
   * 7-12 hrs : Mornings
   * 13-18 hrs : Afternoon
   * 19-23 hrs : Night

** E-commerce orders in the Brazil region:**
  1. Getting the % increase in the cost of orders from year 2017 to 2018 (include months between Jan to Aug only).
  2. You can use the "payment_value" column in the payments table to Getting the cost of orders.
  3. Calculate the Total & Average value of order price for each state.
  4. Calculate the Total & Average value of order freight for each state.

**Analysis based on sales, freight and delivery time:**
  1. no. of days taken to deliver each order from the order’s purchase date as delivery time.
  2. Also, calculate the difference (in days) between the estimated & actual delivery date of an order.
     Do this in a single query.
  3. calculate the delivery time and the difference between the estimated & actual delivery date using the given formula:
       * time_to_deliver = order_delivered_customer_date - order_purchase_timestamp
       * diff_estimated_delivery = order_estimated_delivery_date - order_delivered_customer_date
  4. Finding out the top 5 states with the highest & lowest average freight value.
  5. Finding out the top 5 states with the highest & lowest average delivery time.
  6. Finding out the top 5 states where the order delivery is really fast as compared to the estimated date of delivery.
  7. Using the difference between the averages of actual & estimated delivery date to figure out how fast the delivery was for each state.

**Analysis based on the payments:**
  1. Finding the month on month no. of orders placed using different payment types.
  2. Finding the no. of orders placed on the basis of the payment installments that have been paid.
     
