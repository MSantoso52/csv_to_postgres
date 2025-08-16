# csv_to_postgres
# *Overview*
Project repo to demonstrate Data Ingestion using Python, CSV file as Data Source and PostgreSQL as database. Data ingestion using Jupyter Notebook with pandas library to process it. Using small data CSV file because the purpose of this project to demonstrate Data Ingestion in simplest way that actually will work also with Big Data.
# *Prerequisites*
To follow along this learning we need to make it available on system, below requirements:
```bash
pip install jupyter-notebook
```
```Jupyter Notebook
pip install pandas, psycopg2
```
# *Project Flow*
Data ingestion from CSV to postgreSQL:
1. Import necessary python library -- pandas, sqlachemy, psycopg2
   ```Jupyter Notebook
   import pandas as pd
   from sqlalchemy import create_engine
   import psycopg2 
   ```
3. [E]xtract CSV to pandas data frame
4. [T]transform pandas -- remove unnecessary string & convert object to numeric data type
5. [L]oad pandas to postgreSQL
