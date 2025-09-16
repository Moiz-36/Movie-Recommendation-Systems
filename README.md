This project implements a simple movie recommendation system using Python, pandas, and scikit-learn. It recommends movies based on their similarity to a given movie, utilizing the TF-IDF vectorization and cosine similarity techniques on selected movie features.

Features:

Reads movie data from a CSV file.
Combines relevant features (genres, keywords, tagline, cast, director) for similarity calculation.
Uses TF-IDF to convert text data into numerical vectors.
Calculates cosine similarity between movie vectors.
Takes a movie name as input and finds the closest match in the dataset.
Provides a list of recommended movies based on similarity scores.
How to Use:

Ensure you have the required libraries installed (pandas, numpy, seaborn, difflib, scikit-learn).
Run the notebook cells sequentially.
Enter the name of a movie when prompted.
The system will output a list of movie suggestions based on similarity.
This project serves as a basic example of content-based movie recommendation.
