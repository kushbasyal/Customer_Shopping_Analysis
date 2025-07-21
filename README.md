
# Customer Shopping Data Analysis and Dashboard Project
The primary purpose of this project is to analyze customer shopping behavior using transaction data and to provide actionable business insights through data visualization. By cleaning and processing raw customer data, performing statistical and time-based analyses, and presenting the results in inteactive Power BI dashboards, this project aims to support data-driven decision-making for key stakeholders such as business analysts, marketing teams, and store managers.

## Business Objectives and Key Questions
This projects aims to uncover insights from customer transaction data using SQL, Python, and Power BI. Below are the key buiness questions addressed, along with their purpose and relevance for stakeholders.

1. What is the total revenue, total number of orders, total quantity sold, and average revenue per customer across all transactions?

2. How has the monthly revenue changed over time, and what patterns or seasonal trends can be observed from the revenue line chart?

3. Which product categories have the highest number of orders and revenue, and how do they compare with other categories in terms of performance?

4. How does the revenue, number of orders, and quantity sold in the current month compare with the previous month, and did the company meet its target growth (e.g., 10% increase)?

5. Who are the top customers based on the total amount they have spent, and what impact do they have on overall revenue?

6. Which shopping malls have the highest number of unique customers, and how does that relate to overall sales performance?

7. Which payment methods are most commonly used by customers?

8. How has the total revenue changed year-over-year, and which years performed best?


## Workflow Details
The workflow starts by loading raw customer shoping data into Python for cleaning, handling missing values, fixing data types, removing duplicates, and feature engineering. Next, statistical anlysis and grouping are performed, including time series analysis. Data is then visualized using Matplotlib ans Seaborn. The cleaned datset is exported to CSV and imported into MySQL, with optimized tables. Key business metrics are retrieved via SQL queries, and finally Power BI connects to the database to create interactive, sharable dashboards for stakeholders.

---

## Tools and Technologies

- Python (pandas, numpy, matplotlib, seaborn)
- MySQL
- Power BI Desktop
---
## Key Insights
Based on the analysis aligned with the key business questions, we identified important insights about customer behavior, sales performance, and operational trends. These finding provide actionable information to help stakeholders make informed decisions and optimize buiness strategies

#### Overall Revenue and Sales
The business generated a total revenue of $252.5 million from 99,500 orders, selling approximately 298,700 items. On average, each customer contributed $2,500 in revenue, indicating strong customer spending and a healthy sales volume across transactions.
#### Monthly Revenue Trends
From January 2021 to early 2023, monthly revenue remained relatively steady with minor fluctuations. The lowest revenue occurred in January 2022, which may be attributed to the period immediately following the holiday season when customer spending typically slows down. Overall, sales show consistent performance with expected dips during off-peak periods.
#### Top Product Categories
Clothing is clearly the most popular category, with 34,500 orders—more than double the next biggest category, cosmetics, which has 15,100 orders. Food and beverages, toys, and shoes follow closely behind, each with around 10,000 to 15,000 orders. This shows that clothing is the main driver of sales, while the other categories also play important roles but at a smaller scale.
#### Month-over-Month Comparison
Compared to the previous month, revenue saw a slight increase from $9.49 million to $9.51 million. However, the number of orders actually decreased from 3,926 to 3,628. The company set a target of 4,319 orders and $10.43 million in revenue for the current month but fell short on both fronts. This indicates that while revenue held steady, order volume declined, and the growth targets were not met, highlighting areas for improvement in sales and customer acquisition.
#### Top Customers
Several customers each contributed the highest individual revenue of $26,250. These top spenders play a crucial role in driving overall revenue, highlighting the importance of maintaining strong relationships with high-value customers.
#### Top Performing Shoping Malls
Analysis of unique customers and total revenue reveals that the top three malls are Mall of Istanbul (19,943 customers, $50.87M revenue), Kanyon (19,823 customers, $50.55M revenue), and Metrocity (15,011 customers, $37.30M revenue). These locations drive the majority of foot traffic and sales, making them key focus areas for business growth and targeted marketing efforts.
#### Yearly Revenue Trend
Total revenue was stable from 2021 to 2022, with $114.56 million in 2021 and a slight increase to $115.44 million in 2022. The lower figure of $21.5 million for 2023 is due to the dataset covering only the early months of the year. This indicates consistent business performance over the full years analyzed, with 2023 results incomplete.
#### Payment Method Analysis
Almost half of all customers pay with cash (44.7%), while credit cards account for 35.1% and debit cards 20.2% of transactions. This mix shows that many customers still prefer cash, but digital payments are also widely used. Therefore, it’s best for the business to offer both cash and card payment options to cater to all customer preferences and ensure a smooth checkout experience.
## Conclusion 
This project helps understand customer behavior and sales trends, making it easier to make smart business decisions. It lays a good foundation for future improvements like better customer targeting and sales forecasting.

## Contact

For questions or suggestions, please contact Kushal Basyal at kushalbasyal123@gmail.com
