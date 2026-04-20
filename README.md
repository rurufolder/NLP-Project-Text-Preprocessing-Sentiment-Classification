# NLP Project: Sentiment Analysis on IMDB Movie Reviews

This is a project I did for my Natural Language Processing course (DS483). It compares two models for classifying movie reviews as positive or negative.

## What the project does

First, it cleans the text using NLTK (lowercase, remove punctuation, remove stopwords, tokenization, lemmatization). Then it uses the IMDB dataset from Keras with 50,000 reviews. Two models are trained: Random Forest and LSTM.

## Results from my run

Random Forest:
- Accuracy: 52.84%
- Precision: 53.11%
- Recall: 48.47%

LSTM:
- Accuracy: 84.04%
- Precision: 88.11%
- Recall: 78.70%

The LSTM model performs much better because it captures word order and context, while Random Forest treats words independently.



## Implemented by

Reema AlFayez – DS483 course project at Saudi Electronic University
