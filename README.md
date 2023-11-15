# Home_Sales

In this project, I used my knowledge of PySpark and PySQL to determine key metrics about home sales data. Then, I used Spark to create temporary views, partition the data, cache and uncache a temporary table, and verified that the table has been uncached.

Steps:

1) Imported the necessary PySpark SQL functions for this assignment.

2) Read the home_sales_revised.csv data in the starter code into a Spark DataFrame.

3) Created a temporary table called home_sales.

4) Addressed the following questions using SparkSQL:

	* What is the average price for a four-bedroom house sold for each year? Rounded off your answer to two decimal places.

	* What is the average price of a home for each year it was built that has three bedrooms and three bathrooms? Rounded off the answer to two decimal places.

	* What is the average price of a home for each year that has three bedrooms, three bathrooms, two floors, and is greater than or equal to 2,000 square feet? Rounded off your answer to two decimal places.

	* What is the "view" rating for homes costing more than or equal to $350,000? Determined the run time for this query, and rounded off your answer to two decimal places.

	* Cached the temporary table home_sales.

	* Check if the temporary table is cached.

	* Using the cached data, run the query that filters out the view ratings with an average price of greater than or equal to $350,000. Determined the runtime and compared it to uncached runtime.

	* Partitioned by the "date_built" field on the formatted parquet home sales data.

	* Created a temporary table for the parquet data.

	* Ran the query that filters out the view ratings with an average price of greater than or equal to $350,000. Determined the runtime and compared it to uncached runtime.

	* Uncached the home_sales temporary table.

	* Verified that the home_sales temporary table is uncached using PySpark.


																								© 2023 edX Boot Camps LLC
