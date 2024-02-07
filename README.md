# Assessment_1 

# Prerequisits: Jyputer notebook, latest version of Apache-Spark, Pyspark libraries

In this project, you will understand a few basic pyspark operations on a dataframe.

Download a sample Json file is used containing the reviews and ratings of a few locations.

# Operations demonstrated in the code-file

1. Loading the file to the Jyputer notebook using the spark.read operation and convert it to a dataframe. CreateOrReplaceTempView() function creates a table name that can be used in spark-sql queries.

2. A spark-sql query to fetch all records from the dataframe that have the maximum ratings and show the number of records using the count() function

3. A spark-sql query to fetch all records from the dataframe that have the minimum ratings and show the number of records using the count() function

4. A spark-sql query to fetch the record with the longest review

5. Writing the dataframe to parquet file

6. Creating a simple graph to show the ratings against the number of ratings

