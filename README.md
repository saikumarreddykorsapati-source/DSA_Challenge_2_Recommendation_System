# DSA_Challenge_2_Recommendation_System

DEMO : https://dsa-challenge-2.herokuapp.com/

Data Sets Link : https://www.kaggle.com/tmdb/tmdb-movie-metadata?select=tmdb_5000_movies.csv

## TechStack Used:
pandas, numpy, ast - abstract syntax trees, sklearn.feature_extraction.text - CountVectorizer, sklearn.metrics.pairwise - cosine_similarity,  streamlit, requests, pickle

## Installation:
Download the data sets from the link provided above, execute ```RS_Model_Creation_DSA_challenge_2.ipynb``` two picekl files will be created one for movie_list another for similarity. provide those pickels files paths in  ```rc_webapp.py``` and then in any of your favourite editor vscode or pycharm create an virtual env then install the neccessay libraries like streamlit, requests etc., and execute ``` streamlit app rc_webapp.py ``` then open localhost to see the recomendation system app.
