# Recommendation Systems 101

This series of tutorials explores different types of recommendation systems and their implementations. Topics include:

- collaborative vs. content-based filtering
- implicit vs. explicit feedback
- handling the cold start problem
- recommendation model evaluation

We will build various recommendation systems using data from the [MovieLens](https://movielens.org/) database. You will need Jupyter Lab to run the notebooks for each part of this series. Alternatively, you can also use Google’s new [colab platform](https://colab.research.google.com) which allows you to run a Jupyter notebook environment in the cloud. You won't need to install any local dependencies; however, you will need a gmail account. 

The series is divided into 5 parts:

1. [Building an item-item recommender with collaborative filtering](#part-1-building-an-item-item-recommender-with-collaborative-filtering)
2. [Handling the Cold Start Problem with Content-based Filtering](#part-2-handling-the-cold-start-problem-with-content-based-filtering)
3. [Enhancing the Quality of Recommendations with Matrix Factorizationm](#part-3-enhancing-the-quality-of-recommendations-with-matrix-factorization)
4. [Building an implicit-feedback recommendation system](#part-4-building-an-implicit-feedback-recommendation-system)
5. [Evaluating the performance of a recommendation model](#part-5-evaluating-the-performance-of-a-recommendation-model) 

More information on each part can be found in the descriptions below.

### Part 1: Building an Item-Item Recommender with Collaborative Filtering

| |Description |
|:-----------|:----------|
|Objective|Want to know how Spotify, Amazon, and Netflix generate "similar item" recommendations for users? In this tutorial, we will build an item-item recommendation system by computing similarity using nearest neighbor techniques.|
|Key concepts|collaborative filtering, content-based filtering, k-Nearest neighbors, cosine similarity|
|Requirements|Python 3.6+, Jupyter Lab, numpy, pandas, matplotlib, seaborn, scikit-learn|
|Tutorial link|[Jupyter Notebook](part-1-item-item-recommender.ipynb)|
|Relevant slides|[slides here](https://github.com/topspinj/presentations/recommendation-systems)|
|Resources|[Item-item collaborative filtering](https://www.wikiwand.com/en/Item-item_collaborative_filtering), [Amazon.com Recommendations](https://www.cs.umd.edu/~samir/498/Amazon-Recommendations.pdf), [Various Implementations of Collaborative Filtering](https://towardsdatascience.com/various-implementations-of-collaborative-filtering-100385c6dfe0) |

### Part 2: Handling the Cold Start Problem with Content-based Filtering

| |Description |
|:-----------|:----------|
|Objective|Collaborative filtering fails to incorporate new users who haven't rated yet and new items that don't have any ratings or reviews. This is called the cold start problem. In this tutorial, we will learn about clustering techniques that are used to tackle the cold start problem of collaborative filtering.|
|Key concepts|k-means clustering, DBSCAN|
|Requirements|Python 3.6+, pandas, scikit-learn|
|Tutorial link|[Jupyter Notebook](part-2-cold-start-problem.ipynb)|
|Resources|[Cold Start and Hybrid Recommender Systems](https://www.youtube.com/watch?v=wEbatX4J-1g)|

### Part 3: Enhancing the Quality of Recommendations with Matrix Factorization

| |Description |
|:-----------|:----------|
|Objective|Reduce the dimensions of the user-item matrix using matrix factorization.|
|Key concepts|k-means clustering, DBSCAN|
|Requirements|Python 3.6+, pandas, scikit-learn|
|Tutorial link|[Jupyter Notebook](part-3-matrix-factorizationipynb)|
|Resources|Coming soon|


### Part 4: Building an implicit-feedback recommendation system

| |Description |
|:-----------|:----------|
|Objective|Unlike explicit feedback (e.g., user ratings), implicit feedback infers a user's degree of preference toward an item by looking at their indirect interactions with that item. In this tutorial, we will investigate two recommendation models that specifically handle implicit feedback datasets.|
|Key concepts|implicit feedback, matrix factorization, alternating least squares, learning to rank|
|Requirements|TBA|
|Tutorial link|TBA|
|Resources|[A Gentle Introduction to Recommender Systems with Implicit Feedback](https://jessesw.com/Rec-System/), [Collaborative Filtering for Implicit Feedback Datasets](http://yifanhu.net/PUB/cf.pdf), [Xavier Amatriain lecture](https://www.youtube.com/watch?v=bLhq63ygoU8)|


### Part 5: Evaluating the performance of a recommendation model

| |Description |
|:-----------|:----------|
|Objective|How do we measure the quality of a recommendation? In this tutorial, we will investigate offline evaluation metrics that assess the performance of recommendation systems.|
|Key concepts|evaluation, accuracy, precision, recall, F1|
|Requirements|TBA|
|Tutorial link|TBA|


### Slides

- [A Brief Intro to Recommendation Systems](https://github.com/topspinj/presentations/recommendation-systems) (PyLadies workshop)


