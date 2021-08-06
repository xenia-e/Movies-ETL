# Movies-ETL
ETL practice

## Overview of the project 

 Create an automated pipeline that takes in new data, performs the appropriate transformations, and loads the data into existing tables. 
 
 
 ## Methods 
 Using ETL Principes create one function that takes in the three resource files — Wikipedia data (JSON), Kaggle metadata (CSV), and the MovieLens rating data (CSV) — and performs the ETL process by adding the data to a PostgreSQL database.

### Resources
Data source: 
- [Kaggle metadata](https://github.com/xenia-e/Movies-ETL/blob/main/Resources/movies_metadata.csv)
- [Wikipedia data](https://github.com/xenia-e/Movies-ETL/blob/main/Resources/wikipedia.movies.json) 
- MovieLens rating data is not included in repository


## Deliverables

- __Deliverable 1:__ [An ETL function to read three data files](https://github.com/xenia-e/Movies-ETL/blob/main/ETL_function_test.ipynb)
- __Deliverable 2:__ [Extract and Transform the Wikipedia Data](https://github.com/xenia-e/Movies-ETL/blob/main/ETL_clean_wiki_movies.ipynb)
- __Deliverable 3:__ [Extract and Transform the Kaggle Data](https://github.com/xenia-e/Movies-ETL/blob/main/ETL_clean_kaggle_data.ipynb)
- __Deliverable 4:__ [Create the Movie Database](https://github.com/xenia-e/Movies-ETL/blob/main/ETL_create_database.ipynb)

Two screenshots of exported SQL databases to confirm that the movies table has 6,052 rows and the rating table has 26,024,289 rows:
![Movies Database query and output](https://github.com/xenia-e/Movies-ETL/blob/main/Resources/movies_query.png) 

>Screenshot 1 - Movies Database query and output

![Ratings Database query and output](https://github.com/xenia-e/Movies-ETL/blob/main/Resources/ratings_query.png)

>Screenshot 2 - Rating Database query and output