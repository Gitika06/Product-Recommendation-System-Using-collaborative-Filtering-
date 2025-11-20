📦 Product Recommendation System using Collaborative Filtering

This project builds a Product Recommendation System using user–item collaborative filtering.
The model analyzes historical user ratings to find similar users and similar products using cosine similarity, and then recommends the top items a user is most likely to purchase.

Note: Due to file size limits, the full reviews.csv dataset is not included in this repository.
You can download the complete dataset from the original source: https://www.kaggle.com/datasets/snap/amazon-fine-food-reviews

🚀 Features
Data preprocessing & building user–item rating matrix
Cosine similarity for item–item recommendations
Fetching top-N similar products
Train–test split to evaluate recommendation quality
Easy-to-understand implementation suitable for beginners

🧠 How It Works (Quick Summary)
Load user–product ratings data
Create a pivot table (rows = users, columns = items)
Replace missing values with zero
Use cosine similarity to compute similarity between products
For a given product, return top 10 most similar products
Split the data into train/test for evaluating recommendation accuracy

📊 Technologies Used
Python
Pandas
NumPy
Scikit-Learn (cosine similarity)
Google Colab

📘 How to Use
Clone the repository
Add your reviews.csv (or a smaller sample file) into the repository
Open the notebook in Colab
Run each cell to generate recommendations

📁 Dataset Source
Amazon Review Dataset – Nick McAuley (UCSD)
(Available publicly for research use)

👩‍💻 Author
Gitika Jain
Data Analyst | Data Scientist | SQL | Python | Machine Learning
