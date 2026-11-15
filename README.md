# Netflix ETL Pipeline

## What this project does
Reads Netflix data from a CSV file, cleans it using Python (pandas),
loads it into a SQLite database, and answers questions using SQL.

## Tools used
Python, pandas, SQLite, SQL, matplotlib

## Steps
1. Extract: read the CSV file
2. Transform: remove duplicates, fix missing values, fix dates
3. Load: save the clean data into a SQL database
4. Analyze: SQL queries (GROUP BY, ORDER BY, window function RANK)

## Key findings
1. Movies are about _70_% of Netflix content.
2. The most titles were added in the year __2019__.
3. Content added per year grew a lot after 2015.
4. The top country is _USA_, followed by __INDIA__.

## Dataset
Netflix Movies and TV Shows by Shivam Bansal (Kaggle)
