# crowdfundingETL_CE
Project 2
Project Title: ETL Mini Project - Crowdfunding Data Pipeline

In this ETL (Extract, Transform, Load) mini project, I collaborated with a partner to showcase my data engineering skills using Python, Pandas, and Postgres. Our goal was to build a robust ETL pipeline to extract, transform, and load data from Excel files into a relational database. This project allowed me to demonstrate my ability to work effectively in a team, communicate clearly, and deliver a functional data solution within a defined timeline.

Project Overview:

Our project was centered around crowdfunding data, and we followed a systematic approach to achieve the desired outcomes.

1. Data Extraction and Transformation:
We started by extracting data from two Excel files, "crowdfunding.xlsx" and "contacts.xlsx." These files contained unstructured data that needed careful transformation to create structured dataframes.

Category and Subcategory DataFrames: We created a "category" dataframe with unique identifiers ("category_id") and corresponding category titles. Similarly, we generated a "subcategory" dataframe with unique subcategory identifiers ("subcategory_id") and their respective titles. These dataframes were exported as "category.csv" and "subcategory.csv."

Campaign DataFrame: We created a comprehensive "campaign" dataframe, which included essential columns such as "cf_id," "company_name," "goal," "pledged," "outcome," and more. We performed data type conversions and renaming to ensure data accuracy. This dataframe was exported as "campaign.csv."

Contacts DataFrame: For the "contacts" dataframe, we chose an approach either using Python dictionary methods or regular expressions to extract "contact_id," "first_name," "last_name," and "email" columns. We aimed to create a clean and well-structured "contacts" dataframe, which was then exported as "contacts.csv."

2. Database Creation and Data Loading:
We designed the database schema based on our understanding of the data relationships, primary keys, foreign keys, and constraints. This schema was documented in a SQL file named "crowdfunding_db_schema.sql."

Database Creation: We created a new Postgres database called "crowdfunding_db" and utilized the schema file to generate tables in the correct order to ensure data integrity.

Data Import: After successfully creating the tables, we imported data from the CSV files into their respective SQL tables. Each import was thoroughly verified by running SELECT statements to ensure data accuracy and completeness.

Project Outcome:

The project showcased my expertise in ETL processes, data transformation, and database management using Python and Pandas.
Effective collaboration and communication with my partner were crucial to completing the project on time.
I demonstrated the ability to work with unstructured data, perform data cleaning, and create structured datasets for analysis.
The creation of a relational database and successful data loading highlighted my proficiency in database design and management.
This ETL mini project not only provided valuable hands-on experience but also allowed me to present a practical example of my data engineering skills. It serves as a testament to my ability to handle data-related tasks efficiently and effectively, making it a valuable addition to my portfolio for potential employers to assess.




