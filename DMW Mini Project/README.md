# Document Clustering with Text Mining

This project explores the use of **unsupervised machine learning** techniques to analyze, cluster, and extract meaningful insights from large collections of unstructured text data. The goal is to organize documents into meaningful groups based on content using text mining and clustering algorithms.

---

## Problem Statement

Unstructured text data—such as research papers, reviews, or articles—lacks inherent organization, making analysis and retrieval difficult. This project addresses the challenge of clustering these documents based on their semantic similarity using:

- Text preprocessing and cleaning
- Feature extraction (TF-IDF)
- Clustering algorithms like **K-Means**, **Hierarchical Clustering**, and **DBSCAN**

---

## Objectives

- Preprocess raw text data for consistency
- Extract meaningful features using TF-IDF
- Cluster documents based on similarity
- Evaluate cluster quality with Silhouette Score, Davies-Bouldin Index, etc.
- Visualize clusters using PCA or t-SNE

---

## Dataset

- **Source**: Kaggle – 20 Newsgroups dataset  
- **Records**: ~18,000 documents  
- **Attributes**:
  - `Text` – Raw text
  - `Processed_text` – Cleaned version for analysis
  - `Subject` – Email subject lines
  - `Label` – Category label (used only for validation)

---

## Preprocessing Steps

- Removing stopwords, punctuation, and special characters
- Lowercasing and lemmatization
- Handling missing values and duplicates
- Text vectorization using **TF-IDF**

---

## Exploratory Data Analysis

- Descriptive stats (word counts, doc length)
- Class distribution visualization
- Word clouds and N-gram analysis
- Correlation between document features and cluster structure

---

## Models Used

| Algorithm | Purpose | Evaluation |
|-----------|---------|------------|
| **K-Means** | Base clustering algorithm | Silhouette Score, Elbow Method |
| **Hierarchical Clustering** | Captures hierarchical relationships | Dendrograms |
| **DBSCAN** | Detects dense regions and outliers | Cluster noise, compactness |

---

## Evaluation Metrics

- **Silhouette Score**
- **Davies-Bouldin Index**
- **Visualizations**: PCA, t-SNE plots

---

## Insights

- Clusters successfully represent topic-based groupings (e.g., sports, science, religion)
- Document vectors (TF-IDF) allow semantic comparison
- Outlier detection helps flag irrelevant/noisy documents

---

## Tech Stack

- Python
- pandas
- scikit-learn
- NLTK
- Matplotlib & Seaborn
- WordCloud
- t-SNE / PCA

---

## What I Learned

- Applied end-to-end NLP pipeline on unstructured data
- Compared unsupervised clustering algorithms
- Understood limitations of unsupervised evaluation
- Visualized high-dimensional text data meaningfully

---

## Contributors

- Sinchana Suresh Ganiga  
- S Manmohan Reddy  
- Sadineni Aasritha  
- N. Chethan  

Instructor: **Dr. Neeba E A**  
Department of CSE (Data Analytics), Alliance University

---

> “Turning raw text into clusters of meaning — one document at a time.”

