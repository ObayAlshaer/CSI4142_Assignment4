# CSI4142 - Fundamentals of Data Science
## Assignment 4: Recommendation Systems
### Group Information
**Group Number:** 39  
**Members:** Mohamed-Obay Alshaer (300170489), Samih Karroum (300188957)  
**Course:** CSI4142 - Fundamentals of Data Science  
**Instructor:** Caroline Barrière  
**Term:** Winter 2025  
**Submission Date:** April 10, 2025  
---
## About This Repository
This repository contains our submission for Assignment 4 of CSI4142 - Fundamentals of Data Science. The focus of this assignment is **Recommendation Systems**, specifically:
- Study 1: Similarity measures on various attributes
- Study 2: Clustering algorithms (KMeans and DBSCAN)
- Study 3: Content-Based Recommendation System
- Study 4: Collaborative Filtering Recommendation System

The assignment is implemented entirely in **Python** and documented using **Jupyter Notebooks** to ensure transparency, reproducibility, and clarity in our analysis.
---
## Repository Structure
This repository consists of four branches:
1. **Main**: Contains only this README file.
2. **study1**: Contains the Jupyter Notebook for similarity measures analysis.
3. **study2**: Contains the Jupyter Notebook for clustering algorithms.
4. **study3**: Contains the Jupyter Notebook for content-based recommendation systems.
5. **study4**: Contains the Jupyter Notebook for collaborative filtering recommendation systems.

Each study and its respective implementation are thoroughly explained within their respective Jupyter Notebooks.
---
## Dataset Information
### Selected Dataset
We chose [DATASET_NAME] for this assignment. The dataset contains:
- [Brief description of the dataset]
- [Mention the two main files: one for metadata and one for ratings]
- [Explain why you chose this dataset]

**Source:** [Link to dataset]
---
## Studies Overview

### Study 1: Similarity Measures
- Implementation of at least 3 different similarity measures (e.g., Jaccard, Hamming, Cosine, Euclidian, Manhattan)
- Additional exploration of a text-based similarity measure
- Simulation of 5 requests to demonstrate each similarity measure with Top 10 results

### Study 2: Clustering Algorithms
- Implementation of KMeans and DBSCAN clustering algorithms
- Testing different parameter variations for each algorithm
- Visual inspection of clustering results using 2 different attribute combinations
- Analysis of which clustering algorithm performs better based on visual inspection

### Study 3: Content-Based Recommendation System
- Development of 2 different similarity heuristics using feature subsets
- Implementation of a content-based recommendation system using these heuristics
- Simulation of 3 requests with Top 10 recommendations for each heuristic
- Qualitative comparison of the results from different heuristics

### Study 4: Collaborative Filtering Recommendation System
- Building a utility matrix (Rui) from user ratings
- Matrix Factorization to decompose the Rui matrix into P and Q matrices
- Testing with different latent dimensions
- Simulation of 3 requests for user recommendations
- Quantitative evaluation using a 10% held-out dataset as Gold Standard
- Implementation of evaluation metrics (MSE, P@5, P@10, MRR)
---
## Instructions for Running the Code
1. Clone the repository:
```bash
git clone https://github.com/ObayAlshaer/CSI4142_Assignment4
cd CSI4142_Assignment4
```
2. Checkout the branch you want to work with:
```bash
git checkout study1  # For Similarity Measures
git checkout study2  # For Clustering Algorithms
git checkout study3  # For Content-Based Recommendation
git checkout study4  # For Collaborative Filtering
```
3. Open Jupyter Notebook:
```bash
jupyter notebook
```
4. Navigate to the corresponding notebook and run the cells sequentially.
---
## Acknowledgment
This assignment was completed as part of the CSI4142 - Fundamentals of Data Science course under the guidance of **Professor Caroline Barrière** at the **University of Ottawa**.
---
## Contact
For any questions or clarifications, please reach out via email:  
malsh094@uottawa.ca  
skarr026@uottawa.ca
---
**Mohamed-Obay Alshaer & Samih Karroum**  
**Winter 2025**
