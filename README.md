# 🎬 Hybrid Movie Recommendation System

This project implements a **hybrid movie recommendation system** using the MovieLens dataset.  
It combines **popularity-based**, **content-based**, and **collaborative filtering (SVD)** approaches into a single weighted ensemble and evaluates performance using ranking-based metrics.

## 🔍 Key Features
- MovieLens Small dataset (automatic download & preprocessing)
- User–item sparse matrix construction
- Popularity-based recommender with Bayesian weighted ratings
- Content-based filtering using genre similarity (cosine similarity)
- Collaborative filtering via matrix factorization (SVD)
- Hybrid recommendation system with configurable weights
- Ranking-based evaluation: Precision@K, Recall@K, NDCG@K
- Cold-start handling for new users and movies

## 🛠️ Tech Stack
- Python
- NumPy, Pandas
- SciPy (Sparse matrices & SVD)
- Scikit-learn
- Matplotlib / Seaborn

## ⚙️ Methodology
1. Data loading, filtering, and sparsity analysis  
2. Train/validation/test split (user-wise)
3. Independent training of:
   - Popularity model
   - Content-based model
   - Matrix factorization model
4. Hybrid ensemble using weighted score aggregation
5. Evaluation using ranking metrics instead of RMSE

## 📂 File
- `Movie Recommendation System.ipynb` – Complete end-to-end implementation

## 🚀 How to Run
1. Open the notebook in Google Colab or Jupyter
2. Run all cells — dataset downloads automatically
3. View evaluation metrics and sample recommendations

## 📈 Output
- Top-K personalized movie recommendations
- Precision@10, Recall@10, and NDCG@10 scores
- Example recommendations with movie titles

## 📌 Future Improvements
- Neural collaborative filtering
- Learning hybrid weights automatically
- Web-based deployment (Streamlit / Flask)
- Temporal dynamics and user profiling

## 👤 Author
Prashant Verma  
B.Tech Electrical Engineering, IIT Kanpur  
Interests: Machine Learning, Recommender Systems, Core EE
