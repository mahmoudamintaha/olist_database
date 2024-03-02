# Olist Database Modelling

## Overview
This project focuses on modeling the Olist database using MySQL. The Olist database consists of 9 CSV files:

- category_translation
- customers
- geolocation
- order_items
- order_payments
- order_reviews
- orders
- products
- sellers

These files were imported into MySQL, where data cleaning operations were performed. Duplicates were removed, and missing data was consolidated to prepare the tables for primary keys and foreign keys. The ultimate goal was to create a well-defined schema for the database.

## Key Steps
1. **Data Import:** The CSV files were imported into MySQL for further processing.
2. **Data Cleaning:** Duplicates were removed, and missing data was handled to ensure data integrity.
3. **Schema Definition:** Primary keys, foreign keys, and composite keys were defined to establish relationships between tables.
4. **Entity-Relationship Diagram (ERD):** Reverse engineering was used to generate an ERD using MySQL.

## Additional Resources
- **Presentation Slide Deck:** A presentation slide deck outlining the project's objectives, methodology, and results is available for reference.
- **Source Data:** The original CSV files used in this project are included for transparency and reproducibility.
- **Database SQL Script:** The SQL script used to create the resulting database schema is provided for those interested in conducting exploratory data analysis (EDA) using SQL.

## Future Steps
This project is part 1 of a three-part series. The next steps include:
- **Part 2: EDA with SQL:** Analyzing the database using SQL queries to gain insights into Olist's operations.
- **Part 3: Dashboard with Power BI:** Creating a dashboard using Power BI to visualize key metrics and trends.

## Repository Structure
- **Jupyter Notebook:** Contains the main code for data import, cleaning, schema definition, and ERD creation.
- **README.md:** This file, providing an overview of the project and instructions for use.
- **Requirements.txt:** Lists the required Python packages to run the Jupyter Notebook.

## Usage
To replicate the steps and view the results of this project:
1. Ensure MySQL is installed on your system.
2. Clone this repository to your local machine.
3. Install the required Python packages listed in `requirements.txt`.
4. Open and execute the Jupyter Notebook to follow along with the data modeling process.
