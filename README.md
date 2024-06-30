# Prject : Text-Classification

Text classification is a fundamental task in natural language processing (NLP) where the goal is to categorize text into predefined classes. 

In this project, we aim to build a text classification model to determine whether a given movie review is positive or negative.

The dataset we will be using is from the Stanford Large Movie Review Dataset, which contains 25,000 highly polar movie reviews for training and 25,000 for testing. 
Each review is labeled as either positive or negative, making it an ideal dataset for binary sentiment classification tasks.

For more information on this dataset, you can visit Stanford Large Movie Review Dataset.

## Goal:

Given a set of text movie reviews labeled as negative or positive, our objective is to create a model that can accurately predict the sentiment of new, unseen movie reviews.

## Steps:

- Perform Imports and Load the Dataset: We will start by importing the necessary libraries and loading the dataset into a pandas DataFrame.
- Data Preprocessing: This involves cleaning and preparing the text data for modeling.
- Feature Extraction: Converting text data into numerical features that can be used by machine learning algorithms.
- Model Training: Training a machine learning model on the training data.
- Model Evaluation: Evaluating the model's performance on the test data.
- Prediction: Using the trained model to predict the sentiment of new movie reviews.
