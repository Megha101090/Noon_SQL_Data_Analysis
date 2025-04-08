# Noon_SQL_Food Delivery Insights
# Objective

This SQL project analyzes food delivery data to derive actionable business insights. It simulates real-world use cases that growth and marketing teams face in a food delivery business, like customer acquisition, retention, and promotions.

# Dataset
The dataset contains a single orders table with the following columns:

1️⃣	Order_id

2️⃣	Customer_code

3️⃣	Placed_at

4️⃣	Restaurant_id

5️⃣	Cuisine

6️⃣	Order_status

7️⃣Promo_code_Name
   
All data is simulated and covers various cuisines, promo usage, and customer behaviors across multiple cities.

#  Business Questions
1️⃣	Top outlets by cuisine without using LIMIT or TOP

2️⃣	Daily new customer count from the launch date

3️⃣	Count of users acquired in Jan 2025 who placed only one order in Jan and none after

4️⃣	Customers with no orders in the last 7 days, but were acquired a month ago using a promo

5️⃣	Trigger target customers after every third order

6️⃣	List customers who only ordered using promos and ordered more than once

7️⃣	% of users organically acquired in Jan 2025 (without a promo code)

# Tools used
1️⃣ SQL

2️⃣	MySQL

# Learnings

1️⃣ Use of CTEs, ROW_NUMBER(), WINDOW FUNCTIONS

2️⃣	Conditional Aggregation

3️⃣	Temporal Filtering (based on GETDATE()/curdate())

4️⃣	Real-world business thinking in SQL

5️⃣	Key Metrics for Food Delivery Business


