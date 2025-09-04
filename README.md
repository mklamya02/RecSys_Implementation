# 🎬 AI-Driven Recommender Systems on MovieLens Dataset  

## 📝 Description  
This repository contains a collection of Jupyter notebooks implementing and comparing different recommender system architectures using the **MovieLens ML-Latest-Small dataset**.  
The goal is to cover a wide range of approaches—from classical methods to modern AI-driven techniques including deep learning and graph neural networks—to analyze their performance and limitations.  

---

## 📂 Repository Content  

### 🔹 Content-Based Filtering (CBF)  
- Bag-of-Words (BoW)  
- Binary Feature Metrics  
- TF-IDF with Cosine Similarity  
- **Interactive CBF**: the user can input a movie title (correct or misspelled). Using **FuzzyWuzzy**, the system automatically matches it with the closest title in the dataset and returns the **top-10 most similar movies**.  

---

### 🔹 Collaborative Filtering (CF)  
- **SVD** (Singular Value Decomposition)  
- **SVD++**  
- **NMF** (Non-Negative Matrix Factorization)  
- **ALS** (Alternating Least Squares)  
- **AutoRec** (Autoencoder for Recommendations)  

---

### 🔹 Graph-Based Recommendation  
- **GCMC** (Graph Convolutional Matrix Completion)  
- **IGMC** (Inductive Graph-based Matrix Completion)  
- **LightGCN** (Light Graph Convolutional Network)  

---

### 🔹 Deep Learning-Based Recommendation  
- **Content-Based CNN** applied to movie features.  
- **Neural Collaborative Filtering (NCF):**  
  - User and item embeddings  
  - Multi-Layer Perceptron (MLP)  
  - Final fusion layer producing the complete NCF model  

---

## 📚 Dataset  
All experiments are based on the **MovieLens ML-Latest-Small dataset**, which contains user–movie ratings and metadata.  
You can download it here: [MovieLens Dataset](https://grouplens.org/datasets/movielens/latest/)  

---

## 🚀 Getting Started  
 Clone this repository:  
   ```bash
   git clone https://github.com/mklamya02/RecSys_Implementation.git
