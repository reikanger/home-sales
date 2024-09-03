# Home Sales Metrics

## Background
The `Home_Sales.ipynb` notebook determines metrics about home sales data using **SparkSQL**.

The code features using Spark to create temporary views, query the data, partition the data, cache and uncache a temporary table, and verify that the table has been uncached.

Questions Answered via SparkSQL:
- What is the average price for a four-bedroom house sold for each year?
- What is the average price of a home for each year the home was built, that has three bedrooms and three bathrooms?
- What is the average price of a home for each year the home was built, that has three bedrooms, three bathrooms, two floors, and is greater than or equal to 2,000 square feet?
- What is the average price of a home per "view" rating having an average home price greater than or equal to $350,000?
