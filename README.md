# Sentiment Analysis using LSTM

This repository contains a Python script for sentiment analysis using a Long Short-Term Memory (LSTM) neural network model. The script analyzes IMDb movie reviews to predict whether a review is positive or negative.

## Overview

Sentiment analysis is a natural language processing (NLP) task that involves determining the sentiment expressed in a piece of text. In this project, we use an LSTM-based neural network model, implemented using the Keras library, to perform sentiment analysis on IMDb movie reviews.

## Features

- Preprocesses text data by removing HTML tags, URLs, non-alphanumeric characters, stopwords, and lemmatizing words.
- Tokenizes and pads text sequences to prepare them for input to the LSTM model.
- Defines and trains an LSTM neural network model using Keras Sequential API.
- Evaluates the trained model on a test dataset to measure its accuracy.
- Provides functionality to predict sentiments for custom sentences.

## Requirements

- Python 3.x
- TensorFlow
- Keras
- pandas
- numpy
- scikit-learn
- NLTK

## Usage

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/sentiment-analysis-lstm.git

2.Navigate to the project directory:

cd sentiment-analysis-lstm

3.Install the required dependencies:

pip install -r requirements.txt

4.Run the Python script:

pip install -r requirements.txt

5.Follow the prompts to preprocess the IMDb dataset, train the LSTM model, and make predictions.


License
This project is licensed under the MIT License - see the LICENSE file for details.

Acknowledgments
This project is based on the concept of sentiment analysis using LSTM neural networks.
The IMDb dataset used in this project is publicly available.
