# Sentiment_Analysis
Sentiment analysis on Twitter and Reddit posts using a Support Vector Machine (SVM) classifier trained on a manually curated dataset with Positive, Negative, and Neutral labels.

**Description**
This repository contains a machine learning-based sentiment analysis model trained on manually curated Twitter and Reddit datasets. The project focuses on classifying social media posts into three sentiment categories: Positive, Negative, and Neutral using a Support Vector Machine (SVM) classifier.

Unlike generic sentiment datasets, this dataset was manually prepared by collecting and combining Twitter and Reddit posts, followed by extensive preprocessing and quality checks to improve the model's performance.

**Overview**
Social media platforms contain large volumes of user opinions that can be analyzed to understand public sentiment. This project builds a sentiment classification pipeline that:
Combines Twitter and Reddit datasets
Cleans and preprocesses textual data
Extracts meaningful text features
Trains an SVM classifier
Predicts sentiment as Positive, Negative, or Neutral
Evaluates model performance using standard classification metrics

**Dataset**
The dataset was manually created by merging sentiment-labeled data from Twitter and Reddit.
Sentiment Classes
Positive
Negative
Neutral
Data Preparation

**The dataset underwent several preprocessing steps, including:**
Removing duplicate records
Removing URLs
Removing mentions and hashtags
Removing punctuation
Converting text to lowercase
Removing stop words
Tokenization
Text normalization
Handling missing values
Manual quality verification

**Machine Learning Pipeline**
Dataset Collection
Data Cleaning
Text Preprocessing
Feature Extraction (TF-IDF)
Train/Test Split
Model Training using SVM
Model Evaluation
Sentiment Prediction

**Model**
Algorithm Used:
Support Vector Machine (SVM)
The SVM model was selected after comparing multiple machine learning algorithms due to its superior performance on the sentiment classification task.

**Features**
Twitter and Reddit sentiment classification
Three-class sentiment prediction
Manual dataset preparation
Text preprocessing pipeline
TF-IDF feature extraction
SVM classifier
Easy-to-use prediction pipeline

**Evaluation Metrics**
The model is evaluated using:
Accuracy
Precision
Recall
F1-Score
Confusion Matrix
