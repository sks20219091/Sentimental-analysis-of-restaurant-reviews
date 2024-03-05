# Sentiment Analysis of Restaurant Reviews

## Overview

This project focuses on sentiment analysis for restaurant reviews using Natural Language Processing (NLP) techniques. The primary goal is to analyze and classify restaurant reviews into positive or negative sentiments based on the text content.

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Preprocessing](#preprocessing)
- [Model Building](#model-building)
- [Evaluation](#evaluation)
- [Hyperparameter Tuning](#hyperparameter-tuning)
- [Dependencies](#dependencies)
- [Contributing](#contributing)


## Introduction

Sentiment analysis is a natural language processing task that involves determining the sentiment expressed in a piece of text. In this project, we apply sentiment analysis to restaurant reviews, classifying them as either positive or negative. The classification is performed using a machine learning model trained on a labeled dataset.

## Dataset

The dataset used in this project consists of restaurant reviews and their corresponding sentiments. The data is stored in a TSV (Tab-Separated Values) file, where each row represents a review and its sentiment. The dataset is preprocessed to clean and transform the text data for analysis.

## Preprocessing

The preprocessing steps include:
- Removing special characters
- Converting text to lowercase
- Tokenizing text into words
- Applying stemming using the Porter Stemmer
- Creating a corpus of cleaned reviews
- Transforming text data into a numerical format using CountVectorizer

## Model Building

A Random Forest Classifier is chosen as the machine learning model for sentiment analysis. The model is trained on the preprocessed data, and predictions are made on a test set.

## Evaluation

The model's performance is evaluated using metrics such as accuracy, precision, recall, and a confusion matrix. These metrics provide insights into how well the classifier is performing in classifying positive and negative reviews.

## Hyperparameter Tuning

The project explores hyperparameter tuning to optimize the Random Forest Classifier's performance. The best hyperparameters are determined to achieve the highest accuracy score.


## Dependencies
- numpy
- pandas
- scikit-learn
- nltk
- seaborn
- matplotlib


## Contributing
Contributions are welcome! If you have ideas for improvements, feel free to submit a pull request.
