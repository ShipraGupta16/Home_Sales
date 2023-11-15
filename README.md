# Home_Sales

In this project, I used my knowledge of PySpark and PySQL to determine key metrics about home sales data. Then, I used Spark to create temporary views, partition the data, cache and uncache a temporary table, and verified that the table has been uncached.

Steps:

1) Imported the necessary PySpark SQL functions for this assignment.

2) Read the home_sales_revised.csv data in the starter code into a Spark DataFrame.

3) Created a temporary table called home_sales.

4) Addressed the following questions using SparkSQL:

	* What is the average price for a four-bedroom house sold for each year? Rounded off your answer to two decimal places.

![Screenshot 2023-11-14 at 10 27 11 PM](https://github.com/ShipraGupta16/Home_Sales/assets/25715747/4036bba7-ae24-4ee5-8f38-a551ad72021d)

	* What is the average price of a home for each year it was built that has three bedrooms and three bathrooms? Rounded off the answer to two decimal places.

![Screenshot 2023-11-14 at 10 27 34 PM](https://github.com/ShipraGupta16/Home_Sales/assets/25715747/267c409c-dded-4854-a10d-868904f4481c)

	* What is the average price of a home for each year that has three bedrooms, three bathrooms, two floors, and is greater than or equal to 2,000 square feet? Rounded off your answer to two decimal places.

![Screenshot 2023-11-14 at 10 27 54 PM](https://github.com/ShipraGupta16/Home_Sales/assets/25715747/38fcaa2e-1ea3-4681-a1b5-a2fd17594ab0)

	* What is the "view" rating for homes costing more than or equal to $350,000? Determined the run time for this query, and rounded off your answer to two decimal places.
 
![Screenshot 2023-11-14 at 10 28 13 PM](https://github.com/ShipraGupta16/Home_Sales/assets/25715747/30238fbd-71c6-48b5-96d9-11f92cda8c7b)

	* Cached the temporary table home_sales.

	* Check if the temporary table is cached.

	* Using the cached data, run the query that filters out the view ratings with an average price of greater than or equal to $350,000. Determined the runtime and compared it to uncached runtime.

![Screenshot 2023-11-14 at 10 28 39 PM](https://github.com/ShipraGupta16/Home_Sales/assets/25715747/c7126d04-1667-44a6-b678-f1bcc57bbb55)

	* Partitioned by the "date_built" field on the formatted parquet home sales data.

	* Created a temporary table for the parquet data.

	* Ran the query that filters out the view ratings with an average price of greater than or equal to $350,000. Determined the runtime and compared it to uncached runtime.

![Screenshot 2023-11-14 at 10 29 04 PM](https://github.com/ShipraGupta16/Home_Sales/assets/25715747/4039ad68-5b79-4e7e-bce6-ae9a42b7c279)

	* Uncached the home_sales temporary table.

	* Verified that the home_sales temporary table is uncached using PySpark.



© 2023 edX Boot Camps LLC
