# FOOD-SALES-REPORT
The restaurant is a high-volume digital food business generating over $1M in revenue, offering multiple payment options and frequent discount promotions. It maintains strong delivery performance but faces profitability challenges due to refunds and heavy discount usage.

# Dataset used
<a href="https://github.com/Imayorrr/FOOD-SALES-REPORT/blob/main/food_orders_new_delhi%20(1).xls">Dataset used</a>

## Objectives
1.	To know the refund rate by payment method
2.	To know the delivery time quality status
3.	To know the most used discount offers
4.	To know total revenue by day
5.	To know the total revenue by payment method
6.	To know the payment method distribution

<img width="545" height="352" alt="food service SS" src="https://github.com/user-attachments/assets/a0e8b659-0da6-47a9-870c-7930c1380758" />

## Data cleaning process
1.The dataset contains 1000 rows and 12 columns.

2.I checked for duplicates but there were no duplicates.

3.I also checked for blank cells but there no blank cells.

4. Originally, there was an "order date/time and delivery date/time column, but i splitted itthem into two by seperating the order date from the order time column and i did the same for the delivery date and time column.

5. I also created a new column named "delivery time (minutes) by subtracting the order time from the delivery time"

6. After getting the delivery time in minutes i had negative values due to AM/PM rollover so that made me create a new column named "delivery time status" so i can know the positive numbers from the negative numbers.

7. After i was done with everything i had 1000 rows and 16 columns

# Analysis insights and recommendation

# 1. Refund Rate by Payment Method 
 ## Insight
 Credit Card has the highest refund rate, Digital Wallet the lowest.
 ## Analysis
 Certain payment methods may be linked to disputes or failed deliveries.
 ## Recommendation
 Investigate refund reasons by payment type and improve checkout or order accuracy.

 # 2. Delivery Time Quality Status

 ## Insight
 94% of deliveries are successful, only 6% fail.
## Analysis
Delivery operations are strong and reliable.
## Recommendation
Use this performance in marketing and maintain delivery standards.

# 3. Most Used Discount Offers
## Insight
High usage of discounts, especially 50% off and new user offers.
## Analysis
Discounts drive orders but may reduce profitability.
## Recommendation
Shift from heavy discounts to loyalty and repeat-customer rewards.

# 4. Total Revenue By Day
## Insight
Revenue fluctuates heavily with sharp drops and spikes.
## Analysis
Demand is inconsistent, making planning difficult.
## Recommendation
Introduce promotions, subscriptions, or campaigns to stabilize daily sales.

# 5. Total Revenue By Payment Method
## Insight
Cash on Delivery generates the highest revenue, but all methods perform closely.
## Analysis
Customers trust multiple payment options.
## Recommendation
Keep all payment options and improve digital wallet adoption.

# 6. Payment Method Distribution
## Insight
Usage is well balanced across payment methods.
## Analysis
No single payment method dominates customer preference.
## Recommendation
Continue offering multiple payment choices to reduce checkout drop-offs.

# Overall Business Summary
## Insight
The business is performing well in revenue and delivery quality.
## Main Risk
Profit loss from refunds, discounts, and unstable daily sales.
## Recommendation
Improve profitability, not just revenue.

# Conclusion
The Food Orders business demonstrates strong revenue performance and reliable delivery operations, with over $1M in total revenue and a 94% successful delivery rate. However, profitability is challenged by high refunds, processing costs, and heavy reliance on discount offers. Revenue fluctuations also indicate unstable daily demand.
To sustain growth, the business should focus on reducing refunds, optimizing discount strategies, stabilizing daily sales, and improving cost efficiency. By shifting attention from revenue growth to profit optimization, the business can achieve more sustainable long-term performance.










