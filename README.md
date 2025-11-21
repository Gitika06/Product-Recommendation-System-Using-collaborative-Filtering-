## Product Recommendation System using Collaborative Filtering
This project builds a Product Recommendation System using user–item collaborative filtering.  
The model analyzes historical user ratings to find similar users and similar products using cosine similarity, and then recommends the top items a user is most likely to purchase.

---

## Dataset
Note: Due to file size limits, the full `reviews.csv` dataset is not included in this repository.  
You can download the complete dataset from the original source:  
https://www.kaggle.com/datasets/snap/amazon-fine-food-reviews

---

## Features
- Data preprocessing & building a user–item rating matrix  
- Cosine similarity calculation for item–item recommendations  
- Fetching top-N similar products  
- Train–test split to evaluate recommendation quality  
- Easy-to-understand implementation using Python + Pandas + Scikit-Learn  

---

## Approach
1. Load and clean the review dataset  
2. Build user-item ratings pivot table  
3. Apply cosine similarity to compute similarity between items  
4. Build a function to recommend top-N similar products  
5. Evaluate the recommendation quality  

---

## Project Structure
├─ Product_recommendation_collab_filtering.ipynb
├─ README.md
└─ Reviews_sample.csv

---

## Technologies Used
- Python  
- Pandas  
- NumPy  
- Scikit-Learn  
- Google Colab  

---

## How to Run
1. Clone this repository  
2. Install dependencies  
3. Open Google Colab  
4. Run all cells  
