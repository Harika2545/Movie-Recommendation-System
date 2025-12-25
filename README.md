# 🎬 Movie Recommendation System

A hybrid movie recommendation system built using **content-based filtering** and **collaborative filtering (SVD)**.  
This project analyzes movie metadata, genres, keywords, cast, crew, and user ratings to recommend similar movies.

---

## 📌 Features

✔ Content-based recommendations using metadata  
✔ Collaborative filtering using Surprise SVD  
✔ Hybrid recommender combining both systems  
✔ Movie similarity using cosine similarity  
✔ Works with **The Movies Dataset** from Kaggle  
✔ Implemented in **Python & Jupyter Notebook**

---

## 📂 Dataset

This project uses **The Movies Dataset** from Kaggle:

👉 **[Download Dataset](https://www.kaggle.com/datasets/rounakbanik/the-movies-dataset)**

> ⚠ **Note:** The dataset is too large for GitHub.  
> After downloading, place your CSV files in the project folder:
> 
---

## 🧠 How the system works

### 🔹 Content-based filtering
- Extracts **genres, cast, crew, keywords**
- Creates a unified **text "soup"**
- Vectorizes using **TF-IDF / CountVectorizer**
- Computes **cosine similarity**
- Recommends movies with similar features

### 🔹 Collaborative filtering
- Uses **user ratings** (`ratings_small.csv`)
- Trains **SVD model from Surprise**
- Predicts user preferences

---

## 🛠️ Tech Stack

| Component | Technology |
|----------|------------|
| Language | Python |
| Recommendation | Surprise SVD, TF-IDF, CountVectorizer |
| ML Libraries | scikit-learn, pandas, numpy |
| Similarity | Cosine similarity |
| Development | Jupyter Notebook |

---


