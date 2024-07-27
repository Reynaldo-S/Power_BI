# Dashboard Creation Report

This report details the process of creating a dashboard using data from the 'Walmart.csv' file, hosted on GitHub. The dashboard is designed to provide the details of sales, customer and product performance. The following sections outline the API selection, data fetching steps, and the visual elements used in the dashboard.

## API Selection and Data Fetching

## API Selection
The chosen API is a CSV file hosted on GitHub, the relevant URL given below https://raw.githubusercontent.com/LokeshKumarChauhan/DE_with_powerBI/main/Walmart.csv
This file contains relevant data for creating the dashboard.

## Data Fetching
The data is fetched using Python code, which imports the Pandas library to read the CSV file from the specified URL.


## Python Code:

import pandas as pd

url = "https://raw.githubusercontent.com/LokeshKumarChauhan/DE_with_powerBI/main/Walmart.csv"
df = pd.read_csv(url)
df.info()


# Visuals Used in the Dashboard
•	Cards
•	Waterfall Chart
•	Stacked Bar Chart
•	Line Chart
•	Table


