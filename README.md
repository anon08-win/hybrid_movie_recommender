# Hybrid Movie Recommendation System
**Collaborative Filtering | Matrix Factorization | Evaluation | Python**

## 🎯 Objective

Develop a movie recommendation system using the MovieLens dataset.
The goal is to compare multiple recommender techniques and evaluate
their performance from a practical data science perspective.

This project simulates a real-world analytics assignment.

## 📊 Dataset Used

- MovieLens 100K dataset
- User-Item ratings
- Movie metadata (genres, titles)

## 📌 Methods Implemented

1️⃣ Popularity-based Recommendation  
2️⃣ User-User Collaborative Filtering  
3️⃣ Matrix Factorization (SVD)

## 📈 Evaluation Strategy

Models were evaluated using RMSE and ranking metrics.  
Performance comparison helps determine which model best fits user preferences.

## 🛠 Tools Used

- Python  
- Pandas, Numpy  
- Surprise (SVD model)  
- Scikit-Learn  
- Matplotlib / Seaborn

## 📁 Folder Structure

- notebooks/ – Notebook with full modeling pipeline
- data/ – MovieLens dataset files
- scripts/ – Supporting Python scripts
- results/ – Visualizations & metrics


## 💡 Results & Insights

- Popularity model offers fast but generic recommendations  
- Collaborative Filtering captures individual preferences  
- SVD performs better on RMSE and personalized ranking  
- Recommendation quality improves when hybridized

## 🔍 Future Scope

- Add content-based features
- Optimize for top-N recommendation
- Deploy as Flask/Streamlit app

## 👤 Author

**Aishwary Pratap Singh**  
Aspiring Machine Learning Enthusiast