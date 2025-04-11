# 🧠 Language Modeling with N-Gram and Neural Architectures

## 📌 Project Overview

This project explores traditional and neural language models to evaluate the quality of natural language generation using **n-gram models**, **neural networks**, and **LSTM-based architectures**. The goal was to build, compare, and improve various models based on **validation perplexity**, a common metric for language models.

## 🎯 Objectives

- Implement and evaluate Unigram, Bigram, and Trigram (with backoff) models.
- Develop a neural n-gram model using PyTorch for improved context modeling.
- Build and optimize an LSTM-based language model with regularization and scheduling techniques.
- Analyze performance improvements using validation perplexity as the key metric.

## 📈 Key Results

| Model                      | Validation Perplexity |
|---------------------------|------------------------|
| Unigram Model             | (sample output only)   |
| Bigram Model              | 635.63                 |
| Trigram Backoff Model     | 310.73                 |
| Neural Trigram Model      | 240.38                 |
| LSTM Model (baseline)     | ~166                   |
| **Improved LSTM Model**   | **115.44**             |

## 🧪 Technologies Used

- Python
- NumPy, PyTorch
- NLTK, Pandas
- Jupyter Notebook

## 🧪 Enhancements Implemented

- Gradient Clipping
- Weight Decay
- Activation Regularization
- Learning Rate Scheduling
- Increased Sequence Length

## 📚 Learning Outcomes

- Gained deep understanding of traditional and neural language modeling techniques.
- Improved LSTM performance by experimenting with regularization, optimization, and architectural modifications.
- Applied perplexity as a robust metric for evaluating generative models.

## 📂 Files

- `proj_1.ipynb`: Python notebook implementation.
- `report.pdf`: Summary report with analysis and results.
- `unigram_demonstration_predictions.npy`: Sample predictions from unigram model.
- `bigram_predictions.npy`: Bigram model predictions.
- `trigram_backoff_predictions.npy`: Trigram with backoff predictions.
- `neural_trigram_predictions.npy`: Neural trigram model predictions.
- `lstm_predictions.npy`: Improved LSTM model predictions.

## 👨‍💻 Author

Aditya Ketanbhai Shah  
Project for CS 678: Advanced Natural Language Processing (Fall 2024)  
George Mason University
