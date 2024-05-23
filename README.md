Pandas Data Science Tasks
This project focuses on analyzing a year's worth of sales data from an electronics store using Python Pandas and Matplotlib. The dataset consists of hundreds of thousands of purchases categorized by month, product type, cost, purchase address, and more.

Data Cleaning
The initial phase involves cleaning up the data by:

Removing NaN values from the DataFrame
Filtering rows based on specific conditions
Converting column types using methods such as to_numeric, to_datetime, and astype
Data Exploration
After cleaning the data, the exploration phase addresses five key business questions:

Best Month for Sales: Identifying the most profitable month and determining the revenue earned.

Top Selling City: Determining the city with the highest sales volume.

Optimal Advertisement Timing: Analyzing the best time to display advertisements to maximize the likelihood of purchases.

Frequently Co-Purchased Products: Finding combinations of products that are often purchased together.

Top-Selling Product Analysis: Identifying the best-selling product and exploring reasons behind its success.

Methods Used
To answer these questions, various Pandas and Matplotlib functionalities are employed, including:

Concatenating multiple CSV files using pd.concat
Manipulating columns by parsing cells as strings (.str)
Applying custom operations using the .apply() method
Performing aggregate analysis with groupby
Visualizing results using bar charts and line graphs
Properly labeling graphs for clarity
Instructions
To run the analysis and explore the findings, simply clone this repository and execute the provided Python scripts.
