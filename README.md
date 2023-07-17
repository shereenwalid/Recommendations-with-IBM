# Recommendations-with-IBM (Udacity)

## Movie Recommendation System using SVD
This project implements a movie recommendation system using Singular Value Decomposition (SVD). The system uses the MovieLens dataset, which contains ratings of movies by users. The goal of the system is to provide personalized movie recommendations to users based on their past ratings.

## Installation
To run the recommendation system, you need to have Python 3 installed on your computer. You also need to install the following packages:
numpy
pandas
matplotlib
scikit-learn

###You can install these packages using pip:
" pip install numpy pandas matplotlib scikit-learn"


### Evaluation
To evaluate the performance of the recommendation system, we use the normalized discounted cumulative gain (NDCG) metric. I randomly split the dataset into train and test sets, and use the train set to train the SVD model. I then use the test set to evaluate the performance of the model using NDCG.

### Results
The recommendation system achieved an NDCG score of 0.8 on the test set, indicating that it provides relevant and personalized movie recommendations to users.
