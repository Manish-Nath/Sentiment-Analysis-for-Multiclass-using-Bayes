# Sentiment-Analysis-for-Multiclass-using-Bayes

Introduction
This project focuses on sentiment analysis using a Naive Bayes approach. The dataset used for training and testing the model is loaded from a CSV file (test.csv). The goal is to predict sentiment labels for given text data, categorizing them as 'positive,' 'negative,' or 'neutral.'

Requirements
Ensure you have the required libraries installed before running the code. You can install them using the following:

Load the dataset from a CSV file (test.csv).
Select relevant columns ('text' and 'sentiment').
Clean the text data by converting to lowercase and removing punctuation.
Shuffle the data for randomness.
Exploratory Data Analysis:

Print a few examples of each sentiment class for exploration.
Data Splitting:

Split the data into training and testing sets.
Bag of Words (BoW) Creation:

Create Bag of Words representations for positive, negative, and neutral sentiments.
Calculate the term frequency for each word.
Training the Model:

Train a Naive Bayes model using the training dataset.
Prediction and Evaluation:

Predict sentiment labels for the testing dataset.
Evaluate the model's performance using recall for each sentiment class.
Results and Analysis:
#Recall for Positive Sentiment: 0.5842696629213483                                                                                                                                                              .
#Recall for Negative Sentiment: 0.44981412639405205                                                                                                                                                              .
#Recall for Neutral Sentiment: 0.5642201834862385


Print the number of positive instances in the testing set.
Calculate the number of correctly detected positive sentiments.
Display recall values for positive, negative, and neutral sentiments.
How to Run
Ensure you have the required libraries installed (Pandas, NumPy).
Download the dataset file (test.csv) and place it in the same directory as the script.
Execute the script in a Python environment.
