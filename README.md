# Car Sales Analysis - Power BI Dashboard
## Overview
The Car Sales Analysis Power BI dashboard offers comprehensive insights into sales performance across various regions, customers, car models, salespersons, and car stock price trends. The dashboard visualizes and analyzes key metrics, helping stakeholders make data-driven decisions regarding sales strategies, customer engagement, and inventory management.

## Data Model Overview
The Power BI dashboard is built on a well-structured dataset comprising multiple related tables. The data is connected through foreign keys to provide a unified view of the car sales operations.

## Key Tables and Columns
1) Regions:
   
  RegionID: Unique identifier for each region.
  
  Country: Country where the region is located.
  
  State/Province: State or province within the country.
  
  City: City within the region.

2) Salespersons:
   
  SalespersonID: Unique identifier for each salesperson.
  
  SalespersonName: Name of the salesperson.
  
  RegionID: Region where the salesperson works.
  
  TotalSalesBySalesperson: Total sales made by the salesperson.
  
  Hiredate: The hire date of the salesperson.

4) Customers:
   
  CustomerID: Unique identifier for each customer.
  
  CustomerName: Name of the customer.
  
  Age: Age of the customer.
  
  Gender: Gender of the customer.
  
  IncomeLevel: Customer’s income level.
  
  RegionID: Region of the customer.
  
  LoyaltyProgramMember: Whether the customer is a loyalty program member.
  
  TotalSalesByCustomer: Total sales made by the customer.

5) CarModels:
     
  CarModelID: Unique identifier for each car model.
  
  CarMake: Manufacturer of the car.
  
  CarModel: Name of the car model.
  
  CarType: Type of car (e.g., sedan, SUV).
  
  CarCategory: Category of the car (e.g., luxury, economy).
  
  CarPrice: Price of the car.
  
  YearOfManufacture: Year of manufacture for the car model.
  
  TotalSalesByCarModel: Total sales of that car model.

6) Promotions:
   
  PromotionID: Unique identifier for each promotion.
  
  PromotionName: Name of the promotion.
  
  DiscountRate: Discount rate applied during the promotion.
  
  StartDate: Start date of the promotion.
  
  EndDate: End date of the promotion.

7) CarStockPrices:
   
  StockPriceID: Unique identifier for each stock price entry.
  
  CarModelID: Car model identifier.
  
  Date: Date of the stock price record.
  
  OpeningPrice: Opening price of the car stock.
  
  ClosingPrice: Closing price of the car stock.
  
  HighestPrice: Highest price during the day.
  
  LowestPrice: Lowest price during the day.
  
  VolumeTraded: Volume of stock traded.

8) Sales:
   
  SaleID: Unique identifier for each sale.
  
  DateOfSale: Date the sale occurred.
  
  SalesPrice: Price at which the car was sold.
  
  CarModelID: Car model sold.
  
  SalespersonID: Salesperson involved in the sale.
  
  RegionID: Region where the sale took place.
  
  CustomerID: Customer who purchased the car.
  
  TransactionID: Unique identifier for the transaction.
  
  PromotionID: Identifier for any promotion applied during the sale.

## Dashboard Overview
### Key Visualizations:

1) Sales Overview:
Total sales figures and trends, visualized over time to understand overall sales performance.
Key metrics include total revenue, number of cars sold, and average sales price.

2) Sales by Region:
Visualizes sales performance across different regions, highlighting top-performing regions.
Allows users to drill down by country, state, and city.

3) Sales by Customer:
Displays sales performance segmented by customer demographics such as age, gender, income level, and loyalty program membership.
Helps identify trends in customer purchasing behavior.

4) Sales by Car Model:
Provides insights into which car models are performing best in terms of sales.
Includes detailed analysis by car type, category, and price.

5) Sales by Salesperson:
Compares salesperson performance based on total sales.
Identifies top-performing salespeople and regions where they excel.

6) Car Stock Price Analysis:
Analyzes stock price trends of car models, displaying opening, closing, highest, and lowest stock prices.
Visualizes the volume of stocks traded and their impact on car sales.

## Key Insights and Analysis
1) Regional Sales Performance: Identify which regions are contributing the most to total sales and where there is room for improvement.

2) Customer Insights: Understand customer purchasing patterns, including which demographics are driving sales and which may need targeted marketing efforts.

3) Car Model Trends: Track which car models are in high demand and adjust inventory or promotional strategies accordingly.

4) Salesperson Performance: Evaluate the performance of individual salespeople and identify best practices or areas for additional training.

5) Stock Price Correlation: Monitor the effect of stock price trends on sales figures and market behavior.

Conclusion
The Car Sales Analysis Power BI dashboard provides a rich set of visualizations and metrics that help businesses track and improve sales performance across regions, car models, and customer demographics. By leveraging the interactive capabilities of Power BI, users can dive deep into the data, uncover trends, and make informed decisions to optimize sales strategies.

Screenshots:
![{8C952C23-9B02-427D-A1B0-08066A209515}](https://github.com/user-attachments/assets/10513c6c-cbaf-44e2-b3d3-84759ed36bab)

![{4FA80CAC-9618-4E63-ACAF-89A22847654C}](https://github.com/user-attachments/assets/fcf9a134-be6e-458e-8640-8eb1e58ca138)

![{6D54E208-C81C-4C3C-A038-D423AB8D1A7D}](https://github.com/user-attachments/assets/4f1c68cc-637c-4b73-8f3a-97b7b321da6d)

![{7B60FC00-8A98-4454-B1FB-6DDB94FF5BE9}](https://github.com/user-attachments/assets/ab3bda3c-7e61-4efe-992b-6d94df091b19)

![{B46A1EE2-27C9-45C5-B44B-CE990C2DD617}](https://github.com/user-attachments/assets/38c3779f-9299-4edf-9117-6f4ebe5aab29)

![{852D03FE-90B2-4269-9CDF-75C6AEB8FDBF}](https://github.com/user-attachments/assets/ee4067a9-6907-4a33-bcbe-476262894af6)

![{BF024F30-3FB7-4E33-B265-C7DBC20A0082}](https://github.com/user-attachments/assets/727d0df1-38e3-420c-ac3c-826e8b3e42f8)

![Uploading {D1DD8A67-918C-4247-84E1-467889061E41}.png…]()









