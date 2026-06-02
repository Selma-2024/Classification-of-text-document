# Text Document Classification using Machine Learning

## Overview
This project implements a Text Document Classification system using Machine Learning. The model classifies input text into predefined categories by training on a labeled dataset.

The project uses:
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

## Features
- Loads and processes text data from a CSV file.
- Converts text into numerical features using CountVectorizer.
- Trains a Multinomial Naive Bayes classifier.
- Evaluates model performance using accuracy and confusion matrix.
- Predicts the category of custom user-entered text.

## Dataset
The dataset is stored in:
df_file.csv

Expected columns:
- `text` – document/content text
- `label` – category of the document

Example categories:
- Technology
- Entertainment
- Sports
- Politics

## Project Workflow

1. Load dataset
2. Preprocess text data
3. Split data into training and testing sets
4. Convert text into feature vectors using CountVectorizer
5. Train a Multinomial Naive Bayes model
6. Evaluate model accuracy
7. Predict categories for new text inputs

