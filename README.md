
/*

     Author:: Raj Mehrotra
     Date:: 20-01-2019
     
 */

# Amazon-Fine-Food-Reviews-Analysis
The famous Amazon fine food reviews dataset on Kaggle for text classification.

First the data is cleaned and pre-processed using **standard NLP techniques like tokenization,stemming ,stop-words removal among others**.  Then I have performed sentiment analysis on the dataset using different approaches.  

**1)** The first approach used is the **traditional Bag-of-Words (BOW) approach using Tfidf and Count Vectorizer** in scikit. In this case the **word level tfidf vectorizer using the Logistic Regression gave best results for me with an accuracy of about a little more than 86%.**

**2)** In the second approach I have used the **Google Word2Vec word embeddings from Gensim** librray and trained a **LSTM model in Keras** on them. **This method also gives an accuracy of about 85%.**
