What is a recommendation system?
================================

A recommendation system is an algorithm that matches items to users. Its goal is to predict a user's preference toward an item.

Examples
+++++++++
- recommending products based on past purchases or product searches (Amazon)
- suggesting TV shows or movies based on prediction of a user's interests (Netflix)
- creating well-curated playlists based on song history (Spotify)
- personalized ads based on "liked" posts or previous websites visited (Facebook)

The two most commonly used methods for recommendation systems are: 1) collaborative filtering, and 2) content-based filtering. 

Collaborative Filtering 
++++++++++++++++++++++++

- utility matrix

.. image:: images/utility-matrix.png
   :width: 280px


Content-based Filtering
++++++++++++++++++++++++

- user and item features

.. image:: images/cb-filtering.png
   :width: 550px


How do we define a user's "preference" towards an item?
+++++++++++++++++++++++++++++++++++++++++++++++++++++++

There are two types of feedback data:

1. Implicit feedback (e.g., number of times a user has watched a movie)
2. Explicit feedback (e.g., movie ratings)


