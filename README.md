# Unsupervised-Topic-Modeling-on-Customer-Reviews-using-BERTopic-UMAP-and-CountVectorizer
This project explores **unsupervised topic modeling** on customer reviews using **BERTopic**, a cutting-edge NLP library built on top of BERT embeddings and clustering algorithms. It helps in understanding latent topics in customer feedback without requiring any labeled data.
---

##  Objective

To extract key topics from unstructured customer review data using BERTopic and visualize the structure of the topics using dimensionality reduction and class-based TF-IDF techniques.

---

##  Tools & Technologies

| Task                          | Tool / Library         |
|-------------------------------|------------------------|
| Embeddings                    | BERT (via BERTopic)    |
| Dimensionality Reduction      | UMAP                   |
| Vectorization                 | CountVectorizer        |
| Clustering                    | HDBSCAN                |
| Topic Modeling                | BERTopic               |
| Visualization                 | BERTopic (interactive) |
| Data Manipulation             | pandas, NumPy          |

---

##  Workflow Overview

1. **Data Preprocessing**
   - Cleaned raw customer reviews
   - Removed noise, punctuation, and stopwords

2. **Topic Modeling with BERTopic**
   - Transformed reviews into BERT embeddings
   - Reduced dimensionality with UMAP
   - Clustered embeddings with HDBSCAN
   - Generated interpretable topics using CountVectorizer

3. **Visualization**
   - Topic distributions
   - Inter-topic distance map
   - Word clouds and bar plots for top keywords

---

##  Example Output

> Sample Topic:  
> **"Shipping & Delivery Delays"**  
> Keywords: `['shipping', 'late', 'delayed', 'package', 'delivery']`  
> Support: 320 reviews (approx.)

---


