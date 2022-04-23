# Movies-ETL
## Overview of the Movies-ETL
### Purpose of the analysis

The purpose of the anaylsis is to perform the ETL process for the movies data and add the data to a PostgreSQL database.

In the module, we imported the files from our computer by using extract_transform_load function, and then we use clean_movie function to rename all titles to an appropiate title. In the extract_transform_load function we also perform a "cleaning" process, we transforms the data by regex and functions, and then we add the data to the PostgreSQL database.

## Resources

- ETL_function_test.ipynb - Extract
- ETL_clean_wiki_movies.ipynb - Transform
- ETL_clean_kaggle_data.ipynb - Transform
- ETL_create_database.ipynb - Load

- Data Source: wikipedia-movies.json, movies_metadata.csv, ratings.csv(file size too large, unable to push to github)

- Application: Python 3.9.7, Jupyter Notebook 6.4.5, PostgreSQL 13.6

## Result

THe movies table has 6,052 rows.



The ratings table has 26,024,289 rows.