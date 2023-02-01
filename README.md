# Movie Recommendation System
This is a movie recommendation system built with the Streamlit framework and powered by the cosine similarity metric from the scikit-learn library. The system allows users to search for a movie and receive a list of recommended movies based on the selected movie's genre and other features.

## Cosine Similarity
Cosine similarity is a metric used to determine the similarity between two non-zero vectors of an inner product space. In this project, we use cosine similarity to measure the similarity between movies based on their genre and other features.

The cosine similarity score between two movies is calculated as the cosine of the angle between their feature vectors. A score of 1 means the two movies are exactly similar, while a score of 0 means they are completely dissimilar.

## Features
The movie dataset used in this project contains the following features:

Title
Genre
Year of release
In addition to these features, we also created binary features for each genre in the dataset. These binary features indicate whether a movie belongs to a particular genre or not.

The genre and binary genre features were used as the input features for the cosine similarity calculation.

## Recommendation Algorithm
The recommendation algorithm is based on the cosine similarity between the movies. The cosine similarity is a measure of the similarity between two non-zero vectors of an inner product space. In this case, the movies are represented as binary feature vectors, with each feature representing a genre. The cosine similarity matrix is calculated using the scikit-learn library and is used to find the most similar movies for a given movie.

## Usage
To run the movie recommendation system, simply run the following command in your terminal:
```
streamlit run movie_recommendation_system.py

```

Once the app is running, select a movie from the dropdown menu and click the "Recommend Movie" button to receive a list of recommended movies based on the selected movie's genre and other features.

