# 7120CEM-NLP-Coursework 1

# ClickBait Spoiling - Spoiler Classification using LSTM 

This repository contains code and resources for a spoiler classification model based on Long Short-Term Memory (LSTM) neural networks. The model is designed to classify text and identify potential spoilers in textual content.

## Overview
- The LSTM model is trained to predict whether a given text contains spoilers or not.
- In this project I employed pre-trained GloVe word embeddings. GloVe embeddings provide vector representations for words that capture their meaning and 
  relationships in a continuous vector space. These embeddings were used as the input features for the LSTM model.
- It can be useful for applications like spoiler detection in user-generated reviews, comments, or social media posts.

## Requirements
- Python (>= 3.6)
- TensorFlow (>= 2.0)
- Numpy
- Pandas
- scikit-learn
- Jupyter Notebook

## Dataset
- This dataset contains the clickbait posts and manually cleaned versions of the linked documents, and extracted spoilers for each clickbait post.
  Additionally, the spoilers are categorized into three types: short phrase spoilers, longer passage spoilers, and multiple non-consecutive pieces of text.
- I have provided the dataset for training and validating the model.
- The dataset comes with predefined train/validation/test splits:
- [3,200 posts for training] (training.jsonl)
- [800 posts for validation] (validation.jsonl).

