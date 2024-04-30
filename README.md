# Anime-and-Chill---Recommendation-system
We create a Anime recommendation syatem using Pyspark
Anime and  Chill - Recommendation System

Welcome to the Anime Recommendation System project! This project uses Apache Spark's MLlib to build a recommendation system based on user ratings data. Our goal is to provide personalized anime recommendations using collaborative filtering techniques implemented with the Alternating Least Squares (ALS) algorithm.

Features
* Collaborative Filtering: Utilize user ratings to predict and recommend anime titles.
* Cosine Similarity: Analyze similarities between different animes to refine recommendations.
* Data Visualization: Plot and compare the actual ratings against predictions to evaluate the model performance.
  
Project Structure
```bash
/root
│
├── preprocessed_data
│   ├── anime.csv          # Dataset containing anime titles and IDs
│   ├── rating.csv         # User ratings for different animes
│   └── user.csv           # User demographic data (optional)
│
├── notebooks                        # Source files for the project
│   ├── Recommendation_system.ipynb  # Main script for the recommendation system
│   ├── Pre-Processing book.ipynb    # Preprocessing script for data cleaning
│
│
├── data                             # After preprocessing Dataset
│   ├── updated_anime_cleaned.zip    # After preprocessing dataset for Animes
│   ├── updated_ratings_cleaned.zip  # After preprocessing dataset for Ratings
│   ├── updated_users_cleaned.zip    # After preprocessing dataset for Users
│
├── model12     # Exported model - for recommendation of animes from ALS training
│
└── README.md              # Project documentation

```
Prerequisites
* Apache Spark 3.2.0
* Python 3.7 or higher
* Libraries: Pandas, NumPy, Matplotlib, FindSpark, Pyspark
* Java 8

API Documentation
* recommend_for_user(user_id)
* Returns a list of recommended anime titles for a given user.

Parameters:
*user_id (int): The ID of the user for whom recommendations are to be made.

Authors
* Ankit Singh Chauhan
* Amritha Prakash
* Navdeep Meltchu
* Pritesh Shah

Acknowledgments
* kaggle.com
* myanimelist.com
* Special thanks to all the anime fans out there!
