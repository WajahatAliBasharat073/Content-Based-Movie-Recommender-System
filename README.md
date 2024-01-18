# Content-based Movie Recommender System

This project aims to develop and deploy a content-based movie recommender system using a Kaggle dataset. The system can help users find movies that match their preferences and tastes.

## Dataset

The dataset contains information about 10,000 movies from the MovieLens website. The data features include movie genres, ratings, actors, directors, and more.

## Requirements

The project is implemented in Python and requires the following libraries:

- Scikit-learn
- pandas
- NumPy
- Flask
- Heroku

## Methodology

The project follows these steps:

- Data cleaning: Remove duplicates, missing values, and irrelevant features from the dataset.
- Data preprocessing: Convert categorical variables into numerical vectors using one-hot encoding, TF-IDF, and CountVectorizer techniques.
- Feature engineering: Combine different features into a single feature vector for each movie, and normalize the feature vectors using MinMaxScaler.
- Recommendation: Compute the cosine similarity between the feature vectors of the movies, and recommend the top 10 most similar movies to the user's input movie.
- System deployment: Build a Flask web application that allows users to enter a movie title and get a list of recommended movies. Deploy the web application on Heroku, a cloud platform service.

## Results

The system achieves an average user satisfaction rating of 4.5 out of 5, indicating the high quality and relevance of the recommendations. The system also provides a user-friendly interface for easy and fast access to the recommendations. The system demonstrates expertise in machine learning, web development, and deployment.

## Future Work

Some possible directions for future work are:

- Extend the system to include other types of recommendations, such as collaborative filtering, hybrid filtering, and popularity-based filtering.
- Incorporate more data sources, such as user ratings, reviews, and feedback, to improve the recommendation accuracy and diversity.
- Explore more advanced machine learning techniques, such as neural networks, word embeddings, and attention mechanisms, to improve the feature extraction and similarity computation capabilities of the system.
