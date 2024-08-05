# Databases_Assignment7  

**Team Members :**  
Kunal Deshmukh (25PGAI0036),  
Krunal Name (25PGAI0134),  
Pranjal Grover (25PGAI0107),  
Pravin Patrike (25PGAI0008),  
Shikha Thakur (25PGAI0045)


# Performing ETL jobs on 'Titanic' dataset and train a Logistic Regression Model

This project aims to perform ETL (Extract, Transform, Load) jobs on 'Titanic' dataset sourced from Kaggle and train a Logistic Regression model for survival prediction. It extracts and transforms the data and then stores it in a SQLite database. It then integrates the ETL job with a simple ML pipeline to train and evaluate the model.

## Requirements

- Python 3.7+
- pandas
- scikit-learn
- SQLAlchemy

## Installation


Place the 'train.csv' file in the project directory. It can be downloaded from Kaggle.

Run the **dbms_assignment7_group6.py** script:
This script will:

Load the dataset.  
Fill missing values.  
Drop the 'Cabin' column.  
Extract titles from names.  
Create a 'FamilySize' feature.  
Transform the numerical and categorical features.  
Store the transformed data in a SQLite database.  
Load the transformed data from the database.  
Split the transformed data into training and testing sets.  
Train a Logistic Regression model.  
Evaluate the model's accuracy and print it.
