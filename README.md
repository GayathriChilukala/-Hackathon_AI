# AI Guardian for Content Integrity: Embodies Responsible AI

## Overview

The AI Guardian for Content Integrity is a Python project that embodies the principles of Responsible AI. This project focuses on the detection of fake news using Natural Language Processing (NLP) techniques. Rigorous Exploratory Data Analysis (EDA) is conducted to understand the dataset's structure, and a slight imbalance is addressed using a smoothing technique. The preprocessing steps involve punctuation removal, feature selection, lowercase conversion, whitespace tokenization, removal of short tokens, stopword removal, and lemmatization. The resulting clean text is utilized for vectorization.

## Step 1: Data Loading

### Load Text Data

The project begins with loading text data to understand the structure of the dataset.

## Step 2: Text Preprocessing

### Convert to Lowercase, Tokenize, and Remove Stop Words and Punctuation

The text data is processed by converting it to lowercase, tokenizing it, and removing stop words and punctuation.

### Calculate Basic Stats

Basic statistics, such as document lengths, word frequencies, and n-grams, are calculated to gain insights into the dataset.

## Step 3: Visualizations

### Word Clouds, Histograms, and Bar Charts

Visualizations such as word clouds, histograms, and bar charts are employed to provide intuitive insights into the dataset.

### Sentiment Analysis, NER, and Topic Modeling Visuals

Visualizations for sentiment analysis, Named Entity Recognition (NER), and topic modeling are included to enhance understanding.

## Step 4: Explore Relationships

### Investigate Feature Correlations

The project explores correlations among features to identify relationships within the dataset.

### Analyze Text Lengths

Text lengths are analyzed to understand the distribution of document lengths.

### Explore Word Embeddings

Word embeddings are examined to reveal relationships between words and their semantic meanings.

## Step 5: Word Clouds

### Word Clouds Generation

Two word clouds have been created for 'FAKE_NEWS' and 'REAL_NEWS' to visually represent the most frequent words in each category.

### Comparison of Frequency

The frequency of words in both fake and real news has been compared to gain insights into their distribution.

## Step 6: Data Splitting and Vectorization

### Data Splitting

The dataset has been split into training and test sets.

### Vectorization

Text data has been vectorized to prepare it for machine learning models.

## Step 7: Class Imbalance Resolution

### SMOTE

Synthetic Minority Over-sampling Technique (SMOTE) has been applied to oversample the minority class and address the class imbalance.

## Step 8: Machine Learning Models

### Random Forest Classifier

Trained and tested on the preprocessed data.

### Logistic Regression

Model trained and tested on the vectorized text data.

### Support Vector Classification

Implementation of SVC for fake news detection.

### Decision Tree Classifier

A decision tree model trained and tested on the preprocessed data.

## Step 9: Model Interpretability

### SHAP and LIME

SHAP values and LIME have been used for model interpretability.

## Transparency and Accountability

The AI Guardian adheres to principles of transparency and accountability. It integrates Explainable AI (XAI) techniques, specifically SHAP (SHapley Additive exPlanations) and LIME (Local Interpretable Model-agnostic Explanations), to provide users with clear insights into the decision-making process.





