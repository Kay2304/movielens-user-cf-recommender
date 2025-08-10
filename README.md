MovieLens 32M User-Based Collaborative Filtering Recommender
Overview
This project implements a user-based collaborative filtering recommendation system using the MovieLens 32M dataset. The system recommends movies to users based on similarities in user rating behavior.

Dataset
Source: MovieLens 32M Dataset

Files used: movies.csv, ratings.csv, and tags.csv

Dataset size: 32 million ratings, 87,000+ movies, 270,000+ users (full dataset)

For performance reasons, a subset of 10,000 users and 10,000 movies is used in this project.

Features
Data cleaning and filtering to focus on active users and popular movies

Construction of user-item rating matrix

Calculation of cosine similarity between users

Generation of personalized movie recommendations for a given user

Mapping movie IDs to titles for readable recommendations

How to Run
Clone the repository:

bash
Copy code
git clone https://github.com/Kay2304/movielens-user-cf-recommender.git
cd movielens-user-cf-recommender
Download the MovieLens 32M dataset from here and extract it into the project folder.

Install required Python packages:

bash
Copy code
pip install pandas numpy scikit-learn
Run the Jupyter notebook or Python script:

bash
Copy code
jupyter notebook
or

bash
Copy code
python recommender.py
Results Example
Here is a sample output recommending movies for user with ID 10:

diff
Copy code
Recommended movies for user 10:
- Léon: The Professional (1994)
- Fargo (1996)
- Monty Python and the Holy Grail (1975)
- Goodfellas (1990)
- Groundhog Day (1993)
- Good Will Hunting (1997)
- The Big Lebowski (1998)
- American Beauty (1999)
- The Green Mile (1999)
- Monsters, Inc. (2001)
Future Improvements
Implement item-based collaborative filtering for better scalability

Integrate matrix factorization techniques (e.g., SVD)

Optimize performance for full dataset usage

Add a web interface or API for interactive recommendations

Contact
Created by Keletso Mashabela
GitHub: https://github.com/Kay2304
Kaggle: https://www.kaggle.com/kay2304
LinkedIn: https://www.linkedin.com/in/keletso-mashabela-2a6a86248/
Email: keletso.xavi2@gmail.com
