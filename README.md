# Home_Sales

The objective of this challenge was to utilize SparkSQL in google colab to review home sales information. The data was stored in a csv and was imported using SparkFiles (from pyspark). Once the information was loaded into a dataframe, I began running queries and cached the results. The next step was to partition the data based off of when the homes were built, create a temporary table for the parquet data, and then run additional queries. Lastly, I uncached the data from the temporary tables.

This was a fun exercise since we tackled a variety of questions like 

-What is the "view" rating for the average price of a home, rounded to two decimal places, where the homes are greater than
or equal to $350,000?

-What is the average price of a home for each year built that have 3 bedrooms, 3 bathrooms, with two floors,
 and are greater than or equal to 2,000 square feet rounded to two decimal places?