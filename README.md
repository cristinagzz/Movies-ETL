# Movies-ETL

In this module we use Python, Pandas and PostgreSQL to perform, Transform and load (ETL) procedure to build and clean the data.

## Overview
The goal of this project was to build and automated pipeline that receives new data, process it and create database tables with useful data.

## Activity
We use Jupyter Notebook and PostgresSQL to clean our data.
- Extract - From Wikipedia and Kaggle (2 csv datasets)
- Transform - Using Pandas and Regex we transform and clean our data. We make sure everything was clean in order to create our final dashboards.
- Load - We export our data into SQL and create our tables.

## Results

We created two tables, Movie table with 6,052 rows + rating table with 26,024,289 rows.

![movies_query](Movies-ETL/movies_query.png)

![ratings_query](Movies-ETL/ratings_query.png)