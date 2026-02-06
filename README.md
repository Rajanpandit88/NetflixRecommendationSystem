# 🎬 Netflix Content Clustering & Recommendation System Using NLP and Unsupervised Learning

## 📌 Project Overview

This project builds a **content-based recommendation system** for
Netflix titles using **Natural Language Processing (NLP)** and
**Unsupervised Machine Learning**.\
Instead of relying on user ratings or watch history, the system
understands the **semantic meaning** of movies and TV shows using
textual metadata such as title, cast, director, genres, and description.

The project addresses the problem of **choice paralysis** by grouping
similar content and recommending relevant titles automatically.

------------------------------------------------------------------------

## 🎯 Objectives

-   Analyze Netflix dataset for content patterns
-   Create a unified textual representation ("bag of content")
-   Apply NLP techniques for text cleaning and normalization
-   Convert text into numerical vectors using TF-IDF
-   Reduce dimensionality using SVD
-   Perform clustering using KMeans
-   Build a cosine similarity--based recommendation engine

------------------------------------------------------------------------

## 🧠 Technologies Used

-   Python
-   Pandas, NumPy
-   NLTK (Text Processing)
-   Scikit-learn (TF-IDF, SVD, KMeans, Cosine Similarity)
-   Matplotlib, Seaborn (Visualization)
-   Google Colab

------------------------------------------------------------------------

## 📂 Dataset

Netflix Movies and TV Shows Dataset (7,000+ titles)

------------------------------------------------------------------------

## ⚙️ How the System Works

1.  Combine textual columns into one content field
2.  Clean and preprocess text using NLP
3.  Convert text into TF-IDF vectors
4.  Apply SVD for dimensionality reduction
5.  Cluster similar content using KMeans
6.  Recommend similar titles using cosine similarity

------------------------------------------------------------------------

## ▶️ How to Run the Project in Google Colab

1.  Upload the dataset (`netflix_titles.csv`)
2.  Run the notebook cells step-by-step
3.  Use the recommendation function by entering a movie name

------------------------------------------------------------------------

## 📈 Business Impact

-   Improved content discovery
-   No dependency on user data (privacy-friendly)
-   Solves cold-start problem
-   Better utilization of long-tail content

------------------------------------------------------------------------

## 📁 Project Structure

    Netflix-Recommendation-System/
    │
    ├── netflix_titles.csv
    ├── Netflix_Clustering_Recommendation.ipynb
    ├── README.md

------------------------------------------------------------------------

## ✅ Output

The system clusters Netflix titles into meaningful groups and recommends
similar movies/shows based on semantic similarity.

Example: \> If you like **3 Idiots**, the system recommends **PK**,
**Rang De Basanti**, etc.

------------------------------------------------------------------------

## 👨‍💻 Author

Rajan Pandit
