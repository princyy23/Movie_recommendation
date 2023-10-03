# Movie_recommendation
This repository contains a Python code for a movie recommender system. The system works by first processing a dataset of movies and their metadata, such as genres, keywords, cast, and crew. This data is then used to create a vector representation of each movie, which captures the key words and concepts that are associated with it.

Next, the system calculates the cosine similarity between all pairs of movies. This measure of similarity tells us how similar two movies are based on their vector representations.

Finally, the system uses the cosine similarity matrix to recommend movies to users. Given a movie that a user likes, the system can recommend other movies that are similar to it.

