# Hybrid AI Model for Explainable Text Classification

This project implements a hybrid AI-based text classification system that combines 
deep learning models with rule-based decision logic to deliver both high accuracy 
and explainable predictions.

## Project Overview
Traditional deep learning models often act as black boxes. This project addresses
that limitation by integrating neural networks with decision trees, enabling
transparent and human-readable decision-making.

## Key Features
- End-to-end NLP pipeline for unstructured text data
- Hybrid model using RNN/LSTM and Decision Trees
- Rule-first decision logic with machine learning fallback
- Explainable predictions using human-readable rules
- Designed for enterprise use cases such as IT support automation

## Datasets Used
- IT Ticket Dataset (Kaggle)
- 20 Newsgroups Dataset

## Technologies
- Python
- TensorFlow / Keras
- Scikit-learn
- Pandas, NumPy
- NLTK / spaCy
- Matplotlib, Seaborn

## Results Summary
- Hybrid model achieved higher accuracy than standalone decision trees
- Maintained explainability while handling complex text data
- Suitable for real-world enterprise applications

## How to Run
1. Clone the repository  
2. Install dependencies:
   ```bash
   pip install -r requirements.txt

