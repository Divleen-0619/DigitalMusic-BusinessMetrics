# Analyzing Key Business Metrics for a Digital Music Store Using SQL
Welcome to the Digital Music Store Business Metrics Analysis project. This project leverages SQL to analyze key business metrics for a digital music store, providing actionable insights and strategic recommendations. The primary objective is to help understand customer behavior, sales trends, and other critical business metrics to make data-driven decisions.

![ImageAlt](https://github.com/Divleen-0619/DigitalMusic-BusinessMetrics/blob/d93cd6972dc0f509e5fd8a3b5e757e7bab83d5e8/lively%20landscape%20cover%20page%20for%20a%20digital%20music%20store%20analysis.png)

# **Business Questions**
1. Who is the most senior employee based on the job title?
2. Which countries have the most invoices?
3. What are the top 3 values of total invoices?
4. Which city has the best customers in terms of total invoice amounts?
5. Who is the best customer based on the total money spent?

# **Data**
The project utilizes the following data sets:

1. Customer Transactions: Details of purchases made by customers.
2. Genre Information: Information about the genre available in the store.
3. Sales Data: Records of sales transactions including invoice details.

# **Setup**
To set up the project locally, follow these steps:

1. Clone the repository:
git clone [https://github.com/Divleen-0619/DigitalMusic-BusinessMetrics/tree/main]
2. Navigate to the project directory:
cd DigitalMusic-BusinessMetrics
3. Set up the database:
createdb your_database_name
4. Run the SQL scripts to create tables and insert data:
psql your_database_name < scripts/create_tables.sql
psql your_database_name < scripts/insert_data.sql

# The project focuses on the following key **business metrics**:

1. Total Revenue: Sum of all invoice totals.
2. Top 3 Invoice Totals: Highest values of invoice totals.
3. Customer Lifetime Value (CLV): Total money spent by each customer.
4. Number of Invoices per Country: Count of invoices grouped by country.
5. Total Sales by Artist: Sum of sales grouped by artist.

# **Analysis:**
The analysis covers several aspects of the business, including:

1. Most Senior Employee
Who is the most senior employee based on the job title: Identifying the employee with the highest job title level.
2. Invoice Distribution by Country
Which countries have the most invoices: Determining the countries with the highest number of invoices to understand regional sales distribution.
3. Top Invoice Totals
What are the top 3 values of total invoices: Identifying the largest transactions by analyzing the top 3 highest invoice totals.
4. Best Customers by City
Which city has the best customers in terms of total invoice amounts: Identifying the city with the highest sum of invoice totals to pinpoint locations with the best customers.
5. Top-Spending Customer
Who is the best customer based on the total money spent: Recognizing the customer who has spent the most money to identify valuable customer profiles.
6. Rock Music Listeners
Email, first name, last name, genre of all rock music listeners: Segmenting rock music listeners based on email, first name, and last name for targeted marketing.
7. Top Rock Music Artists
Top 10 artists who have written the most rock music tracks: Identifying and understanding the most prolific rock music artists.
8. Longest Tracks
Tracks with lengths longer than the average song length: Analyzing tracks with unique characteristics by identifying those longer than the average length.
9. Customer Spending on Artists
Total amount spent by each customer on different artists: Understanding customer preferences by identifying the total spending on various artists.
10. Popular Genre by Country
Most popular genre in each country based on purchases: Identifying regional music preferences by determining the most popular genre in each country.
11. Top-Spending Customers by Country
Customer who has spent the most on music in each country: Recognizing key customers in each region by analyzing total spending per customer by country.

# **Recommendations**
Based on the analysis, the following recommendations are made to guide teams:

1. Increase Marketing Efforts in High Revenue Cities: Focus promotional activities in cities that generate the most revenue.
2. Target High-Spending Customers: Offer personalized promotions to customers who spend the most money.
3. Analyze Senior Employee Roles: Understand the impact of senior employees on business performance and explore ways to utilize their expertise.
4. Expand in Top Invoice Countries: Consider business expansion in countries with the highest number of invoices.
5. Engage with Popular Artists: Collaborate with artists who have the most rock music tracks, as they might attract more customers.

# **Conclusion**
By analyzing these key business metrics and customer purchase behaviors, we can derive data-driven insights to enhance sales revenue and improve customer retention. The insights provided by this analysis can help in making strategic decisions that drive business growth.

# **Results**
1. Most Senior Employee: The most senior employee is identified based on job title level.
2. Invoice Distribution: Countries with the most invoices are identified, with specific counts.
3. Top Invoices: Top 3 highest invoices are highlighted.
4. Best Customers: Cities with the highest invoice totals and the best customers are pinpointed.
5. Customer Spending: Detailed insights into customer spending patterns on different artists and genres are provided.

# **Credits and Acknowledgments**
1. Data Source: [https://drive.google.com/file/d/1MC4xgRlf51HISE1iyf9dJpdy6ATI1spP/view]
2. Inspiration: [https://github.com/rishabhnmishra/SQL_Music_Store_Analysis/commits?author=rishabhnmishra]

# **Contact**
For any questions or collaboration opportunities, please reach out to divleenkaurchaudhery@gmail.com .
