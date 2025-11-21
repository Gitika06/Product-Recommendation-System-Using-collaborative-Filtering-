#Product Recommendation System (Item–Item Collaborative Filtering)
This project builds a basic product recommendation engine using item–item collaborative filtering.  
It demonstrates my ability to work with user behavior data, create similarity-based models, and design an end-to-end data pipeline for identifying products that are most similar or frequently co-rated by users.

---

## Project Objective
To recommend the top-N similar products for any given product by analyzing user–item interactions.  
The model uses historical rating patterns to identify items that tend to be liked by similar users.

---

## Dataset
A small sample dataset (`Reviews_sample.csv`) is included for demonstration.  
It contains:
- User IDs  
- Product IDs  
- Ratings  
- Basic metadata  

The dataset reflects typical challenges in recommendation tasks such as sparsity and variable rating behavior.

---

## End-to-End Workflow
### **1. Data Preparation**
- Loading user–item rating data  
- Handling missing values  
- Creating a cleaned interaction matrix  
- Building a pivot table (rows: users, columns: products)  

### **2. Constructing User–Item Matrix**
A sparse matrix is generated where each cell represents a user's rating for a product.  
This is used for similarity computations.

### **3. Similarity Computation**
- Item–item similarity is calculated using **cosine similarity**  
- Similarity matrix is used to identify products with the highest similarity scores  

### **4. Recommendation Generation**
- For a given product, retrieve top-N similar products  
- Filter out items with insufficient interaction  
- Provide ranked recommendations  

### **5. Evaluation**
- Exploratory checks on similarity values  
- Manual validation of sample recommendations  
This project focuses on demonstrating conceptual clarity, not accuracy benchmarking.

---

## Project Structure
├── Product_recommendation_collab_filtering.ipynb
├── Reviews_sample.csv
└── README.md

---

## Technologies & Skills Demonstrated

### **Languages & Libraries**
- Python  
- Pandas  
- NumPy  
- Scikit-Learn  
- Google Colab  

### **Core Data Skills**
- Working with sparse matrices  
- Data preprocessing  
- Similarity computation  
- Analytical reasoning  
- Building reusable functions  
- Interpreting model outputs  

---

## How to Run This Project
1. Clone this repository  
2. Install required Python libraries  
3. Open the notebook in Jupyter  
4. Run all cells sequentially
