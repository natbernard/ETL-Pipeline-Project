# Sparkify database

## Purpose of the project
The purpose of this database is to assist the team at Sparkify to analyze music app data particularly songs and user activity to understand which songs their users are listening to. 
The database contains five tables, songplay, users, songs, artist and time tables. The database will optimize queries on user activity analysis. 

### How to run the python scripts
The python scripts can be run from the terminal or from a notebook. To run from a terminal, navigate to the location of the script using the 'cd' command then type python name_of_script.py to execute. To run from a notebook, import the python files to the notebook then run the cells.

### Files in the repository
The repository contains five files and one folder. The folder contains the data used to data from the Sparkify streaming app in json files. The other six files are python scripts and notebooks.

- create_tables.py drops and creates the tables.
- etl.ipynb contains code for the ETL process. It reads and processes files from the data folder, then loads it to the tables. 
- etl.py load all of the files in the data folder into the tables.
- sql_queries.py contains the sql queries.
- test.ipynb checks if data is uploaded to the tables in the database.

## Database schema
The database organizational structure for the Sparkify database is the star schema. It contains the songplay table as the fact tables and the rest as the dimension tables. The star schema is optimized for simpler queries and fast aggregations.

