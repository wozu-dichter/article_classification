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
*  F1-score
* ROC plot 
3. Implement Clustering
In this query you need to implement clustering in the various text files.
The number of clusters for each query will be 5. The clustering will be done with
use of the K-Means clustering algorithm. The distance function that should
to be used is Cosine Similarity. K-Means will be applied to the data
training set. Clustering should be implemented without
use the Category variable. The clustering should be done in the following
different representations of the texts:
● In the corresponding document-words table that will result from BoW
representation of texts (both in simple counts and individually in
tf-idf transformation of counts)
● In the corresponding document-embeddings table that will appear
using pre-trained embeddings (one of word2vec, glove, fast-text).
Also, visualize the distribution of texts in the space and make it visible
the cluster they belong to as well as their actual category. To
you can view the points in 2d space, use a compression method
Principal Component Analysis (PCA), Singular Value Decomposition (SVD) or
Independent Component Analysis (ICA) (if you use all 3 you have a bonus). The
compression method you will apply it to both representations mentioned
previously.


## Tips
Add the 'articles.tsv' dataset in your 'gdrive/My Drive/Colab Notebooks/' path to execute correctly

## Author
Vassilis Panagakis

## Date
May 2020
