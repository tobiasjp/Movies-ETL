# Movies-ETL

## Overview

Amazing Prime is looking to create an automated pipeline that can take in new movie data, appropriately tranform the data into a readable and reliable format, and loads the data into an existing database.  Data was sourced from multiple online databases and will be cleaned to make the data useable.

## Resources

Data: 

- Wikipedia-movies.json (Sourced from Wikipedia)
- Movies_metadata.csv (Sources from Kaggle)
- ratings.csv (Sourced from MovieLens)

Software:
- Python
- PostgreSQL 14/ pgAdmin

## Analysis of the Data
 
 The raw data from the three listed sources requires a large amount of work to extract, tranform and load the data into a database.  Data sources such as ratings.csv contains over 26 million data points, which is not easy to read.  By creating two functions (clean_movie, best_movies), we are able to easily call the function to operate on multiple sets of data, filter out unnecessary data, redefine the types of data, merge columns with the same data, and produce multiple dataframes from the cleaned data we extract from multiple sources. This data is more readily accessible and readable and ready to be evaluated.  
