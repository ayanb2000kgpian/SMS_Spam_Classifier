# SMS_Spam_Classifier
A SMS-Spam-Classifier based on NLP(Natural Language Processing).
# Introduction
This project is to design a sms-spam classifier with the help of Natural Language Processing. In this project I have used datasets available on kaggle in order to train our sms-spam classifier model.
# Implementation Details

## Data Cleaning:
1. Remove the nan columns from the data.
2. Remove the duplicated values from the data.

## Data Analysis:
1. Perform analysis on the number of spam and ham messages by plotting a pie chart.
2. Perform analysis on number of character,words,sentences for spam and ham mesaages.

## Data Preprocessing:
1. Convert all the text data to lower case characters.
2. Tokenize the text data.
3. Remove stopwords, punctuations from the tokenized data.
4. Apply stemming on the data to convert into root form.

## Model Building:
1. Vectorize the transformed data using tf-idf(Term Frequency-Inverse Document Frequency) algorithm.
2. Train model using different classifier algorithms like Gaussian Naive Bayes,Multinomial Naive Bayes,Bernoulli Naive Bayes and compare the accuracy and precision score.
3. Choose model based on higher accuracy and precision score.

Then I have deployed this sms-spam classifier on a local website.

Here is an example of our sms-spam classifier:
![app · Streamlit - Opera 28-06-2023 21_48_31](https://github.com/ayanb2000kgpian/SMS_Spam_Classifier/assets/138036625/dd5ed702-1914-4397-80c5-679e864017db)

![app · Streamlit - Opera 28-06-2023 21_50_14](https://github.com/ayanb2000kgpian/SMS_Spam_Classifier/assets/138036625/fe81211a-eb6a-483e-960d-186bb3b3fb06)

It can be seen that our sms-spam classifier works perfectly.

