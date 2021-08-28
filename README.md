# 20 Newsgroup Dataset Analysis
## Introduction 

The 20 Newsgroups data set is a collection of approximately 20,000 newsgroup documents, partitioned evenly across 20 different newsgroups.
The 20 newsgroups collection has become a popular data set for experiments in text applications of machine learning techniques, such as text classification and text clustering.

For more information, click this link: http://qwone.com/~jason/20Newsgroups/

## Data

The data source: http://qwone.com/~jason/20Newsgroups/

## Tools
* BoA, Tf-idf, LDA
  * Gensim; sklearn
  
* Doc2Vec
  * Gensim
  
* Visualization
  * t-SNE [1] or PCA
  * matplotlib; seaborn; visdom; tensorboard
  * Matlab is also powerful
  
* Document clustering
  * sklearn.cluser.Kmeans
  * sklearn.metrics


## Project Flow

**1.**  Preprocess the dataset

* Clean the data and build the vocabulary
* Visualize the statistics of the dataset
* Baseline document features
* Bag-of-words; TF-IDF Model

**2.** Topic Modeling

* Train a LDA model with given topic number
* Visualize different topics
![Topic Modeling](https://user-images.githubusercontent.com/61637539/131232688-445100ef-9a5c-4197-a731-b7d1e155cba7.PNG)


**3.** Vector representation of documents

* Train a Doc2Vec model
* Visualize word embedding and document embedding
![Word2Vec-technical](https://user-images.githubusercontent.com/61637539/131232698-b849118b-c3bb-429f-847d-f716d25a2f2d.PNG)


**4.** Comparison between different document representations

* Document clustering
![Clustering-technical](https://user-images.githubusercontent.com/61637539/131232638-bb602d43-aeb1-4d7e-b864-aab74de4d465.PNG)


## Important Files

<code>FinalProject_codes1.ipynb</code> - Vector Representations  
<code>FinalProject_codes2.ipynb</code> - Topic Modeling  
<code>Text Classification methods in NLP using Deep Learning.ipynb</code> - Convoluted Neural Network   

<code>Topic_modeling_and_clustering_Report.pdf</code> - PDF report that decribes the appreaches used for document representation and classsification in python and compares 
the different approaches along with their visual representations using t-SNE
