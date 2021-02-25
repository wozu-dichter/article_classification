# article_classification
Application of Multiclassification and Clustering on articles

## Platform
Google Collab

## Language
Python

## Libraries
Sklearn, Pandas, Numpy, Nltk, Seaborn

## Description / Goals 
1. Create WordClouds for each one of the five articles' categories.
2. Implement different Classifiers using word counts and tf-idf transformations embeddings:
   * Support Vector Machines (sklearn)
   * Random Forests (sklearn)
   * Naive Bayes (sklearn)
   * K-Nearest Neighbor (implementation of K-Nearest Neighbor algorithm using Majority Voting to predict the final label)
  
   We evaluate the performance of each method using 10-fold Cross Validation with the following metrics:
    * Accuracy
    * Precision  
    * Recall 
    * F1-score
    * ROC plot 
3. Implement Clustering using the K-Means clustering algorithm and Cosine Similarity as the distance function. <br> The clustering is applied in the following representations of the articles:
* Bag of words representation of texts (word counts & tf-idf transformation of counts)
* Pre-trained word2vec embeddings 
We visualize the distribution of texts in the spacethe points in 2d space, use a compression method
* Principal Component Analysis (PCA) 
* Singular Value Decomposition (SVD) 
* Independent Component Analysis (ICA)

## Tips
Add the 'articles.tsv' dataset in your 'gdrive/My Drive/Colab Notebooks/' path to execute correctly

## Author
Vassilis Panagakis

## Date
May 2020
