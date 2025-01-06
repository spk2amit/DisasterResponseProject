# DisasterResponseProject
DisasterResponseProject
Project Overview
This project consists of three key components to be implemented:

1. ETL Pipeline
In the Python script process_data.py, you will create a data cleaning pipeline that performs the following steps:

Loads the messages and categories datasets
Merges the two datasets into one
Cleans the data by handling missing values, duplicates, and irrelevant information
Saves the cleaned data into an SQLite database
2. ML Pipeline
In the Python script train_classifier.py, you will develop a machine learning pipeline that:

Loads the cleaned data from the SQLite database
Splits the data into training and test sets
Builds a pipeline for text processing and machine learning
Trains and tunes a model using GridSearchCV for hyperparameter optimization
Evaluates the model on the test set and outputs the results
Exports the trained model as a pickle file for later use
3. Flask Web Application
We have provided a basic Flask web app structure. Feel free to extend it based on your knowledge of Flask, HTML, CSS, and JavaScript. For this component, you will need to:

Modify file paths for the database and model to match your setup
Add data visualizations using Plotly (one example is provided)
Customize the app with additional features based on your expertise
GitHub & Code Quality
Your project will also be evaluated based on the following criteria:

Proper use of Git and GitHub for version control
Clear and thorough documentation throughout the codebase
Clean, modular, and well-organized code for ease of understanding and maintenance
