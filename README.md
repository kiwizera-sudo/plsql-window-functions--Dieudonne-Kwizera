Business Context
Kwizera.co Ltd., a retail company in Rwanda, sells food and beverages across regions of Rwanda.
Data Challenge
The company generates thousands of sales transactions monthly, but management struggles to identify top customers by revenue, track sales growth trends, and segment customers effectively. Without insights, marketing campaigns and inventory planning remain inefficient.
Expected Outcome
•	Identify top-performing customers and products.
•	Track running totals and trends.
•	Analyze month-over-month growth.
•	Segment customers into quartiles.
•	Provide actionable insights for business strategy.
________________________________________
Database Schema
Tables
•	customers (customer_id, name, region)
•	products (product_id, name, category)
•	transactions (transaction_id, customer_id, product_id, sale_date, amount)





ER Diagram
 
In this picture we see the relationship diagram 
________________________________________
 Window Function Implementations
Ranking Functions – Top  Customers by Revenue
 
 
 
Interpretation: Ranking functions help identify top customers, while handling ties differently.
________________________________________
 Aggregate Functions – Running Totals & Trends
  
Interpretation: Aggregates show cumulative totals and trends over time.
________________________________________
Navigation Functions – Period-to-Period Analysis
 
Interpretation: Navigation functions show changes between periods to measure performance.
________________________________________
Distribution Functions – Customer Segmentation
 
Interpretation: Distribution functions divide customers into segments, useful for marketing and loyalty programs.
________________________________________
5. Results Analysis
•	Descriptive – What happened?
Kigali recorded the highest sales, with Coffee Beans and Tea dominating.
•	Diagnostic – Why did it happen?
Kigali benefited from higher urban demand and frequent promotions, while Musanze lagged due to limited product range.
•	Prescriptive – What next?
Expand successful products in Kigali, and introduce discounts or promotions in Huye and Musanze to boost performance.
________________________________________
6. References
1.	Oracle Docs – Analytic Functions
2.	MySQL Docs – Window Functions
3.	GeeksforGeeks – SQL Window Functions
4.	TutorialsPoint – SQL Analytics Functions
5.	W3Schools – SQL OVER Clause
6.	DataCamp – Intro to SQL Window Functions
7.	Mode Analytics – SQL Window Functions Guide
8.	Oracle Academy Learning Resources


