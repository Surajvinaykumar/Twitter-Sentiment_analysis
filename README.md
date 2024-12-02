# Twitter Sentiment Analysis Project

## Project Overview
This project implements a machine learning model for sentiment analysis on Twitter data, using logistic regression to classify tweets as positive or negative.
Project Steps
### Data Acquisition

Used Kaggle library to extract dataset
Dataset was large and stored in .zip format
Extracted and loaded the data

### Data Preprocessing

Imported necessary libraries:

Kaggle
Pandas
StopWords
Stemming tools


Loaded CSV data into a Pandas DataFrame

Initial DataFrame size: 1.6 million rows
Manually created column names due to reading issues



### Data Cleaning and Preparation

Checked DataFrame shape
Identified and handled missing values
Analyzed data distribution
Converted target label "4" values to "1" for convenience

### Text Processing

Performed stemming to reduce words to their root form
Created a new 'stemmed' column with processed text
Removed stopwords to eliminate non-contextual words

### Feature Extraction

Used vectorization to convert textual data to numerical format
Prepared data for machine learning model

### Model Training

Split data into training and testing sets
Used Logistic Regression as the classification algorithm
Trained the model on the preprocessed data
Evaluated model accuracy

### Model Persistence

Saved trained model using Pickle
Saved with .sav extension for future use
Implemented functionality to predict sentiment for individual tweets

## Requirements

Python 3.x
Pandas
Scikit-learn
NLTK (for stopwords and stemming)
Pickle

## How to Run

Install required libraries
Load the dataset
Run the preprocessing script
Train the model
Use the saved model for predictions


## Future Improvements

Experiment with other machine learning algorithms
Try advanced text preprocessing techniques
Implement more sophisticated feature extraction methods
