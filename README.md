# Big_Data
Challenge Summary
Instructions



1.) Make schemata to create tables in our RDS database.

2.) Create a Google Colab Notebook and extract any dataset from the list of review datasets , one into each notebook.

3.) For the notebook, complete the following:

Extract dataset from the S3 bucket and load into a DataFrame.
Count the number of records (rows) in the dataset.
Transform the dataset to fit the tables in the schema file.
Load the DataFrames that correspond to tables into an RDS instance.
4.) Use either PySpark to analyze and determine if the Vine reviews are biased.
I chose PySpark to create a new notebook and perform an analysis.
5) Access to Colab is in the OfficeProductsChallenge.ipynb



First, looking at more data or larger datasets may always bring doubt and allow for discussion or disagreemet in findings. It comes down to your gut and informed observation. While looking at the top 20 rows of each tokenized dataset, there doesn't seem to be any correlation in the Vine Reviews. There isn't a pattern in words or tokens. I can then determine the vine reviews have zero biaz.

