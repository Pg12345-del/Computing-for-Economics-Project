Methodology and Data Source
 Data Source: Ministry of Consumer Affairs, India
 Dataset: Monthly Consumption Index (MCI) panel data in .parquet format.
 Tools Used: Python libraries — pandas, duckdb, matplotlib, statsmodel , numpy
 , fastparquet
 Method:
 1. Loaded panel data and processed it using DuckDB.
 2. Grouped households by income quantiles (quartiles).
 3. Computed average income and expenditure by year.
 4. Calculated budget shares by region and income groups.
 5. Plotted Engel curves to visualize the relationship between income and spending.
