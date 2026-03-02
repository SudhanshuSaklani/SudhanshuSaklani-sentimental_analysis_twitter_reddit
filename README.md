# **Twitter & Reddit Sentiment Analysis**

Sentiment Analysis is the process of detecting emotions or opinions expressed in text (e.g., positive, negative or neutral) using Natural Language Processing (NLP) and machine learning techniques.
This repository provides a complete pipeline to analyze sentiment from Twitter and Reddit data, including data preprocessing, model training, prediction and a simple web interface to test the model.

## **Project Overview**

This project enables you to:

Use sample Twitter and Reddit text data

Preprocess and clean raw text data

Train an NLP model to classify sentiment

Save and load trained models for real-time prediction

Use a simple web interface (Flask app) to classify new pieces of text

The goal is to build an end-to-end system that can categorize social media text into positive, negative, or neutral sentiment — helpful for market analysis, public opinion monitoring, brand reputation, etc.

## **Features**

✔ Preprocessing and cleaning of social text

✔ TF-IDF vectorizer for converting text to numerical features

✔ Trained classifier to predict sentiment

✔ Serialization of models (.pkl, .joblib)

✔ Flask app for serving predictions through a simple UI

✔ Jupyter Notebook with exploratory analysis

## **Repository Structure**

https://github.com/SudhanshuSaklani/SudhanshuSaklani-sentimental_analysis_twitter_reddit/blob/8d5063ba6806edfb8b5bea55231a2138c2bb18c9/Screenshot%202026-03-02%20215232.png

## **How It Works**

**Text Data Input**
Tweet or Reddit content is read from CSV or via input in the app.

**Preprocessing**
Clean text by removing noise (hashtags, URLs, punctuation, etc.).

**Feature Extraction**
Convert cleaned text into numerical features using TF-IDF.

**Model Training**
Train sentiment classifier to learn patterns in text.

**Prediction & Output**
Use the trained model to predict whether input text is positive, negative, or neutral.
