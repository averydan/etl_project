# ETL-Project---Group-2

We are a new coffee shop looking to set up vendor to supply our beans.

We want to source our coffee in an ethical way.

The data we are going to use data from CQI to learn more about the quality of the beans.  Coffee stats from ICO coffee data set that provides information about the countries that export coffee.  

https://www.kaggle.com/volpatto/coffee-quality-database-from-cqi

https://www.kaggle.com/yamaerenay/ico-coffee-dataset-worldwide?select=disappearance.csv

We will work to load these data sets so that they are clean and ready for analysis.

The Technical Report.docx explains the ETL process used.

Teh coffee_cleaned_data.ipynb is the combined python code to pull in the CSV (Extract) files,  Transform them for exploration and final database dataframe loading, and then using SQLAlchemy to Load them to our production Postgres database.

The Resources folder contain our raw data extracted from our source site.

The cleaned_data_files are the teams individual code development portions.