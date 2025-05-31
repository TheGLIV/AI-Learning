# Day 2: CSV Operations & Pandas Fundamentals
On Day 2, I explored Pandas, the core data manipulation library in Python.

## What I Practiced:
-Reading CSV files using pd.read_csv()

-Inspecting datasets using .head(), .info(), .describe()

-Handling missing data with:

-dropna() to remove

-fillna() to impute

-Filtering rows based on conditions

-Using .groupby() to perform aggregated operations

-Sorting data with .sort_values()

-Exporting data:

-to CSV using .to_csv()

-to Excel using .to_excel()

## Files Added:
pandas_basics.ipynb – Full code walkthrough

sample_csv_file.csv – Dummy data for practice

cleaned_data.csv – Exported after cleaning

cleaned_data_excel.xlsx – Same as above, in Excel format

## Notes:

Pandas chaining (df[df['col'] > x].groupby('other')) can be powerful but needs practice.

Handling missing values is crucial for any real-world dataset.

Exporting allows you to bridge analysis with external reporting tools.

