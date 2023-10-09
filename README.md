# EmailSpamDetection-SpamBase

## Project Overview

This project is a machine learning-based email spam classifier that uses the [SpamBase dataset](https://archive.ics.uci.edu/ml/datasets/spambase) for training and testing. The goal of this project is to build a model that can classify emails as either "spam" or "not spam" based on various features such as word frequency, character frequency, and more.

## Features

- Data Collection: The project collects data from the SpamBase dataset, which contains labeled email data for spam and non-spam emails.

- Data Preprocessing: The dataset is preprocessed to handle missing values, outliers, and feature engineering.

- Model Selection: Different machine learning models are evaluated for their performance, including Logistic Regression, and Random Forest.

- Model Evaluation: The models are evaluated using metrics like accuracy, precision, recall, F1-score, and ROC-AUC to determine their effectiveness in classifying spam.

- Feature Selection: Relevant features that have the most impact on spam classification are identified and used to train the final model.

## Usage

1. Clone this repository to your local machine.
2. Run the Jupyter Notebook or Python script to train and evaluate the spam classifier.

## Results

- The project achieves an accuracy of 87 percent on the testing dataset.
- The model's precision, recall, and F1-score are 0.85, 0.95, and 0.90 respectively.

## Future Enhancements

- Explore more advanced machine learning models.
- Fine-tune hyperparameters for better performance.
- Deploy the classifier in a real email system.

