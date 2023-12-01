# Crowdfunding_ETL
# **PROJECT-2**
![download]([https://github.com/Cameron762/Project-1-11/assets/72319764/7f8c363a-026a-429c-be56-127ed8535605](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQIfnfFy9lf0JxSrbs5wXt-ea2ESgiJ6mbLM_8bGwzh&s))

**PROJECT TITLE:**
The ETL (Extract, Transform and Load) of crowdfunding Data to create multiple data frames.

[PROJECT DESCRIPTION](#project-description)   
[CONTRIBUTORS](#contributors)  
[INSTALLATION](#installation)  
[DOCUMENTATION](#documentation)  
[DEVELOPMENT](#development)  
[FINDINGS](#findings)
[CONCLUSIONS](#conclusions)


**PROJECT DESCRIPTION**  
Using cowdfunding data, the purpose of this project was to showcase how to extract and transform into multiple dataframes 

*Research questions to ask:*
1. How to create a category and subcategory data frame
2. How to create a campaign data frame
3. How to create a contact data frame
4. How to create a crowdfunding database
   
**CONTRIBUTORS**
- Kelechi Joel Github Link: https://github.com/kcjoel
- David Cortez Github Link: https://github.com/dcortez03

  
**INSTALLATION** 
- Python 
- Code Editor (Visual code, jupyter etc)
- import pandas 
- from pathlib import Path
- import numpy 
- PgAdmin 4
- QuickDBD

**DOCUMENTATION**
- ERD

 


**DEVELOPMENT**  
The instructions for this mini project are divided into the following subsections:

1. Create the Category and Subcategory DataFrames:
    - The DataFrame contains a "category_id" column that has entries going sequentially from "cat1" to "catn", where n is the number of unique categories 
    - The DataFrame has a "category" column that contains only the category titles 
    - The category DataFrame is exported as category.csv 
3. Create the Campaign DataFrame:
    - The DataFrame contains a "subcategory_id" column that has entries going sequentially from "subcat1" to "subcatn", where n is the number of unique subcategories 
    - The DataFrame contains a "subcategory" column that contains only the subcategory titles 
    - The subcategory DataFrame is exported as subcategory.csv
4. Create the Contacts DataFrame: The DataFrame has the following columns: 
    - A "cf_id" column
    - A "contact_id" column
    - A "company_name" column
    - A "description" column
    - A "goal" column that is a float data type
    - A "pledged" column that is a float data type
    - An "outcome" column
    - A "backers_count" column
    - A "country" column
    - A "currency" column
    - A "launch_date" with the time formatted as "YYYY-MM-DD"
    - A "end_date" with the time formatted as "YYYY-MM-DD"
    - A "category_id" column that contains the unique identification numbers matching those in the "category_id" column of the category DataFrame
    - A "subcategory_id" column that contains the unique identification numbers matching those in the "subcategory_id" column of the subcategory DataFrame
    - The campaign DataFrame is exported as campaign.csv
5. Create the Crowdfunding Databa:
    - A database schema labeled, crowdfunding_db_schema.sql is created (5 points)
    - A crowdfunding_db is created using the crowdfunding_db_schema.sql file (5 points)
    - The database has the appropriate primary and foreign keys and relationships (5 points)
    - Each CSV file is imported into the appropriate table without errors (5 points)
    - The data from each table is displayed using a SELECT * statement

**FINDINGS**

**CONCLUSIONS**
