

# Movie Recommendation System

## Introduction  
Recommendation systems are a specialized branch of machine learning designed to analyze user behavior and item characteristics to deliver personalized suggestions. Major companies like Google, Instagram, Spotify, Amazon, and Netflix use these systems to enhance user engagement and retention.  

For example:  
- Spotify recommends music similar to tracks a user has previously enjoyed.  
- Netflix suggests movies based on viewing history and preferences.  

These systems use collaborative filtering, content-based filtering, and hybrid models to improve recommendations and optimize the user experience.  

## Movie Recommendation System  

This project develops a machine learning-driven movie recommendation system using multiple datasets. It predicts user preferences by analyzing personal tastes and community ratings, helping users discover relevant movies.  


## Types of Recommender Systems  

### 1. Simple Recommender (IMDb Dataset)  
- Suggests movies based on popularity metrics (e.g., overall ratings, review counts).  
- Does not consider individual user preferences.  

### 2. Knowledge-Based Recommender (IMDb Dataset)  
- Uses movie metadata (e.g., genre, director, actors) for recommendations.  
- Suggests movies based on a user’s past viewing history and preferences.  

### 3. Content-Based Recommender (IMDb Dataset)  
- Analyzes movie attributes and the user’s past interactions.  
- Suggests movies similar to those previously watched.  

### 4. Metadata-Based Recommender (IMDb Dataset)  
- Relies on descriptive metadata (e.g., release year, themes, keywords) for recommendations.  

### 5. Collaborative Filtering Recommender (MovieLens Dataset)  
- Predicts user preferences based on:  
   - User-User Filtering (suggests movies liked by users with similar habits).  
   - Item-Item Filtering (suggests movies similar to those the user has rated positively).  

### 6. Hybrid Recommender (MovieLens Dataset)  
- Combines content-based and collaborative filtering for personalized recommendations.  
- Estimates ratings for unrated movies using user profiles and similar user preferences.  

# Datasets
- The IMDb dataset was downloaded from Kaggle: https://www.kaggle.com/datasets/rounakbanik/the-movies-dataset
- The MovieLens dataset was downloaded from Kaggle: https://www.kaggle.com/datasets/prajitdatta/movielens-100k-dataset or '.csv' format at https://www.kaggle.com/datasets/rounakbanik/the-movies-dataset?select=movies_metadata.csv

# Acknowledgements
- This work was inspired by the book: "Hands-On Recommendation Systems with Python: Start Building Powerful and Personalized, Recommendation Engines with Python"
