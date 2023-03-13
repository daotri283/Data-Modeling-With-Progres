# Summary: 
This project is used to import the data into database from json log files & song files


# sql_queries.py:
This file includes all the queries which be used in project

# create_tables.py: 
This python source code executes the queries for connect database, create the schema

# test.ipynb:
This notebook to validate the data structure 

# etl.py:
This file is responsible for reading json thence import the data into tables

# etl.inpynb: 
This notebook to develop the ETL process for each of your tables to load the whole datasets.

# data/log_data
This folder include all the log file json

# data/song_data
This folder include all the song file json

# Run the database schema: 
python3 create_tables.py

# Run the test: 
ipython -c "%run test.ipynb"

# Run the etl progress: 
python3 etl.py

# Run the sanity tests: 
ipython -c "%run elt.ipynb"
