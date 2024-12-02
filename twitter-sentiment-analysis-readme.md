# Twitter Sentiment Analysis Project

## Project Overview
This project implements a machine learning model for sentiment analysis on Twitter data, using logistic regression to classify tweets as positive or negative.

## Project Steps

### 1. Data Acquisition
- Used Kaggle library to extract dataset
- Dataset was large and stored in .zip format
- Extracted and loaded the data

### 2. Data Preprocessing
- Imported necessary libraries:
  - Kaggle
  - Pandas
  - StopWords
  - Stemming tools

- Loaded CSV data into a Pandas DataFrame
  - Initial DataFrame size: 1.6 million rows
  - Manually created column names due to reading issues

### 3. Data Cleaning and Preparation
- Checked DataFrame shape
- Identified and handled missing values
- Analyzed data distribution
- Converted target label "4" values to "1" for convenience

### 4. Text Processing
- Performed stemming to reduce words to their root form
- Created a new 'stemmed' column with processed text
- Removed stopwords to eliminate non-contextual words

### 5. Feature Extraction
- Used vectorization to convert textual data to numerical format
- Prepared data for machine learning model

### 6. Model Training
- Split data into training and testing sets
- Used Logistic Regression as the classification algorithm
- Trained the model on the preprocessed data
- Evaluated model accuracy

### 7. Model Persistence
- Saved trained model using Pickle
- Saved with `.sav` extension for future use
- Implemented functionality to predict sentiment for individual tweets

## Requirements
- Python 3.x
- Pandas
- Scikit-learn
- NLTK (for stopwords and stemming)
- Pickle

## How to Run
1. Install required libraries
2. Load the dataset
3. Run the preprocessing script
4. Train the model
5. Use the saved model for predictions

## Model Performance
- Accuracy: [Insert your model's accuracy percentage]
- Precision: [If available]
- Recall: [If available]

## Future Improvements
- Experiment with other machine learning algorithms
- Try advanced text preprocessing techniques
- Implement more sophisticated feature extraction methods
