# Music-Recommendation
We created this project for recommending music to the usual listners.<br>
As we know that one of the most used machine learning algorithms is recommendation systems.<br>
A recommender (or recommendation) system (or engine) is a filtering system which aim is to predict a rating or preference a user would give to an item, eg. a film, a product, a song, etc.

There are two main types of recommender systems:<br>
 * Content-based filters<br>
Content-based filters predicts what a user likes based on what that particular user has liked in the past. On the other hand, collaborative-based filters predict what a user like based on what other users, that are similar to that particular user, have liked.
 * Collaborative filters<br>
Collaborative Filters work with an interaction matrix, also called rating matrix. The aim of this algorithm is to learn a function that can predict if a user will benefit from an item - meaning the user will likely buy, listen to, watch this item.
<br>Among collaborative-based systems, we can encounter two types: user-item filtering and item-item filtering.

What algorithms do collaborative filters use to recommend new songs? There are several machine learning algorithms that can be used in the case of collaborative filtering. Among them, we can mention nearest-neighbor, clustering, and matrix factorization.

K-Nearest Neighbors (kNN) is considered the standard method when it comes to both user-based and item-based collaborative filtering approaches.

In this project, we'll go through the steps for generating a music recommender system using a k-nearest algorithm approach.

The modules basically used in this project are warnings, pandas, numpy, matplotlib.pyplot, seaborn, scipy.sparse, recommeders.knn_recommender .