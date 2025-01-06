# DisasterResponseProject

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

Project Overview
* Objective: Create a Natural Language Processing (NLP) tool to categorise messages for disaster response.
* Dataset: Pre-labeled tweets and messages from real-world disasters, sourced from Figure Eight.

Key Features
1️⃣ ETL Pipeline
* Extracted, cleaned, and stored data in a SQLite database.
2️⃣ ML Pipeline
* Developed a classification model to categorise messages effectively.
* Included text processing, model training, and hyper-parameter tuning using GridSearchCV.
3️⃣ Web Application
* Designed an interactive web app to display dataset insights and test the model’s predictions.

Data Highlights
* Dataset Size: 30,000 disaster-related messages.
* Categories: 36 disaster response topics (e.g., medical aid, search & rescue).
* Privacy: Sensitive information removed for data security.

Custom Model Development Workflow
1. Data Preparation
    * Loaded and merged datasets (messages + categories).
    * Cleaned data and stored it in a SQLite database.
2. Pipeline Construction
    * Built a combined text processing and machine learning pipeline.
    * Split data into training and testing sets.
3. Model Optimisation
    * Fine-tuned the model using GridSearchCV for optimal performance.
    * Evaluated results for metrics like accuracy, precision, recall, and F1-score.

Final Outcome
This project demonstrates a complete data science workflow, including:
* Data Engineering: ETL pipeline for structured data storage.
* Machine Learning: Classification model development.
* Deployment: Web application for practical use.
