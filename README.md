# Recommendation Systems 101

This series of tutorials explores different types of recommendation systems and their implementations. Topics include:

- collaborative vs. content-based filtering
- implicit vs. explicit feedback
- handling the cold start problem
- recommendation model evaluation

We will build various recommendation systems using data from the [MovieLens](https://movielens.org/) database. You will need Jupyter Lab to run the notebooks for each part of this series. Alternatively, you can also use Google’s new [colab platform](https://colab.research.google.com) which allows you to run a Jupyter notebook environment in the cloud. You won't need to install any local dependencies; however, you will need a gmail account. 

The series is divided into 3 parts:

1. [Building an Item-Item Recommender with Collaborative Filtering](#part-1-building-an-item-item-recommender-with-collaborative-filtering)
2. [Handling the Cold Start Problem with Content-based Filtering](#part-2-handling-the-cold-start-problem-with-content-based-filtering)
3. [Building an Implicit Feedback Recommender System](#part-3-building-an-implicit-feedback-recommender-system)


More information on each part can be found in the descriptions below.

### Part 1: Building an Item-Item Recommender with Collaborative Filtering

| |Description |
|:-----------|:----------|
|Objective|Want to know how Spotify, Amazon, and Netflix generate "similar item" recommendations for users? In this tutorial, we will build an item-item recommendation system by computing similarity using nearest neighbor techniques.|
|Key concepts|collaborative filtering, content-based filtering, k-Nearest neighbors, cosine similarity|
|Requirements|Python 3.6+, Jupyter Lab, numpy, pandas, matplotlib, seaborn, scikit-learn|
|Tutorial link|[Jupyter Notebook](part-1-item-item-recommender.ipynb)|
|Resources|[Item-item collaborative filtering](https://www.wikiwand.com/en/Item-item_collaborative_filtering), [Amazon.com Recommendations](https://www.cs.umd.edu/~samir/498/Amazon-Recommendations.pdf), [Various Implementations of Collaborative Filtering](https://towardsdatascience.com/various-implementations-of-collaborative-filtering-100385c6dfe0) |


### Part 2: Handling the Cold Start Problem with Content-based Filtering

| |Description |
|:-----------|:----------|
|Objective|Collaborative filtering fails to incorporate new users who haven't rated yet and new items that don't have any ratings or reviews. This is called the cold start problem. In this tutorial, we will learn about clustering techniques that are used to tackle the cold start problem of collaborative filtering.|
|Requirements|Python 3.6+, Jupyter Lab, numpy, pandas, matplotlib, seaborn, scikit-learn|
|Tutorial link|[Jupyter Notebook](part-2-cold-start-problem.ipynb)|


### Part 3: Building an Implicit Feedback Recommender System

| |Description |
|:-----------|:----------|
|Objective|Collaborative filtering fails to incorporate new users who haven't rated yet and new items that don't have any ratings or reviews. This is called the cold start problem. In this tutorial, we will learn about clustering techniques that are used to tackle the cold start problem of collaborative filtering.|
|Requirements|Python 3.6+, Jupyter Lab, numpy, pandas, implicit|
|Tutorial link|[Jupyter Notebook](part-3-implicit-feedback-recommender.ipynb)|