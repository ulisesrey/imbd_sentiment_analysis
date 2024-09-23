# IMDB Sentiment Analysis

This project aims to classify movie reviews as positive or negative based on their textual content using natural language processing (NLP) techniques.

## Table of Contents
- [Dataset](#dataset)
- [Problem Statement](#problem-statement)
- [Model and Results](#model-and-results)
- [Skills Acquired](#skills-acquired)
- [Acknowledgements](#acknowledgements)

## Dataset

The dataset consists of 25,000 labeled movie reviews from the [IMDB dataset](https://ai.stanford.edu/~amaas/data/sentiment/) hosted by Stanford AI (~85 MB). Each review is classified as either positive or negative. 

You can download the dataset directly using the link above or load it via the code in the [first notebook](notebooks/todo_text_classification_with_spacy_NLP_part1.ipynb).

## Problem Statement

The goal of this project is to build a model capable of predicting whether a movie review is positive or negative based on its text. For example, consider the following review:

> The special effects were pretty good and more than a little intimidating. Not sure I'll ever go deep sea fishing again... I expected a little more emotion in the film than what was presented. Definitely a movie that could've been seen on DVD.


Although this review has mixed emotions, the user rated the movie positively. Our challenge is to build a model that can make accurate predictions on such ambiguous cases.

## Model and Results

We employed various text-processing techniques and trained a Recurrent Neural Network (RNN) with Long Short-Term Memory (LSTM) cells to predict sentiment. Below are the evaluation metrics for our best-performing model:

- **Accuracy**: 76.45%
- **Precision**: 81.91%
- **Recall**: 67.90%


## Skills Acquired

- Proficient use of the **spaCy** library for NLP tasks.
- Preprocessing and cleaning of text datasets.
- Implementation of custom tokenizers.
- Use of **Bag of Words (BoW)** and **Term Frequency-Inverse Document Frequency (TF-IDF)** for text vectorization.
- Calculation of **cosine similarity** between vectorized word representations.
- Visualization of word embeddings using **Principal Component Analysis (PCA)**.
- Training and tuning **RNNs with LSTMs** to improve sentiment analysis performance.

## Acknowledgements

This project was developed as part of the Data Science course at the University of Barcelona, with special thanks to **Mariona Carós Roca** for preparing the notebooks.
