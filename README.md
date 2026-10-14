# Transformer-Based Sentiment Classification

A simple NLP project that uses a Transformer Encoder to classify text sentences as **positive or negative** based on their sentiment.

## Overview

This project explores how Transformer architectures can be applied to sentiment analysis. It uses a small dataset of positive and negative sentences related to courses, lectures, and learning experiences.

The model learns patterns in the text and predicts the sentiment of a given sentence.

## Features

- Text tokenization and padding
- Token embeddings and positional embeddings
- Multi-head self-attention
- Transformer Encoder architecture
- Binary sentiment classification
- Model training and evaluation
- Sentiment prediction for new sentences

## Technologies Used

- Python
- TensorFlow
- Keras
- NumPy

## How It Works

The project follows these steps:

1. **Dataset Creation:** Creates sample sentences labelled as positive or negative.
2. **Tokenization:** Converts words into numerical sequences using `TextVectorization`.
3. **Embedding:** Converts token IDs into vectors and adds positional information.
4. **Self-Attention:** Helps the model learn relationships between words in a sentence.
5. **Transformer Encoder:** Processes the embeddings using multi-head attention and a feed-forward network.
6. **Classification:** Uses a sigmoid output layer to predict the probability of positive sentiment.
7. **Evaluation:** Evaluates the model on the same small dataset used for training.
8. **Prediction:** Classifies new sentences using a threshold of 0.5.

## Model Architecture

The model consists of:

- Token and positional embedding layers
- Transformer Encoder with multi-head self-attention
- Global average pooling
- Dense layer with ReLU activation
- Dropout layer
- Sigmoid output layer for binary classification

## Installation

Install the required libraries:

```bash
pip install tensorflow numpy
```
## Example

**Input:**
- `this session is good`
- `i did not like this course`
- `teaching is excellent`
- `this course is confusing`

**Expected output categories:**
- Positive
- Negative


## Acknowledgement

This project is an educational experiment to understand Transformer-based NLP and sentiment classification.The project is intended primarily for learning and understanding the workflow rather than building a production-ready sentiment analysis system.

---

**Author:** Bela
