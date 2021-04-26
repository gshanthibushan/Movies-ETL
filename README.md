# Movies-ETL_Analysis
Learn ETL to Collect, Import, and Process Data

## Overview of the analysis:
The purpose of this analysis to gather data from both Wikipedia and Kaggle, combine them, and save them into a SQL database so that the hackathon participants have a nice, clean dataset to use. To do this, I have to follow the ETL process: extract the Wikipedia and Kaggle data from their respective files, transform the datasets by cleaning them up and joining them together, and load the cleaned dataset into a SQL database.. 

 During the analysis following were learned and applied in the Movies-ETL_Analysis:
  * Create an ETL pipeline from raw data to a SQL database.
  * Extract data from disparate sources using Python.
  * Clean and transform data using Pandas.
  * Use regular expressions to parse data and to transform text into numbers.
  * Load data with PostgreSQL.

## Source Data Files:

Python PostgreSQL CSV Files:
ratings.csv
movies_metadata.csv

JSON Files:
wikipedia-movies.json

## Results:

1. Write an ETL Function to Read Three Data Files 
  * ETL_function_test.ipynb
  * ![image](https://user-images.githubusercontent.com/79486450/116017637-3098b800-a60e-11eb-99c6-b860b674d5ea.png)
  * ![image](https://user-images.githubusercontent.com/79486450/116017666-3f7f6a80-a60e-11eb-99e8-77acd47efdb1.png)
  * ![image](https://user-images.githubusercontent.com/79486450/116017679-473f0f00-a60e-11eb-951f-d875fa5b9a13.png)

2. Extract and Transform the Wikipedia Data
  * ETL_clean_wiki_movies.ipynb
  * ![image](https://user-images.githubusercontent.com/79486450/116017753-79e90780-a60e-11eb-9b5e-1f075ef75019.png)
  * ![image](https://user-images.githubusercontent.com/79486450/116017775-8b321400-a60e-11eb-9e3c-50f40f5d3d75.png)

3. Extract and Transform the Kaggle Data
  * ETL_clean_kaggle_data.ipynb
  * ![image](https://user-images.githubusercontent.com/79486450/116017880-c59bb100-a60e-11eb-9207-2a827d265a12.png)
  * ![image](https://user-images.githubusercontent.com/79486450/116017913-d64c2700-a60e-11eb-8509-2ec2d4c0a0d2.png)
  * ![image](https://user-images.githubusercontent.com/79486450/116017940-e82dca00-a60e-11eb-8666-f9c218a557c8.png)

4. Create the Movie Database
  * ETL_create_database.ipynb
  * ![image](https://user-images.githubusercontent.com/79486450/116018362-e57fa480-a60f-11eb-9d4a-0b4b671f40b2.png)
  * ![image](https://user-images.githubusercontent.com/79486450/116018236-9d608200-a60f-11eb-89cc-6aa12428de7c.png)


