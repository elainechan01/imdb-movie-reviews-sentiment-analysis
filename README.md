# Sentiment Analysis ML Model

## Description
NLP project to perform sentiment analysis on movie reviews

## Architecture
📌 imdb-movie-reviews-small.ipynb

📒 Jupyter Notebook

### Process
#### Data Preprocessing
1. HTML decoding
2. Lowercase conversion
3. Contractions expansion (e.g. wouldn't -> would not)
4. Digits and punctuations removal
5. Word tokenization
6. Stop words removal and removal of insignificant words (less than 2 characters)
7. Lemmatization (reduce words to its root form)
#### Word Embeddings
Word embedding or word vector is an approach with which we represent documents and words. It is defined as a numeric vector input that allows words with similar meanings to have the same representation. It can approximate meaning and represent a word in a lower dimensional space. [turing.com/word-embeddings](https://www.turing.com/kb/guide-on-word-embeddings-in-nlp#what-is-word-embedding?)
1. Bag of Words (BoW): Calculate frequency of words in a document
2. TF-IDF (Term Frequency - Inverse Document Frequency): Determine the significance of words to a given document
#### Classification Models
Module: [scikit-learn](https://scikit-learn.org/stable/index.html)
1. [Multinomial Naive Bayes](https://scikit-learn.org/stable/modules/naive_bayes.html#multinomial-naive-bayes)
2. [Random Forest Classification](https://scikit-learn.org/stable/modules/ensemble.html#random-forests)
3. [Nearest Neighbors Classification](https://scikit-learn.org/stable/modules/ensemble.html#random-forests)

## Discussion

### Next Steps
📌 imdb-movie-reviews-big.ipynb
1. Enhance data preprocessing step
    - Entities detection (e.g. New York)
    - Slang correction [noslang.com](https://www.noslang.com/dictionary/)
    - Spelling correction [pyspellchecker](https://pypi.org/project/pyspellchecker/)
2. Enhance data-splitting techniques
    - Random
    - Stratified
    - Cross-Validation
3. Deep Learning with Keras
    - Implement a Recurrent Neural Network and evaluate performance 

### Dataset
🔗 [IMDB Dataset of 50K Movie Reviews](https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews)
