# Sentiment-Analysis-IMDB-Reviews
IMDB Movie Review Sentiment Analysis using LSTM
This project focuses on building a Sentiment Analysis model using LSTM (Long Short-Term Memory) networks to classify IMDB movie reviews as positive or negative. The model is built and trained in Google Colab, using TensorFlow and Keras, and the dataset is fetched directly from Kaggle.

📁 Dataset
Name: IMDB Dataset of 50K Movie Reviews

Source: Kaggle - lakshmi25npathi

Description: A balanced dataset containing 50,000 movie reviews from IMDB, labeled as positive or negative.

📌 Project Highlights
Downloaded the dataset using the Kaggle API in Google Colab.

Preprocessed and tokenized text data using Keras Tokenizer.

Converted text to sequences and padded them to a uniform length.

Built an LSTM neural network using TensorFlow's Keras API.

Achieved high accuracy after 5 training epochs.

Implemented a custom predictive function to classify new movie reviews.

🧠 Tech Stack
Python

Google Colab

Pandas & NumPy – Data handling

Keras & TensorFlow – Deep learning

LSTM (Long Short-Term Memory) – For sequence modeling

Kaggle API – Dataset download and integration

🔄 Workflow
Install Kaggle and upload kaggle.json API token.

Download & Extract Dataset using Kaggle CLI.

Read & Explore the dataset using Pandas.

Preprocess Text Data: Tokenize and pad sequences.

Train-Test Split: 80% for training, 20% for testing.

Model Building:

Embedding Layer

LSTM Layer (128 units)

Dense Output Layer with Sigmoid activation

Model Training: 5 epochs, batch size of 64.

Evaluation: Achieved ~88.8% accuracy on test data.

Prediction System: Input your own movie review to test sentiment.
