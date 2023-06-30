
# Data Pipeline: From CSV to MySQL Database

Project Summary: Building a Data Pipeline from World Bank CSV to MySQL Database

In this project, the goal was to create a data pipeline that extracts data from a CSV file downloaded from Kaggle which contained WorldBank data and loads it into a MySQL database. 




## Roadmap

- The project began by downloading a CSV file from the Kaggle, which served as the source of data. The CSV file contained various economic indicators, life expectancy data, literacy rates, export data and much more.

- To build the data pipeline, Python was employed to handle the extraction, transformation, and loading processes. Initially, the CSV file was read using Pandas's CSV module, allowing for easy access to the data within. 
- Data cleaning and transformation techniques were applied as necessary, such as handling missing values, converting data types, or restructuring the data to fit the desired MySQL database schema.
- Next, SQL queries were constructed to create the necessary tables in the MySQL database. The schema was designed based on the specific requirements of the project, accommodating the data from the CSV file.
- Using Python's MySQL connector, the transformed data was then loaded into the MySQL database. The connection to the database was established, and INSERT statements were executed to populate the tables with the extracted data from the CSV file.
- Throughout the project, error handling mechanisms were implemented to ensure data integrity and handle any potential issues during the data pipeline execution.
-  Logging and exception handling techniques were applied to provide visibility into the process and facilitate troubleshooting.
- Upon successful execution of the data pipeline, the CSV data was effectively transformed and loaded into the MySQL database, making it easily accessible for further analysis and querying. 
- The project showcased the utilization of Python and SQL code to build a robust and automated data pipeline, enabling the seamless flow of data from a World Bank CSV file to a MySQL database.

## Tech Stack

**Tools:** Python, SQL, MySQL Workbench, Pandas and MySQL Connector

**Skills**: Extract Transform Load (ETL) & Data Cleaning


## Environment Variables

To run this project, you will need to add the following environment variables to your .csv file

`Country Name`

`Region Code`

`Country Code`

`GDP, PPP (current international $)`

`Population, total`

`Population CGR 1960-2015`

`Internet users (per 100 people)`

`Popltn Largest City % of Urban Pop`

`2014 Life expectancy at birth, total (years)`

`Literacy rate, adult female (% of females ages 15 and above)`

`Exports of goods and services (% of GDP)`



