# PROJECT-1-
## SALES ANALYSIS
### Project Overview

This analysis examines the trends, opportunities and areas for improvement in the business on regional bases and product bases.

### Data Collected 

The analysis is based on data collected from 2023 and 2024.
The dataset includes 9 key variables:
1. OrderID: Identication for each order
2. CustomerID : Identication for each customer
3. Product : Items being sold
4. Region: Geographical area where business took place
5. Orderdate: Date order was made
6. Quantity: Number of product sold
7. Unityprice: Price of each product
8. Revenue: Income generated in the business
9. Average: Statistical measure to describe a value

### Data quality and preparation

To ensure data accuracy and reliability i conducted thorough cleaning
- Addressed missing values and inconsistencies
- Transformed data formats for consistency

### Tools used

Excel:
The data was analyzed with microsoft Excel, using pivot tables to organize, summarize and filter the data for easy interpretation.
SQL:
Structured Query Language, i used it to run some querries on the data.
Power BI:
Power BI is a business analytics service by microsoft.
I used power BI for the data visualization in this project, cards, tables and charts.

### Key Metric
=Average(revenue) 
```
select * from SALES
select product, sum(revenue)as totalsales from Sales
Group by product
```
Measure 
Count of product=count(sales(product))

### Project objective

This project was made to achieve these goals:
1. Regional performance
2. Product sales
3. sales growth
4. monthly sales trends

### Data Analysis
Regional Performance
![REGIONAL PERFORMANCE](https://github.com/user-attachments/assets/8b0f1463-d991-4c62-a837-a824f1cd91b0)


- The South region leads with 475,000 in sales(32% of total) and 4,675,000 in revenue(44% of total)
- The North region follows with 425,000 in sales(29% of total) and 1,950,00 in revenue(18% of total)
- The East and West regions have opportunities for growth.

Product sales
![PRODUCT SALES](https://github.com/user-attachments/assets/dcb92849-62ae-4572-afee-1d6172632df6)


Top selling products
Shoes has sales of 350,000, 
Jacket has the sales of 312,500
Shirt has the sales of 275,000.
Gloves and Socks show potential for growth

Monyhly sales trends
![MONTHLY SALES TRENDS](https://github.com/user-attachments/assets/af350e37-a870-428e-84da-d7a2be16bdac)


Februrary 2024 shows the highest sales at 150,000 driven by shoes.
August 2024 performed well with 125,000 in sales.

Sales Growth
South Region: 21% growth from 2023 to 2024
North Region: 12% decline from 2023 to 2024
East Region: 72% decline from 2023 t0 2024

### Key Insights:

1. Regional imbalance: focus on improving East and West regional sales.
2. Product opportunities: Expand shoes, jacket and shirt product lines
3. Revenue growth: Target high revenue regions like the South.
4. Sales decline: Investigate causes of decline in North and East regions.
5. Seasonal trends: Capitalize on peak sales months( february, August).

### Action Plan:

- Develop targeted marketing campaigns for East and West regions.
- Increase product offerings in shoes, jacket and shirt categories.
- Enhance sales strategies in high revenue regions.
- Analyze and address sales declines causes.
- Optimize inventory management for seasonal demand.

### Visualization
![SALES ANALYSIS](https://github.com/user-attachments/assets/f61974ca-0e91-4701-ad1f-e471f67986fd)

![SALES HIERARCHY](https://github.com/user-attachments/assets/68acd0f4-1640-49fa-9568-85f9bb878bbb)

### Conclusion:

Addressing these insights and opportunities, it can drive business growth,
improve regional sales preformance and increase revenue.






















