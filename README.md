# spark_DA
Note: first four steps are common for environment setup using Pyspark in Google Colab.

1.	Download and install openjdk-8
2.	Download and setup apache spark from url : http://archive.apache.org/dist/spark/spark-3.1.1/spark-3.1.1-bin-hadoop3.2.tgz
3.	Set environment variables for Java and Spark
4.	Create Spark Session to perform different operations in Pyspark
5.	Upload the dataset “assignment2_dataset.csv” file to your google drive and Load in the application. Display the top 10 rows from the dataset.
6.	Display the count of total records in the dataset
7.	Now, we have to filter records based on Area (sq km) column. First, display the count of records where area is greater than “2381750” and below the count display all records where area is greater than the value specified.
8.	Rename the existing column “Area(sq km)” in the dataset to new name “Area” and then display the data to confirm column is renamed
9.	Fetch the top 200 rows from dataset and sort by “Country” descending e.g. countries starting from letter “z” should be on top and so on
10.	Select only three columns “Country”, “Area” and “Population” but all the rows where Population is greater than 29928987. If you display the count of the rows matching this criteria that will be a plus point.
11.	Sort the records fetched in point no 10(applying the mentioned filters and only displaying the three columns specified) by Population descending i.e. display the record on top where population is the highest.
12.	Fetch all the columns for the data where Country is either “Saudi Arabia” or “Pakistan” 
