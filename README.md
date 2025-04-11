This project showcases a Movie Recommendation System built using two fundamental techniques:

Demographic Filtering

Collaborative Filtering (User-Based)

1. Demographic Filtering
Demographic Filtering recommends movies based on their overall popularity and critical reception. It is a non-personalized approach that ranks movies using factors such as:

Average rating

Number of votes

Weighted score (e.g., IMDB’s weighted rating formula)

 Pros:
Simple and fast

Effective for new users (cold start problem)

Works well for highlighting popular or trending movies

Limitations:
Same recommendations for every user

Doesn’t consider individual preferences

2. Collaborative Filtering
To overcome the limitations of demographic filtering, we implemented Collaborative Filtering, which offers personalized recommendations. Specifically, we used:

User-Based Collaborative Filtering
Recommends movies by identifying users with similar rating behavior

Measures similarity using metrics like cosine similarity or Pearson correlation

Predicts movies a user might like based on the preferences of similar users

Pros:
Personalized recommendations

Suggests diverse genres

Improves with more user interaction

Limitations:
Struggles with new users (cold start)

Can be computationally expensive on large datasets

Technologies Used
Python

Google Colab

Pandas, NumPy

Scikit-learn (for similarity computations)

Matplotlib / Seaborn (for visualizations



Notebook Structure
The notebook includes:

Data loading and preprocessing

Demographic filtering implementation

User-based collaborative filtering implementation

Visualization of results

Recommendation outputs for sample users

How to Use
Open the notebook in Google Colab

Upload your datasets (e.g., movies.csv, ratings.csv)

Run the cells to see:

Top movies based on demographic filtering

Personalized recommendations using collaborative filtering






