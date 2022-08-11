# Movies-ETL
Using the Extract, Transform, Load (ETL) process to create data pipelines.
 
## Background
The client is interested in developing an algorithm to predict which low budget movies being relesae will become popular so they can buy the movie rights at a lower price.
 
### Purpose
 
The purpose of this analysis is to to create an automated pipeline that takes in new data, performs the appropriate transformations, and loads the data into existing tables. You’ll need to refactor the code from this module to create one function that takes in the three files—Wikipedia data, Kaggle metadata, and the MovieLens rating data—and performs the ETL process by adding the data to a PostgreSQL database.
 
<br/>
 
## Resources
 
Data source:
- (1)movies_metadata.csv, (2)ratings.csv, (3)wikipedia_movies.json
 
Software:
- PostgreSQL 14.0, PgAdmin 4, Python 3.7.6, Visual Studio Code 1.68.1
 
<br/>
 
## Overview of Analysis
 
Deliverable 1: Using Python, Pandas, the ETL process, and code refactoring, we wrote a function that reads in the three data files and creates three separate DataFrames, as shown in Fig 1.1

Deliverable 2: Using your knowledge of Python, Pandas, the ETL process, and code refactoring - we extracted and transformed the Wikipedia data and then merged it with the Kaggle metadata. While extracting the IMDb IDs using a regular expression string and dropping duplicates, use a try-except block to catch errors. (Fig 1.2)

Deliverable 3: Using your knowledge of Python, Pandas, the ETL process, and code refactoring - extract and transform the Kaggle metadata and MovieLens rating data, then convert the transformed data into separate DataFrames. Then, you’ll merge the Kaggle metadata DataFrame with the Wikipedia movies DataFrame to create the movies_df DataFrame. Finally, you’ll merge the MovieLens rating data DataFrame with the movies_df DataFrame to create the movies_with_ratings_df. (Fig 1.3)

Deliverable 4: Create the Movie Database Use your knowledge of Python, Pandas, the ETL process, code refactoring, and PostgreSQL to add the movies_df DataFrame and MovieLens rating CSV data to a SQL database. (Fig 1.4)
 
 
<br/>
 
## Summary
 
- In this project we were able to use Python, Pandas, the ETL process, code refactoring, and PostgreSQL to create an algorithm that extracted, and transformed the data into DataFrames and then loaded them into a SQL database.
 
<br/>
 
## References
 
[Markdown](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
 
[QuickDBD](https://app.quickdatabasediagrams.com/#/)
 
[Matplotlib gallery](https://matplotlib.org/stable/gallery/index.html)
