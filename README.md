#### Capstone_Project_4 E-Commerce Business Analytics - Purchasing Trends 
![image](https://github.com/ahwinchan/Capstone_Project_4/assets/144866635/b8aebe94-7964-4488-b103-48dbf50e5905)

# Description of Dataset #
[![image001.png](https://i.postimg.cc/HsY0Br0t/image001.png)](https://postimg.cc/YjPmSqs4)

### Data Cleaning and Transformation - in POWER BI
+ Clean, check null value, duplicate items (can observe it from View TAB - under Column distribution and column quality)
+ Merged first_name and last_name become new customer_name column
+ Create new Dax : syntax sum_ttl purchase = purchase[shipping_cost] + purchase[price] + purchase[tax]

The main dataset used in this capstone is the __ITEMS PURCHASE ONLINE TRANSACTIONS__ in Brazil, Mexico, Colombia and Chile. It mainly consists of all transactions from 15 August 2019 to 01 January 2023 of each item. This includes customer id, item description, order date, order id, price, product name, quantity, shipping cost, shipping date and tax involved in the transactions. __The dataset has a size of 50,000 rows and 11 columns__

The secondary dataset is the customer Information which serves as supplementary information. It mainly consists customer name, gender, age, country of purchase and customer id. The dataset has a size of __1001 rows and 8 columns__

*The top 10 products have been shown insight this visualization from main dataset.  For example, Curtain, lighting, wall art, rugs, Kitchen Appliances, furniture, Appliance set, Dining set, Bedding and Home décor*

*These datasets provide valuable insights into our client base. We've identified key demographics, preferences, and purchasing behaviors that will inform our marketing strategies and product offerings. Additionally, the purchase data highlights popular products and trends, which can guide inventory management and procurement decisions. By leveraging this information, we are poised to enhance customer satisfaction and drive revenue growth*

__Feel free to drop me an email if there any: winnie_chan782003@yahoo.com.sg__
