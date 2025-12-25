# 🎬 Movie Recommendation System

A hybrid movie recommendation system built using **content-based filtering** and **collaborative filtering (SVD)**.  
This project analyzes movie metadata, genres, keywords, cast, crew, and user ratings to recommend similar movies.

---

##  Features

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

##  How the system works

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

##  Tech Stack

| Component | Technology |
|----------|------------|
| Language | Python |
| Recommendation | Surprise SVD, TF-IDF, CountVectorizer |
| ML Libraries | scikit-learn, pandas, numpy |
| Similarity | Cosine similarity |
| Development | Jupyter Notebook |

---
Installation

## 1.Clone repository
```bash
git clone https://github.com/Harika2545/Movie-Recommendation-System.git
cd Movie-Recommendation-System

## 2.Create environemnt
conda create -n movie_env python=3.10
conda activate movie_env

## 3.Install dependencies
pip install pandas numpy scikit-surprise scikit-learn notebook

## 4.Run Jupyter Notebook
jupyter notebook

## Run the notebook
Movie-recommendation-System.ipynb

## Outputs:
Movie input: Avatar
Top recommendations:
• John Carter
• Guardians of the Galaxy
• Jupiter Ascending
• Star Trek
• Star Wars: The Force Awakens





