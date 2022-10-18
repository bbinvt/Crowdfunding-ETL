# Crowdfunding-ETL

### Purpose
The purpose of this project was to analyze crowdfunding data using ETL concepts. The raw files are provided in CSV formats. A jupyter notebook was used to extract and transform the data. QuickDB is used to build the relationships between the data tables. And finally, the data was loaded into a postgreSQL database and verified using pgAdmin.

### Resources
- The jupyter notebook used to extract and transform the data can be found here: ![Extract-Transform_final_code.ipynb](https://github.com/bbinvt/Crowdfunding-ETL/blob/1a34ae075b75606be52cbf48d7975aafabe23e2c/Extract-Transform_final_code.ipynb)
- The SQL file used to load the data can be found here: ![crowdfunding_db_schema.sql](https://github.com/bbinvt/Crowdfunding-ETL/blob/1a34ae075b75606be52cbf48d7975aafabe23e2c/crowdfunding_db_schema.sql)
- The transformed data file used in this project can be found here: ![backers.csv](https://github.com/bbinvt/Crowdfunding-ETL/blob/1a34ae075b75606be52cbf48d7975aafabe23e2c/backers.csv)*
- Below you can see the entity relationship diagram used in this project: ![crowdfunding_db_relationships](https://github.com/bbinvt/Crowdfunding-ETL/blob/1a34ae075b75606be52cbf48d7975aafabe23e2c/crowdfunding_db_relationships.png)


*Note: This file was the only one transformed in the jupyter notebook above, however the rest of the data tables referenced in the ERD above were extracted, trasformed, and loaded using similar methods in a separate jupyter notebook which can be found here: ![crowdfunding_etl.ipynb](https://github.com/bbinvt/Crowdfunding-ETL/blob/1a34ae075b75606be52cbf48d7975aafabe23e2c/crowdfunding_etl.ipynb)

- The output of our structured data looked like this: ![backers_pgAdmin.png](https://github.com/bbinvt/Crowdfunding-ETL/blob/b29cb52d7e30b57400e2d00a74930ffd3e312eb5/backers_pgAdmin.png)
