# Bitcoin_Data_Analysis_Project
I recently performed a comprehensive analysis of Bitcoin price data using Jupyter Notebook. The analysis covered various aspects, including data pre-processing, exploratory data analysis, and visualizations.
Reading and Basic Analysis of Data:

The script starts by importing necessary libraries such as Pandas, NumPy, Matplotlib, and Seaborn.
It reads Bitcoin price data from a CSV file into a Pandas DataFrame (df).
Basic exploratory data analysis (EDA) is performed using methods like head(), columns, shape, info(), and describe() to get an overview of the dataset.
Data Pre-processing:

Checks data types, missing values, and duplicate entries.
Converts the 'Date' column to a datetime format for time series analysis.
Sorts the dataset based on the date from oldest to most recent.
Analyzing Change in Price Over Time:

Plots the opening, high, low, and close prices over time using Matplotlib.
Analyzing Open, High, Low, Close Values with Candlestick Charts:

Uses Plotly to create a candlestick chart for a sample of Bitcoin price data.
Analyzing Closing Price on Normal Scale and Log-Scale:

Plots the closing price on a normal scale and a log scale. Logarithmic scales are often used for financial data to better visualize changes over a wide range of values.
Analyzing Closing Price on Yearly, Quarterly, Monthly Basis:

Utilizes Pandas resampling to analyze the average closing price on a yearly, quarterly, and monthly basis.
Analyzing Daily Change in Closing Price:

Calculates the daily percentage change in closing price and plots the results using both Pandas and Cufflinks/Plotly. Cufflinks is used to make the Pandas plot interactive.
Additional Notes:

The script provides explanations and comments throughout, explaining the purpose and functionality of each section.
Various visualization libraries like Matplotlib, Seaborn, and Plotly are used to create interactive and informative plots.
