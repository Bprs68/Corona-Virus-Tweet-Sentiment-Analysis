<h1 align='center'> Corona Virus Tweet Sentiment Analysis</h1>
<p align='center'>
  <img src="https://images.unsplash.com/photo-1584529847460-0e208a238cea?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=870&q=80" align="center" height="250" width="500">
</p>

## Introduction
<p>Social media has become an integral part of our lives and is used extensively for sharing our thoughts, ideas, and opinions. Analyzing the sentiment of social media messages can provide valuable insights into public perception, which can be useful for a variety of applications, such as marketing, customer service, and opinion mining.</p><br>
<p>Tweet sentiment analysis is a technique that involves using natural language processing (NLP) techniques to determine the sentiment expressed in a tweet. In this project, we explore the use of machine learning models for tweet sentiment analysis.</p>

## Project Summary
<p>The main objective of this tweet sentiment analysis project is to classify tweets as either positive or negative in sentiment using different machine learning models. The original dataset contained tweets with five different sentiment labels: Extremely positive, Positive, Extremely Negative, Negative, and Neutral. However, for this project, these sentiments were converted into just two categories: Positive and Negative.</p>

<p>In order to prepare the tweet data for use with machine learning models, a technique called vectorization was used. Vectorization is the process of converting text data into numerical form, so that it can be input into a machine learning model. In this project, the vectorization method used was term frequency-inverse document frequency (TFIDF).</p>

<p>Several machine learning models were used to classify tweets as either positive or negative, including Logistic Regression, Ridge Regression, KNN Classifier, Random Forest Classifier, XGBoost Classifier, Naive Bayes Classifier, SGD Classifier, and Support Vector Classifier. Each of these models has its own characteristics and assumptions, and may perform differently depending on the specifics of the data and the classification task.</p>

## Data Preparation
The original dataset used in this project contained 31,962 tweets with five different sentiment labels. To simplify the classification task, we converted these sentiments into just two categories: Positive and Negative. This allowed us to train machine learning models to predict whether a given tweet was positive or negative in sentiment.

The next step was to prepare the tweet data for use with machine learning models. Text data cannot be directly fed into a machine learning model, so we used a technique called vectorization to convert the text data into numerical form. In this project, we used the TFIDF vectorization method. TFIDF stands for term frequency-inverse document frequency and is a commonly used method for vectorizing text data. It converts a collection of documents into a matrix, where each row represents a document and each column represents a term. The values in the matrix are calculated based on the frequency of each term within a given document and across all documents in the collection.

After applying TFIDF vectorization, the tweet data was ready to be used with the machine learning models.

## Machine Learning Models
Several machine learning models were used to classify tweets as either positive or negative in sentiment. These models included Logistic Regression, Ridge Regression, KNN Classifier, Random Forest Classifier, XGBoost Classifier, Naive Bayes Classifier, SGD Classifier, and Support Vector Classifier.

Each of these models has its own characteristics and assumptions, and may perform differently depending on the specifics of the data and the classification task. For example, Logistic Regression is a linear model that works well with high-dimensional data, while Random Forest Classifier is an ensemble model that works well with complex data.

## Results
The accuracy scores of the different models varied widely, with some models performing better than others. The Logistic Regression, Ridge Regression, SGD Classifier, and Support Vector Classifier models showed the highest accuracy, with scores of 0.8378279883381924, 0.8298104956268222, 0.8217930029154519, and 0.836491739.
