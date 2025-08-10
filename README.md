# KNN Movie Recommendation System

This project is a simple **Movie Recommendation System** built using the **K-Nearest Neighbors (KNN)** algorithm.  
It predicts a movie title based on the **genre** and **popularity** provided by the user.

## 📂 Dataset
The system uses the `tmdb_5000_movies.csv` dataset, which contains metadata such as:
- Movie titles
- Genres
- Popularity scores
- Original language
- And more…

## ⚙ Features
- Extracts and cleans genres from JSON strings in the dataset.
- Encodes genres and movie titles into numerical labels.
- Uses **KNN Classifier** to predict the most likely movie.
- Returns prediction confidence.
- Shows top popular movies based on dataset popularity scores.

##  Installation & Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/KNN-movie-recommendation.git
   cd KNN-movie-recommendation
