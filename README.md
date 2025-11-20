# Product Recommendation System using Collaborative Filtering

This project implements an Item-Based Collaborative Filtering Recommendation System.  
It uses user–item rating interactions to recommend similar products based on cosine similarity.  
The project is designed for beginners and explains each step clearly.

---

## 📘 Project Overview
- Preprocess user–item rating data  
- Build a user–item matrix  
- Compute item–item cosine similarity  
- Recommend top-N similar products  
- Train–test split to evaluate model performance  
- Built using Python, NumPy, Pandas, and Scikit-learn  

---

## 📂 Files in This Repository
- `product_recommendation.ipynb` – Google Colab notebook with full code  
- `ratings_sample.csv` – Sample dataset  
- `README.md` – Project explanation  

---

## 🚀 How It Works

### 1. Load Dataset  
We use a user–item ratings dataset to build the recommendation model.

### 2. Create a User–Item Matrix  
Rows = users  
Columns = products  
Values = ratings

### 3. Compute Cosine Similarity  
We calculate similarity between products based on user ratings.

### 4. Generate Recommendations  
For a selected product, we retrieve its top 10 most similar products.

### 5. Train–Test Split  
We split the rating matrix into train and test parts to evaluate how well the model predicts unseen ratings.

---

## 🧠 Key Concepts Used
- Collaborative Filtering  
- Cosine Similarity  
- User–Item Rating Matrix  
- Recommendation Ranking  
- Train–Test Evaluation  

---

## 📈 Output Examples
- Top 10 similar products  
- Top recommendations for a given user  
- Similarity scores  

---

## 📦 Tech Stack
- Python  
- NumPy  
- Pandas  
- Scikit-learn  

---

## 📬 Contact
For queries or suggestions:  
**Gitika Jain**  
