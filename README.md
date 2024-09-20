# IMDB Sentiment Analysis
Project to identify Positive and Negative reviews based on their text using NLP.

# Table of Contents

    Dataset
    Problem Statement
    Project Structure
    Model and Results
    Skills Acquired
    How to Run
    Acknowledgements

### Dataset
The dataset consists of 25000 reviews from the Internet Movie Data base and is hosted at Stanford AI. You can download it from here (~85 Mb):
https://ai.stanford.edu/~amaas/data/sentiment/

Or follow the code in the [notebook 1](notebooks/todo_text_classification_with_spacy_NLP_part1.ipynb)

### Problem
Can we build a model that can predict if a review on a movie is positive or negative based on the text the user wrote? 
For instance, this review:
```
The special effects were pretty good and more than a little intimidating. Not sure I'll ever go deep sea fishing again...I expected a little more emotion in the film than what was presented.Definitely a movie that could've been seen on DVD.
```
The user rated it as a good movie, but can we build a model that can predict it? We see that even for humans this task is not trivial.

### Results
We found that with a LSTM RNN we could predict if a review was positive or negative with the following metrics:
```
Accuracy: 0.7645
Precision: 0.8190591073582629
Recall: 0.679
```

### Skills Acquired
- Familiarized myself with the Spacy library
- Learn how to clean and process text datasets
- Wrote my own tokenizing function
- Used Bag of Words (BoW) and Term Frequency Inverse Document Frequency (TFIDF) for text analysis
- Used Cosine similarity of vectorized words to calculate their similarity
- Visualized different text embeddings using PCA
- Trained RNNs (with LSTM) to improve the predictions on sentiment analysis

### Acknowledgements
Mariona Carós Roca prepared these notebooks for the Data Science course at the University of Barcelona.
