# SalesAnalytics_Python

Project: Statistical Analysis of Sales Data

Dataset: The dataset consists of sales data from 12 CSV files, each representing a different month. Each CSV file contains the following columns:

1. Order ID: A unique identifier for each order.
2. Product: The name of the product ordered.
3. Quantity Ordered: The quantity of the product ordered in each transaction.
4. Price Each: The price of each unit of the product.
5. Order Date: The date and time when the order was placed.
6. Purchase Address: The address where the purchase was made.

The data is structured in a tabular format, with each row representing a single transaction. The dataset provides valuable information for analyzing sales trends, such as the 
quantity of products sold, the revenue generated, and the popularity of different products. It can also be used to analyze the impact of factors like time of year and location on sales.
By combining and analyzing the data from all 12 CSV files (all_data.csv), a comprehensive analysis of sales performance over the entire year can be conducted. 


Description: This project involved a thorough statistical analysis of monthly sales data using Pandas and Python. The dataset comprised sales data from multiple CSV files, 
which were merged into a single CSV file to facilitate data analysis. The first step of the analysis involved data cleaning, where unwanted entries such as NaN values were 
removed using the dropna function. Additionally, incorrect data entries were identified and rectified. Data formatting techniques, such as astype and to_datetime, were applied to 
ensure consistency and accuracy in the data. To enhance the dataset for more detailed analysis, additional columns were added using techniques like str.split and dt.hour. 
These new columns provided valuable insights and allowed for a more comprehensive analysis of the sales data.


The following questions were answered and plotted throughout the analysis:
1. What was the best month for sales? How much was earned that month?
2. What city sold the most product?
3. What time should we display advertisements to maximize the likelihood of customers buying products?
4. What products are most often sold together?
5. What product sold the most? Why do you think it sold the most?


