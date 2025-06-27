# Email Spam Detector

This project builds a machine learning model to classify emails as either spam or not spam, automating the detection of unwanted messages in email systems.

## Project Overview

The system uses text preprocessing and logistic regression to distinguish between spam and legitimate (ham) emails. The dataset includes labeled email text samples.

## Dataset

- `email_spam_detector_dataset.csv`
- Contains email content and corresponding labels (`spam` or `ham`)

## Workflow

1. Data Cleaning and Preprocessing  
   - Removal of stop words, punctuation, and special characters  
   - Text normalization and vectorization using CountVectorizer or TF-IDF
