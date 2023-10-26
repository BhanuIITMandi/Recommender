# Movie Recommendation System

This repository contains two Jupyter Notebook files that implement movie recommendation systems using different techniques: Word2Vec and Bag of Words.


## Files

1. **movie_reco_word2vec_pretrained.ipynb**
   - Implements a movie recommendation system using Word2Vec embedding.
   - Text preprocessing includes lemmatization using `WordNetLemmatizer`.
   - Uses Google News pre-trained Word2Vec `GoogleNews-vectors-negative300.bin.gz` embedding file.

2. **Recommender.ipynb**
   - Implements a movie recommendation system using Bag of Words (BoW) representation.
   - Text preprocessing includes stemming using `PorterStemmer`.

## Acknowledgments
- The dataset used in this project is sourced from `TMDB 5000 Movie Dataset` downloaded from [https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata].