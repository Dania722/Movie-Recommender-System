# Movie Recommender System 🍿🚀

Welcome to the Movie Recommender System project! This system leverages content-based filtering to provide personalized movie recommendations based on user preferences.

## Overview

This project involves:

- **Data Collection:** Gathering movie data from CSV files and extracting essential features like genres, cast, crew, and keywords.
- **Preprocessing Magic:** Cleaning and transforming data, handling missing values, and applying stemming to convert words to their root forms.
- **Feature Extraction:** Utilizing CountVectorizer to create a bag-of-words representation, capturing the essence of each movie's content.
- **Cosine Similarity Model:** Calculating cosine similarity between movies based on their vectorized tags, establishing the foundation for personalized recommendations.
- **Data Serialization:** Saving the final processed data and the similarity matrix using Pickle for seamless deployment.
- **Dynamic Movie Posters:** Integrating The Movie Database (TMDb) API to fetch eye-catching movie posters dynamically.

## How It Works

1. **Input Movie:** Choose a favorite movie, e.g., "Iron Man 2."
2. **Content Analysis:** The system analyzes genres, cast, crew, and keywords to understand the essence of the selected movie.
3. **Cosine Similarity:** Computes cosine similarity with other movies to recommend those with similar content.
4. **Dynamic Posters:** Enhances recommendations with dynamically fetched movie posters for an immersive experience.

## Key Outcomes

- **Personalized Recommendations:** Recommends movies based on the unique content features of each user's favorite film.
- **Interactive Interface:** Built with Streamlit for a user-friendly experience, allowing seamless interaction with the system.

## Tech Stack

- Python, Pandas, Scikit-Learn, Streamlit, TMDb API

## Results

Successfully achieved accurate movie recommendations, enhancing user engagement and satisfaction.


## How to Run the Streamlit App

1. **Run the Streamlit App:**
   - Ensure you are in the project directory.
   - Run the following command to start the Streamlit app:
     ```bash
     python -m streamlit run app.py
     ```

2. **Access the App:**
   - Once the app is running, it will provide a local URL (usually `http://localhost:8501/`).
   - Open your web browser and go to the specified URL to access the Movie Recommender System interface.

Feel free to dive into the code, experiment with your favorite movies, and let us know your thoughts! 🚀🍿

#DataScience #MachineLearning #RecommendationSystem #MovieRecommender
