# Movies-ETL

## Background:
Amazing Prime loves the dataset and wants to keep it updated on a daily basis. Britta needs your help to create an automated pipeline that takes in new data, performs the appropriate transformations, and loads the data into existing tables. You’ll need to refactor the code from this module to create one function that takes in the three files—Wikipedia data, Kaggle metadata, and the MovieLens rating data—and performs the ETL process by adding the data to a PostgreSQL database.

## Goals:
1. Deliverable 1: Write an ETL Function to Read Three Data Files
2. Deliverable 2: Extract and Transform the Wikipedia Data
3. Deliverable 3: Extract and Transform the Kaggle Data
4. Deliverable 4: Create the Movie Database

## Resources:
* Data Source: ETL Deliverable 1, ETL Deliverable 2 and ETL Deliverable 3
* Data Tools: PostgreSQL, pgAdmin
* Software: pgAdmin, Python, Visual Studio Code, Flask Version

## 1: Write an ETL Function to Read Three Data Files
### Goal: 
    Using your knowledge of Python, Pandas, the ETL process, and code refactoring, write a function that reads in the three data files and creates three separate DataFrames.

### Results:
<img width="806" alt="Screen Shot 2021-08-15 at 10 15 21 PM" src="https://user-images.githubusercontent.com/85847344/129514501-e74a5976-e360-408a-b43c-970d08b292f7.png">

<img width="514" alt="Screen Shot 2021-08-15 at 10 15 35 PM" src="https://user-images.githubusercontent.com/85847344/129514576-7e21221d-f606-4958-9133-41072bf534e3.png">

## 2: Extract and Transform the Wikipedia Data
### Goal: 
    Using your knowledge of Python, Pandas, the ETL process, and code refactoring, extract and transform the Wikipedia data so you can merge it with the Kaggle metadata. While extracting the IMDb IDs using a regular expression string and dropping duplicates, use a try-except block to catch errors.

### Results:
<img width="743" alt="Screen Shot 2021-08-15 at 10 20 35 PM" src="https://user-images.githubusercontent.com/85847344/129514784-6089b5d0-cd7e-49bc-b138-0e1e8478679b.png">

<img width="809" alt="Screen Shot 2021-08-15 at 10 20 43 PM" src="https://user-images.githubusercontent.com/85847344/129514785-bec67dc2-6a1a-491d-92db-46adbb4b6c07.png">

<img width="337" alt="Screen Shot 2021-08-15 at 10 20 49 PM" src="https://user-images.githubusercontent.com/85847344/129514787-95df66da-8ad3-4b60-b9ed-146f6c2cf383.png">

##  3: Extract and Transform the Kaggle Data
### Goal:
    Using your knowledge of Python, Pandas, the ETL process, and code refactoring, extract and transform the Kaggle metadata and MovieLens rating data, then convert the transformed data into separate DataFrames. Then, you’ll merge the Kaggle metadata DataFrame with the Wikipedia movies DataFrame to create the movies_df DataFrame. Finally, you’ll merge the MovieLens rating data DataFrame with the movies_df DataFrame to create the movies_with_ratings_df.

### Results:
<img width="818" alt="Screen Shot 2021-08-15 at 10 24 06 PM" src="https://user-images.githubusercontent.com/85847344/129515028-130bb3ef-2578-48c0-b908-ed9e7bf4adf0.png">

<img width="809" alt="Screen Shot 2021-08-15 at 10 24 14 PM" src="https://user-images.githubusercontent.com/85847344/129515050-dbaf252b-4eca-40a7-b7c4-7660662838e0.png">

<img width="820" alt="Screen Shot 2021-08-15 at 10 24 21 PM" src="https://user-images.githubusercontent.com/85847344/129515059-c67a6514-7fda-4dbe-ab6d-a609402ace5c.png">

## 4: Create the Movie Database
### Goal:
    Use your knowledge of Python, Pandas, the ETL process, code refactoring, and PostgreSQL to add the movies_df DataFrame and MovieLens rating CSV data to a SQL database.
    
### Results:




