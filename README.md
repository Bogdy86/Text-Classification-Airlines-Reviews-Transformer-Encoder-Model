# Text-Classification-Airlines-Reviews-Transformer-Encoder-Model
## Overview
This project builds a Transformer-based text classification model to analyze airline reviews and predict sentiment.

## Project Goals
- Classify customer reviews automatically
- Understand sentiment patterns in airline feedback
- Explore Transformer encoder architecture for NLP tasks

- ## Dataset
Airline customer reviews dataset.

## Data Preprocessing
Text data was cleaned and normalized by removing punctuation, converting to lowercase, and tokenizing sentences, and padded to ensure uniform input length. The text was then encoded into numerical representations suitable for input into the Transformer model.

## Exploratory Data Analysis
The ratings and review text data were explored using bar charts, histograms, and other Python techniques to understand class distribution, review patterns, and potential data imbalance. Visual analysis of the text length distribution was also performed to determine an appropriate sequence length, helping guide padding and truncation choices for the Transformer model. The analysis helped decide how to preprocess the data and improve the model.

## Technologies Used
- Python
- PyTorch
- NLP preprocessing
- Transformer Encoder
- Jupyter Notebook

## Model Architecture
The model uses a Transformer encoder to capture contextual relationships between words and improve classification accuracy.

## Model Evaluation
Model performance was evaluated using standard classification metrics. A confusion matrix was used to assess prediction accuracy across sentiment classes and to identify misclassification patterns.

## Predicting New Reviews
A prediction function was implemented to classify new, unseen airline reviews. This allows the trained model to be used for real-time sentiment prediction on customer feedback.

## Results
The model learns patterns in customer feedback and predicts sentiment automatically.

## How to Run
Open the notebook:

TextClassification.ipynb
