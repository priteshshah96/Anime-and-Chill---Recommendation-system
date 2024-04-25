# Anime-and-Chill---Recommendation-system
We create a Anime recommendation syatem using Pyspark
Anime and  Chill - Recommendation System
Welcome to the Anime Recommendation System project! This project uses Apache Spark's MLlib to build a recommendation system based on user ratings data. Our goal is to provide personalized anime recommendations using collaborative filtering techniques implemented with the Alternating Least Squares (ALS) algorithm.

Features
Collaborative Filtering: Utilize user ratings to predict and recommend anime titles.
Cosine Similarity: Analyze similarities between different animes to refine recommendations.
Data Visualization: Plot and compare the actual ratings against predictions to evaluate the model performance.
Project Structure
```bash
/root
│
├── preprocessed_data
│   ├── anime.csv          # Dataset containing anime titles and IDs
│   ├── rating.csv         # User ratings for different animes
│   └── user.csv           # User demographic data (optional)
│
├── notebooks                    # Source files for the project
│   ├── recommendation.ipynb  # Main script for the recommendation system
│      
└── README.md              # Project documentation

```
Prerequisites
* Apache Spark 3.2.0
* Python 3.7 or higher
* Libraries: Pandas, NumPy, Matplotlib, FindSpark
* Java 8

API Documentation
* recommend_for_user(user_id)
* Returns a list of recommended anime titles for a given user.

Parameters:
*user_id (int): The ID of the user for whom recommendations are to be made.

Authors
* Pritesh Shah
* Ankit Singh Chauhan
* Amritha Prakash
* Navdeep Meltchu

Acknowledgments
kaggle.com
myanimelist.com
Special thanks to all the anime fans out there!
