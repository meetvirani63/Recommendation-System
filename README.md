Created by: Meet Virani

-------------------------------------------------------------------------------------------------------------------------------------

Movie Recommender System

Introduction:

A movie recommender system is a tool that uses machine learning to suggest movies you might enjoy. It analyzes vast amounts of data to find patterns in movie preferences. These patterns can be based on your own viewing history (collaborative filtering) or similarities between movies themselves (content-based filtering).

How it works:

There are two main approaches recommender systems take:

Collaborative Filtering: 
This method analyzes how other users, with similar taste to you, have rated movies.  Imagine you and a friend both loved themovie "Spirited Away."  The system would notice this and look for other movies that your friend enjoyed, but you haven't seenyet. These movies would then be recommended to you.

Content-Based Filtering: 
This approach focuses on the characteristics of the movies themselves.  For instance, if you really enjoyed the action-packedthrill ride of "Mad Max: Fury Road," the system might recommend other action movies with high ratings or movies featuring actorsfrom "Mad Max."

Many recommender systems actually combine these two techniques for a more well-rounded approach.

-------------------------------------------------------------------------------------------------------------------------------------

This project implements a movie recommendation system using content based filtering. It utilizes the TMDb movie dataset to recommend movies similar to a user's selection.

Key Features:

* Recommends movies based on user selection.
* Incorporates data cleaning and pre-processing techniques.
* Utilizes Streamlit for a user-friendly web interface.

Data Preparation:

The code includes snippets demonstrating the following data preparation steps:

1. Importing necessary libraries (pandas, numpy etc.)
2. Loading movie data and credit data from CSV files.
3. Merging the datasets to combine movie information with cast and crew details.
4. Data cleaning steps like handling missing values and converting textual data to a suitable format.
5. Creating a vectorizer to represent movie descriptions and user tags.

Model Training:

The system utilizes cosine similarity to calculate the similarity between movies based on their vectors. This allows the system to recommend movies with similar descriptions and user preferences. 

Evaluation:

The model's performance is evaluated using metrics like precision and recall to assess its effectiveness in recommending relevant movies.


Future Improvements:

Implement a hybrid recommendation approach that combines collaborative filtering and content-based filtering for more personalized recommendations.

