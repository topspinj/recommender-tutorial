# Intro to Recommendation Systems in Python

The html version of this tutorial can be found [here](https://topspinj.github.io/recommender-tutorial/).

### Skill level: intermediate

### Requirements

- Python 3.6+
- Jupyter Lab
- numpy
- pandas
- matplotlib
- scikit-learn

Alternatively, you can also use Google’s new [colab platform](https://colab.research.google.com) which allows you to run a Jupiter notebook environment in the cloud. You won't need to locally install any of the above; however, you will need a gmail account. 

### Description

In this tutorial, we will explore the different types of recommendation systems and their implementations. We will also build our own recommendation system using data from the [MovieLens](https://movielens.org/) database.

### What is a recommendation system?

A recommendation system is an algorithm that predicts a user's preference toward an item. In most cases, its goal is to **drive user engagement**.  

**Examples:**

- recommending products based on past purchases or product searches (Amazon)
- suggesting TV shows or movies based on prediction of a user's interests (Netflix)
- creating well-curated playlists based on song history (Spotify)
- personalized ads based on "liked" posts or previous websites visited (Facebook)

The two most common recommendation system techniques are: 1) collaborative filtering, and 2) content-based filtering

### Collaborative Filtering 

- based on the concept of homophily: similar users will like similar items

#### Data format

- user-item utility matrix

<img src="images/utility-matrix.png" width="280px">

- memory-based: looks at item-item, user-item, user-user similarity using cosine similarity or Pearson correlation coefficient 
- model-based: matrix factorization

### Content-based Filtering

- generates recommendations based on user and item features 
- handles the cold start problem
    - can generate personalized recommendations for brand new users and features 

#### Data format 

- user features
    - e.g., age, gender, country, language, etc.
- item features
    - e.g., movie genre, release date, country, language, etc.

<img src="images/cb-filtering.png" width="550px">

### Hybrid Filtering

This approach combines both collaborative and content-based filtering.

### How do we define a user's "preference" towards an item?

There are two types of feedback data:

1. Explicit feedback, which considers a user's direct response to an item (e.g., rating, like/dislike)

2. Implicit feedback, which looks at a user's indirect behaviour towards an item (e.g., number of times a user has watched a movie)

Before using this data in your recommendation system, it is important to perform some data pre-processing. For example, you should normalize ratings of different users to the same scale. More information on how to normalize data in recommendation systems is described [here](https://www.cs.purdue.edu/homes/lsi/sigir04-cf-norm.pdf).