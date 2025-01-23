# Sarcasm Detection Model (SDM)
The Sarcasm Detection Model (SDM) is a binary classification model designed to identify sarcastic content in social media datasets. It leverages the BERT-base (uncased) architecture, a pretrained large language model (LLM), fine-tuned on the Reddit Dataset from Kaggle.

# Key Features
BERT-based Architecture: Built on the robust BERT-base (uncased) model for contextual natural language understanding.
Binary Classification: Classifies text as sarcastic or non-sarcastic.
Reddit Dataset: Trained on a high-quality Reddit dataset (source: Kaggle).
Data Pipeline Integration: Designed to filter sarcastic content in real-time, enhancing data quality for downstream applications.
Project Overview
Objective
To develop a reliable and efficient model that detects sarcasm, improving the quality of processed data by filtering out sarcastic content.

# Dataset
The model was trained on the Reddit Dataset from Kaggle, which includes a wide variety of sarcastic and non-sarcastic comments sourced from Reddit.

# Model Architecture
The Sarcasm Detection Model is based on:

BERT-base (uncased): A transformer model pretrained on a large corpus of text, enabling contextual understanding.
Fine-tuning: The model was fine-tuned on the Reddit dataset, optimizing it for sarcasm detection tasks.
# Deployment
Once deployed, SDM can:

Integrate with data streaming pipelines to filter sarcastic content in real-time.
Enhance downstream processes such as sentiment analysis, recommendation systems, or content moderation.


Dataset Source: https://www.kaggle.com/datasets/pavellexyr/the-reddit-dataset-dataset/data
