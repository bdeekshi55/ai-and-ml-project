Movie Recommendation System:

This project builds a **Movie Recommendation System using Machine Learning**.
It analyzes user ratings and recommends movies based on **similar users’ preferences**.

Recommendation systems are widely used by companies such as:

* Netflix
* Amazon
* YouTube

The goal of this project is to demonstrate **collaborative filtering techniques for personalized movie recommendations**.

---

# 🧠 Machine Learning Concept

### Collaborative Filtering

Collaborative filtering recommends items by finding **users with similar interests**.

### Steps in the system:

1. Load movie and rating datasets
2. Select movies watched by a user
3. Find similar users using **Pearson Correlation**
4. Calculate **similarity scores**
5. Compute **weighted movie ratings**
6. Rank movies by recommendation score
7. Display **Top 10 recommended movies**

---

# 📂 Project Structure

```
movie-recommender-system
│
├── dataset
│   ├── movies.csv
│   └── ratings.csv
│
├── movie_recommender.ipynb
├── recommender.py
├── requirements.txt
└── README.md



