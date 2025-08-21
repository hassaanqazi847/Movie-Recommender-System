 🎬 Movie Recommender System

A simple **Movie Recommender System** built with **Python** and deployed using **Streamlit**.  
The system suggests movies similar to the one selected by the user, making it easier to discover new movies.  

This project demonstrates the use of **content-based recommendation** and how to deploy ML apps using Streamlit.

---


 Screenshot of the app:  
![App Screenshot](Capture....PNG)


---

##  Project Overview

This project shows how **recommendation systems** work using movie data.  
It uses **cosine similarity** on features like genres, cast, crew, and keywords to recommend movies that are most similar to the selected one.  

The recommender is wrapped in a **Streamlit app** for an interactive and user-friendly interface.

---

##  Features

-  Get **movie recommendations** instantly  
-  Uses **content-based filtering** with cosine similarity  
-  Interactive **Streamlit web app**  
  

---

## Project Workflow

- Data Collection & Preprocessing
   - Collected movie dataset (titles, genres, ratings, user history).
   - Cleaned data (handled missing values, normalized features).
- Feature Engineering
- Extracted features such as movie genres, keywords, cast, director, and user ratings.
- Converted text data into vectors using TF-IDF / Word2Vec / Embeddings.
- Model Building
- Implemented Content-Based Filtering (recommend movies similar to a given one).
- Implemented Collaborative Filtering (recommend based on user–user or item–item similarities).
- Optionally used Matrix Factorization / Deep Learning models to improve recommendations.
- Evaluation
- Used metrics like Precision@K, Recall@K, RMSE to evaluate performance.
- Deployment
- Built a simple Streamlit/Flask app where users can search for a movie and get recommendations instantly.ows.

---

