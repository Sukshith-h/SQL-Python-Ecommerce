E-commerce Data Analytics Project

Overview

This project focuses on analyzing e-commerce data to gain insights into customer behaviors, sales trends, and payment methods using SQL and Python. The analysis explores various facets of the dataset, from basic metrics such as the number of orders per year to advanced insights like customer retention rates and sales growth.

Features:

Data Extraction: SQL queries to fetch and analyze key data points such as order counts, total sales, and customer locations.


Advanced Analytics: Calculation of moving averages, cumulative sales, and customer retention rates.


Data Visualization: Python (matplotlib, seaborn) used to visualize the data trends and correlations between different metrics.


Technologies Used


SQL: For querying and extracting insights from the database.


Python: Libraries such as pandas, matplotlib, and seaborn for data analysis and visualization.


Project Highlights


Basic SQL Queries


1.List of unique cities where customers are located.

2.Count the number of orders placed in 2017.

3.Total sales by product category.

4.Percentage of orders paid in installments.

5.Count of customers by state.

Intermediate SQL Queries:


1.Number of orders per month in 2018.

2.Average number of products per order, grouped by city.

3.Percentage of total revenue by product category.

4.Correlation between product price and number of times it was purchased.

5.Total revenue generated by each seller, ranked.

Advanced SQL Queries:

1.Moving average of order values for each customer.

2.Cumulative sales per month for each year.

3.Year-over-year growth rate of total sales.

4.Customer retention rate (percentage of customers making another purchase within 6 months).

5.Top 3 customers by spend in each year.


Getting Started


Prerequisites

To run this project, ensure you have the following installed:

Python 3.7+

MySQL or PostgreSQL

Libraries: pandas, matplotlib, seaborn

Setup Instructions

Clone the repository:

git clone https://github.com/yourusername/ecommerce-data-analytics.git

cd ecommerce-data-analytics

Set up the database: Ensure your e-commerce database is running and accessible. You can use the provided connection.ipynb to establish a connection to the database.

Install dependencies:       
      pip install -r requirements.txt

Run the Jupyter Notebook: Open and run the project.ipynb in Jupyter to perform the analysis:

"jupyter notebook project.ipynb"

Visualizations

Some of the key visualizations generated by the project:

Top customers by spend: Displays the highest spending customers per year using a bar chart.

Cumulative sales trend: Line charts showing sales trends over time.


