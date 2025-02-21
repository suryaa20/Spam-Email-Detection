# Spam-Email-Detection
It classifies email as spam and not spam using ml model.
# Spam Email Detection

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![License](https://img.shields.io/badge/License-MIT-green)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Spam%20Detection-orange)

This repository contains a machine learning model for detecting spam emails. The goal is to classify emails as either "spam" or "ham" (not spam) using natural language processing (NLP) techniques and machine learning algorithms.

---


## Overview

Spam emails are a significant problem in today's digital world. This project aims to build a robust spam detection system using machine learning. The model is trained on a labeled dataset of emails and uses NLP techniques to preprocess the text data before classification.

---

## Features

- **Text Preprocessing**: Tokenization, stopword removal, stemming/lemmatization.
- **Feature Extraction**: TF-IDF, Bag of Words (BoW).
- **Machine Learning Models**: Logistic Regression, Naive Bayes, Random Forest, etc.
- **Evaluation Metrics**: Accuracy, Precision, Recall, F1-Score.

---


Dataset structure:
- `spam/`: Directory containing spam emails.
- `ham/`: Directory containing non-spam emails.

---

## Installation

To set up the project locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/suryaa20/Spam-Email-Detection
   cd Spam-Email-Detection
