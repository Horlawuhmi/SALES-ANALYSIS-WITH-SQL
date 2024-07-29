# SALES-ANALYSIS-WITH-SQL
This detailed business sales analysis provides a dive into sales data, the key insights and trends that can drive positive growth.
By examining various ascept of the sales process, including product performance, store efficiency, and sales representative effectiveness, we aim to provide actionable recommendations that can enhance overall business performance.

# About the data
The dataset used in this analysis comprises four key tables: Sales, Products, Stores, and Sales Representatives. The data has 3000 sales transactions recorded over a one-year period, with  information on each sale, including product details, customer information, store locations, and sales representatives involved. The dataset also, includes additional columns such as payment methods, store identifiers, and inventory levels.
# Tables
# Sales
* SaleID
* Date
* ProductID
* CustomerID
* Quantity
* UnitPrice
* TotalPrice
* StoreID
* PaymentMethod
* SalesRepID.
# Products
* ProductID
* ProductName
* Category
* SupplierID
* UnitPrice
* StockQuantity
* ReorderLevel
* Discontinued.
# Stores
* StoreID
* StoreName
* Location.
# Sales Representatives
* SalesRepID
* SalesRepName
* HireDate
* StoreID.

# Data Preparation
Using MySQL Workbench to import the data into the table took considerable time. I created a schema and renamed the table for import. Prior to exploring the data, I checked the number of rows and columns, check for duplicates.
![SQL PROJECT QUERY 1](https://github.com/user-attachments/assets/407a0b6b-504f-473c-a5e4-469416d6e3af)    

# Objectives
# The primary objectives of this analysis are:
* To identify sales trends and patterns across different product categories, stores, and sales representatives.
* To evaluate the performance of different payment methods and their impact on sales.
* To assess the inventory status and identify products that require reordering.
* To analyze the geographic distribution of sales and identify high-performing locations.
* To provide actionable recommendations for improving sales performance and inventory management.

# Data Exploration
# 1.  Total Sales by Category and Store
![total sum by cat](https://github.com/user-attachments/assets/12d3cfbb-d6bc-4b62-a9b3-2e486b97989d)
![total sum by store](https://github.com/user-attachments/assets/a88952d0-de68-42e8-b5b2-5b6c6ba16a29)             
_The highest sales were recorded in the Books category with a total of $3,802,732. The Home category followed with $3,379,174 in total sales. Store 2 recorded the highest sales overall. Conversely, Store 12 had the lowest sales._

# 2. Top 5 Sales Representatives by Total Sales
![sales rep](https://github.com/user-attachments/assets/90f32451-733e-4d0f-a9dc-fdb701f241da)
_Rep 44 achieved the highest individual sales, totaling $449,604. Rep 15 followed closely with sales amounting to $426,188._

# 3. Sales Performance by Payment Method
![Payment method img](https://github.com/user-attachments/assets/b287a809-b0d1-4282-8377-f3831ece951a)                   
_Credit Card payments led the total sales with $5,636,882 across 1011 transactions. Cash payments followed with $5,284,566 over 999 transactions. Online Payments accumulated $5,430,731 from 990 transactions._

#  4. Monthly Sales Trend by Store
![month sales img](https://github.com/user-attachments/assets/e92646ed-8a8d-4c03-a8cc-dfb1dc561ff5)   
_There was a significant reduction in sales in May. Sales declined slightly in August and experienced another drop in November._

# 5. Product Inventory Status
![product invent stock](https://github.com/user-attachments/assets/f624f913-e850-4448-a1b2-7605a3467c01)               
_The Sports and Home categories had the lowest reorders, with 0 and 6 items reordered respectively._

# 6. Average Sales per Customer
![avg sales image](https://github.com/user-attachments/assets/0f451553-c24c-42c4-93ff-6d89175de934)

# 7. Sales Distribution by City
![city sales image](https://github.com/user-attachments/assets/5cf62edc-e336-4f47-a410-071d5c1d4fc5)             
_Los Angeles led with total sales of $4,255,695. Phoenix followed closely with $4,213,648. The lowest sales were recorded in Houston with $2,358,602._

# 8. Discontinued Products Sales
![discounted image](https://github.com/user-attachments/assets/c8dd39cb-d60f-4e92-8f63-5e25865549af)                    
_The Books category contributed the most to discounted product sales, totaling $1,982,714._

# Recommendations

* 1. Focus on High-Performing Categories:
Enhance marketing efforts and inventory management for Books and Home categories to sustain and boost their high sales performance.
* 2. Improve Low-Performing Stores:
Investigate the factors leading to the low sales at Store 12 and implement targeted strategies to improve its performance.
* 3. Leverage Top Sales Representatives:
Recognize and reward top-performing representatives like Rep 44 and Rep 15. Encourage knowledge sharing and best practices among the sales team.
* 4. Optimize Payment Methods:
Promote and possibly incentivize the use of Credit Cards and Online Payments due to their higher transaction values.
* 5. Analyze Sales Trends:
Investigate the causes behind the sales reductions in May, August, and November. Develop strategies to mitigate such declines in the future.
* 6. Monitor Inventory:
Review the inventory policies for the Sports and Home categories to ensure optimal stock levels and minimize stockouts.
* 7. Expand Customer Base:
Use the average sales per customer data to develop targeted campaigns aimed at increasing the number of high-value customers.
* 8. Focus on Regional Sales:
Tailor marketing and sales strategies to boost performance in cities like Houston where sales are lower.
* 9. Maximize Discounted Sales:
Continue offering attractive discounts on Books and explore similar strategies for other categories to drive sales.

# Conclusion
The analysis reveals insights into sales performance across various categories, stores, and payment methods. By focusing on high-performing areas, addressing underperformance, and leveraging top sales representatives, the overall sales can be optimized. 
Additionally, understanding and mitigating sales trends and improving inventory management will contribute to sustained growth and customer satisfaction.

![SQL PROJECT QUERIES](https://github.com/user-attachments/assets/58d132a8-0d0e-474f-b876-110208f99cab)






