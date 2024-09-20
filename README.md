# IMDB Sentiment Analysis
Project to identify Positive and Negative reviews based on their text using NLP.

### Dataset
The dataset consists of 25000 reviews from the Internet Movie Data base and is hosted at Stanford AI. You can download it from here:
https://ai.stanford.edu/~amaas/data/sentiment/

Or follow the code in the [notebook 1](notebooks/todo_text_classification_with_spacy_NLP_part1.ipynb)

### Problem

### Results
We found that with a LSTM RNN we could predict if a review was positive or negative with the following metrics:
Accuracy: 0.7645
Precision: 0.8190591073582629
Recall: 0.679

### Skills Acquired
- Familiarized myself with the Spacy library
- Wrote my own tokenizing function
- Used Bag of Words (BoW) and Term Frequency Inverse Document Frequency (TFIDF) for text analysis
- Used Cosine similarity of vectorized words to calculate their similarity
- Trained RNNs (with LSTM) to improve the predictions on sentiment analysis.

### Acknowledgements
Mariona Carós Roca prepared these notebooks for the Data Science course at the University of Barcelona.
