Sentiment Analysis on Arabic Tweets

Overview

This project focuses on Sentiment Analysis of Arabic tweets, classifying them as positive, negative, or neutral. It involves data preprocessing, feature extraction, and model training using machine learning techniques.

Features

Data Preprocessing:

Tokenization, stopword removal, and normalization for Arabic text.

Handling emojis and special characters.

Feature Engineering:

TF-IDF and Word Embeddings (Word2Vec, FastText, or BERT).

Model Training & Evaluation:

Machine Learning: Logistic Regression, Random Forest, SVM

Deep Learning: LSTMs, BERT (Optional)

Metrics: Accuracy, Precision, Recall, and F1-score

Dataset

Arabic tweets collected from Twitter.

Labeled with sentiment categories: Positive, Negative, Neutral.

Installation

Install dependencies before running the project:

pip install pandas numpy scikit-learn nltk gensim arabicstopwords transformers

Usage

Run the preprocessing and model training script:

python sentiment_analysis.py

Results

Identified sentiment trends in Arabic tweets.

Compared different models to find the best-performing one.

Future Improvements

Improve accuracy using pretrained Arabic BERT models.

Expand dataset for better generalization.

License

This project is open-source and available under the MIT License.

