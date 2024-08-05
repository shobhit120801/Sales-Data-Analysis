
# Pandas Data Science Tasks


A brief description of what this project does and who it's for

This project focuses on analyzing a year's worth of sales data from an electronics store using Python Pandas and Matplotlib. The dataset consists of hundreds of thousands of purchases categorized by month, product type, cost, purchase address, and more.


# Data Cleaning
The initial phase involves cleaning up the data by:

1) Removing NaN values from the DataFrame
2)  Filtering rows based on specific conditions
3)  Converting column types using methods such as to_numeric, to_datetime, and astype

# Data Exploration
After cleaning the data, the exploration phase addresses five key business questions:

1) Best Month for Sales: Identifying the most profitable month and determining the revenue earned.

2) Top Selling City: Determining the city with the highest sales volume.

3) Optimal Advertisement Timing: Analyzing the best time to display advertisements to maximize the likelihood of purchases.

4) Frequently Co-Purchased Products: Finding combinations of products that are often purchased together.

5) Top-Selling Product Analysis: Identifying the best-selling product .


# Methods Used
To answer these questions, various Pandas and Matplotlib functionalities are employed, including:

1) Concatenating multiple CSV files using pd.concat
2) Manipulating columns by parsing cells as strings (.str)
3) Applying custom operations using the .apply() method
4) Performing aggregate analysis with groupby
5) Visualizing results using bar charts and line graphs
6) Properly labeling graphs for clarity
