# Detecting-Fraud-Occurances

Unveiling Fraud Detection Repository

## Introduction
Embark on a journey into the world of fraud detection with the comprehensive Fraud Detection repository. Within this repository lies a collection of SQL scripts and Jupyter notebooks that form the backbone of a sophisticated fraud detection system. This data analysis endeavor harmoniously combines SQL for querying data from a Postgres database and Python (Pandas) for data manipulation and analysis. Additionally, the project shines a spotlight on visualizations powered by hvPlot, enabling the identification of fraudulent activities.

## Project Architecture
Our repository structure aligns as follows:

1. all_tables_query.sql: Unveils a treasure trove of SQL queries instrumental in the project.
2. all_tables_schema.sql: Crafts the database schema that sets the stage for the analysis.
3. all_tables_seed.sql: Initiates the database with foundational data to initiate the journey.
4. challenge.ipynb: Immersive Jupyter notebook for the challenge segment, focusing on anomaly identification through standard deviation and interquartile range.
5. visual_data_analysis.ipynb: A Jupyter notebook that unleashes the power of visual data analysis onto transactions.
6. ERD_Diagram.png: A visually insightful Entity Relationship Diagram (ERD) showcasing the database schema.

## Setting Up and Usage
Prerequisites:
- Postgres database
- Python 3.x
- Jupyter notebook

Python Libraries to be Installed:
- pandas
- numpy
- hvPlot
- sqlalchemy
- psycopg2-binary

## Instructions:
1. Clone this repository onto your local machine.
2. Execute the all_tables_schema.sql script in your Postgres database to craft the schema.
3. Seed the database with initial data using the all_tables_seed.sql script.
4. Open the challenge.ipynb and visual_data_analysis.ipynb notebooks, making sure to replace the database connection string with your own Postgres database credentials.
5. Run through all notebook cells to unravel the analysis and visualize the outcomes.

## In Conclusion
This project epitomizes a harmonious fusion of SQL and Python for data analysis. It provides a foundational framework for a fraud detection system, poised for potential augmentation with advanced machine learning algorithms to elevate the accuracy of fraudulent activity detection. Your exploration of this repository marks a stepping stone towards a realm of data-driven vigilance against fraudulent endeavors.
