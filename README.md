# csv_to_postgres
# *Overview*
# *Prerequisites*
# *Project Flow*
Data ingestion from CSV to postgreSQL:
1. Import necessary python library -- pandas, sqlachemy, psycopg2
2. [E]xtract CSV to pandas data frame
3. [T]transform pandas -- remove unnecessary string & convert object to numeric data type
4. [L]oad pandas to postgreSQL
