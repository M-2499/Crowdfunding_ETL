
# Crowdfunding ETL Project

## Overview

The Crowdfunding ETL project is a collaborative effort between partners to build an Extract, Transform, Load (ETL) pipeline using Python, Pandas, and either Python dictionary methods or regular expressions. This project involves extracting and transforming data from Excel files, creating CSV files, generating an Entity-Relationship Diagram (ERD), designing a table schema, and finally, uploading data into a Postgres database.

## Project Timeline

Since this is a one-week project, it's important to stay on track. Ensure that at least half of the project is completed before the third day of class.

## Collaboration and Communication

Although partners will divide the work, active collaboration and communication are crucial. Regular check-ins and support for each other's tasks will lead to a successful project completion.

## Files

Download the starter code and files to help you get started:

- [Project 2 ETL files](#) *(Link to be provided)*

## Before You Begin

1. **Repository Setup:**
   - Create a new repository named `Crowdfunding_ETL` for this project. Add your partner as a collaborator. Do not add this project to an existing repository.

2. **Clone the Repository:**
   - Clone the new repository to your computer.

3. **File Organization:**
   - Rename the `ETL_Mini_Project_starter_code.ipynb` file with the first name initial and last name of each member of the group (e.g., `ETL_Mini_Project_NRomanoff_JSmith.ipynb`).
   - Add this Jupyter notebook file and the `Resources` folder containing the `crowdfunding.xlsx` and the `contacts.xlsx` files to your repository.

4. **Push and Pull:**
   - Push the changes to GitHub.
   - Have your partner pull the changes, so both of you have the same notebook available on your computer.

## Instructions

The instructions for this mini project are divided into the following subsections:

1. **Create the Category and Subcategory DataFrames**
   - Extract and transform the `crowdfunding.xlsx` Excel data to create category and subcategory DataFrames.
   - Export as `category.csv` and `subcategory.csv`.

2. **Create the Campaign DataFrame**
   - Extract and transform the `crowdfunding.xlsx` Excel data to create a campaign DataFrame.
   - Export as `campaign.csv`.

3. **Create the Contacts DataFrame**
   - Choose between Python dictionary methods or regular expressions to extract and transform the data from `contacts.xlsx`.
   - Export as `contacts.csv`.

4. **Create the Crowdfunding Database**
   - Inspect the four CSV files and sketch an ERD of the tables.
   - Create a table schema for each CSV file and save it as `crowdfunding_db_schema.sql`.
   - Create a new Postgres database named `crowdfunding_db`.
   - Create tables and import corresponding CSV files.
   - Verify data integrity.

Please refer to the project documentation for detailed instructions for each subsection.

## Hints

- Utilize Pandas functions like `split()`, `astype()`, and `merge()` for efficient data handling.
- Refer to relevant Pandas documentation for detailed information on DataFrame operations.

---

Feel free to customize this template further or add any specific information that might be relevant for your project.
