![Movies Recommendations Case Study](imgs/cover.jpg)
# Movies Recommendations Case Study
- [Table of Contents](#heading)
  * [Introduction](##Introduction)
  * [Dataset](##Dataset)
  * [Models](##Models)
    + [Content Based Filtering](#Content-Based-Filtering)
    + [Collaborative Filtering](#Collaborative-Filtering)
        + [Matrix Factorization](#Matrix-Factorization)
        + [Deep Learning](#Deep-Learning)
  * [Requirements](#Requirements)

## Introduction
What movie should I watch this evening?,
Have you ever had to answer this question at least once when you came home from work? As for me — yes, and more than once. From Netflix to Hulu, the need to build robust movie recommendation systems is extremely important given the huge demand for personalized content of modern consumers.

An example of recommendation system is such as this:
- User A watches **Game of Thrones** and **Breaking Bad**.
- User B does search on **Game of Thrones**, then the system suggests **Breaking Bad** from data collected about user A.

Recommendation systems are used not only for movies, but on multiple other products and services like Goodreads (Books) Amazon (Items), Pandora/Spotify (Music), Google (News, Search), YouTube or Netflix (Videos) etc.

Two most ubiquitous types of personalized recommendation systems are **Content-Based** and **Collaborative Filtering**. Collaborative filtering produces recommendations based on the knowledge of users’ attitude to items, that is it uses the wisdom of the crowd to recommend items. In contrast, content-based recommendation systems focus on the attributes of the items and give you recommendations based on the similarity between them.

In this repository, We will attempt at implementing these two systems to recommend movies and evaluate them to see which one performs better.

**Let’s get started ..**

## Dataset

One of the most common datasets that is available on the internet for building a Recommender System is the [MovieLens DataSet](https://grouplens.org/datasets/movielens/). This version of the dataset that I'm working with (1M) contains 1,000,209 anonymous ratings of approximately 3,900 movies made by 6,040 MovieLens users who joined MovieLens in 2000.

The data was collected by GroupLens researchers over various periods of time, depending on the size of the set. This 1M version was released on February 2003. Users were selected at random for inclusion. All users selected had rated at least 20 movies. Each user is represented by an id, and no other information is provided.

## Models
- we worked in building 2 types of recommednation systems:
    - Content Based Filtering :
    
         that finds similars for specific item based on its content.
    - Collaborative Filtering :
    
         that finds similarity based on history of user and his prefrences with another users those interacts with same movies. and represent it by two methods :
         
         - Matrix Factorzation : 

            uses SVD to predict approxmate user ratings. 

        - Deep Learning :

            uses deep neural network to apply embedding on users and movies to predict approxmate user ratings.
    

## Requirements

* [Python 3.6](https://www.python.org/downloads/release/python-360/)
* [Jupyter Notebook](http://jupyter.org/)

- Choose the latest versions of any of the dependencies below:
    * [pandas](https://pandas.pydata.org/)
    * [numpy](http://www.numpy.org/)
    * [scipy](https://www.scipy.org/)
    * [matplotlib](https://matplotlib.org/)
    * [sklearn](http://scikit-learn.org/stable/)
    * [wordcloud](https://github.com/amueller/word_cloud)
    * [NLTK](https://nltk.org/)
    * [keras](https://keras.io/)
    * [h5py](https://www.h5py.org/)
