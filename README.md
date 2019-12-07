# Empirical_Study_on_Text_Classification

Trying to establish an Empirical finding upon taking a closer look on how different Machine Learning Models would work on Google-play-store-reviews dataset. Pretty simple binary calssification approach has been adopted. We are trying to identify if the reviews are "Energy-Related" or not.

## Models Used
* Naive Bayes
* Linear Classifier
* Support Vector Machine
* Extreme Gradient Boosting
* Sahallow Neural Networks
* Deep Neural Networks
  - Convolutional Neural Network (CNN)
  - Long Short Term Model (LSTM)
  - Gated Recurrent Unit (GRU)
  - Bidirectional (RNN)
  - Recurrent Convolutional Neural Network (RCNN)

## Features Used
* **_Count Vectors_** :
  Matrix notation of the dataset in which every row represents a document from the corpus, every column represents a term from the  corpus, and every cell represents the frequency count of a particular term in a particular document.
* **_Word Level TF-IDF_**:
  Matrix representing tf-idf scores of every term in different documents
* **_N-gram Level TF-IDF_**:
  N-grams are the combination of N terms together. This Matrix representing tf-idf scores of N-grams
* **_Character Level TF-IDF_** :
  Matrix representing tf-idf scores of character level n-grams in the corpus
* **_Combinations Tried_**:
  - Count Vectors + Word Level TF-IDF
  - Count Vectors + N-gram Level TF-IDF
  - Count Vectors + Character Level TF-IDF
  - Word Level TF-IDF + N-gram Level TF-IDF
  - Word Level TF-IDF + Character Level TF-IDF
  - N-gram Level TF-IDF + Character Level TF-IDF
  - Count Vectors + Word Level TF-IDF + N-gram Level TF-IDF
  - Count Vectors + Word Level TF-IDF + Character Level TF-IDF
  - Count Vectors + N-gram Level TF-IDF + Character Level TF-IDF
  - Word Level TF-IDF + N-gram Level TF-IDF + Character Level TF-IDF
  - Count Vectors + Word Level TF-IDF + N-gram Level TF-IDF + Character Level TF-IDF
  
* **_Word Embeddings_**:

  Form of representing words and documents using a dense vector representation. The position of a word within the vector space is learned from text and is based on the words that surround the word when it is used. 
  * Glove (wiki-news-300d-2M.vec)
  * FastText (wiki-news-300d-2M.vec)
  * Word2Vec (wiki-news-300d-2M.txt)
  
[Special Thanks goes to https://www.analyticsvidhya.com](https://www.analyticsvidhya.com/blog/2018/04/a-comprehensive-guide-to-understand-and-implement-text-classification-in-python/)
