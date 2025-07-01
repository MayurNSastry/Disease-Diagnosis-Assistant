# Disease Diagnosis Assistant

## Overview
This project implements a disease diagnosis assistant designed to help predict potential diseases based on reported symptoms. It leverages machine learning techniques and extensive exploratory data analysis to understand symptom relationships and provide informed predictions.

## Project Structure
-   `data/`: Contains the dataset used for analysis.
-   `code/`: Python scripts/Jupyter notebooks
-   `report/`: A detailed report summarizing findings, methodologies, and conclusions.

## Features & Functionality
1. Exploratory Data Analysis (EDA):
Analyzes the co-occurrence and correlations between various symptoms to identify significant relationships.
Provides insights into symptom patterns that are indicative of specific diseases.
2. Symptom Prediction:
Predicts potential new symptoms based on a set of existing symptoms provided by the user.
3. Disease Diagnosis:
Utilizes supervised machine learning models to classify and predict the most probable disease(s) given a patient's symptoms.
4. Machine Learning Models:
Naive Bayes Classifier: A probabilistic machine learning model used for classification tasks, particularly effective with text or categorical data.
Random Forest Classifier: An ensemble learning method that builds multiple decision trees and merges them to get a more accurate and stable prediction.

## Technical Details & Methodology
The core of this assistant involves:
1. Data Preprocessing: Cleaning and preparing the symptom-disease dataset for analysis.
2. Exploratory Data Analysis:
Calculating and visualizing symptom co-occurrence matrices.
Determining correlation coefficients between symptoms to uncover underlying patterns.
3. Feature Engineering: Transforming raw symptom data into features suitable for machine learning models.
4. Model Training: Training Naive Bayes and Random Forest classifiers on the processed data.
5. Prediction Logic: Implementing a system to take user input (symptoms) and feed it into the trained models for diagnosis.

## Technologies Used
Python: The primary programming language for development.

## Libraries:
pandas and numpy for data manipulation and numerical operations.
matplotlib and seaborn for data visualization during EDA.
scikit-learn for implementing Naive Bayes and Random Forest classifiers, as well as for model evaluation.