# ETL Movie Ratings

## About the Project

This project was completed using SQL, SQLAlchemy, Postgres, and Python. The test dataset is a freely available dataset from https://github.com/prust/wikipedia-movie-data

## Installation

Clone the git repo from
https://github.com/roeggealissa/Movies_ETL.git

Enter your postgres password in config.py

db_password = 'YOUR PASSWORD HERE'

## Usage

This is a basic demonstration of utilizing SQL and Python to extract, transform, and load data, as well as data quality assurance. The data used in this is focused on movies however the concept can be applied to situations where ETL is applicable. The dataset used in the test case contains a large amount of natural language so regex is used to standardize the data

[](https://github.com/roeggealissa/Movies_ETL/blob/a7b7ea0b779f55e58beb4df1a39f332f598d201f/ETL_regex.png)

Above is an example of the regex used to clean up the column "release date". The regex used will depend on the specific files that are to extracted, transformed, and loaded. Each ETL_clean_().ipynb can be used as a basis to understand what sort of data should undergo a transformation and what data can be left as is.

## Roadmap

* Extract data to ipython notebook
* Validate data
  * Apply regex to columns with strings
* Create database with SQLAlchemy 
* Upload database to Postgres
  * Check database in Postgres


## Contact

Alissa Roegge - roeggealissa@gmail.com

https://github.com/roeggealissa/Movies_ETL



