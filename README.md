# DisasterResponseProject

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
