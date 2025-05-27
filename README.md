# ecommerce_overview
Assumptions and explanation of metric used in Looker dashboard.


Taks 1 
Created a table chart and Time series chart for revenue.
Revenue = Price * Quantity
Joined/Blended tables on the Orders and Products on Product_id columnn and performed a Left outer join. 
In the data only one month's data was present that's why its april revenue only. 

Task 2 
Users, orders and Product tables were joined on user_id and product_id column. 
Drill down button added on the right top (Region to User email).

Task 3 
New users = Users whos signed up in last 50 days from current date.
Converted Users = users who signed up in last 50 days and then placed an order.
Both table charts and scorecards are theres using a blend of users and orders table.

Task 4
Number of order for each referrer in pie chart. 
For bar chart another blend was created using order and page_views on user_id where i took mininum event_time to get first referrer.

Task 5 
Product category wise metrics are added where users, orders and products table were blended. 
user and order on user_id columnn, order and products were blended on product_id.

Additionaly tool tip or i button is added to provide more information on the charts.
Also this report is scheduled weekly for email : Noelin@ascendeum.com (every thursday) at 3PM, IST.
Lastly, month over month revenue can be generated if we have other months data as well by using below formula : revenue(current month) - revenue(previous month)*100/revenue(previous month)
