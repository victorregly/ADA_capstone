# ADA_capstone
Advanced Data Analysis Capstone project


# Music Streaming and Track Genre Prediction

**University of Lausanne, HEC Lausanne**

**Advanced Data Analysis**  
**Professor: S. Scheidegger**  
**TAs: Anna Smirnova, Maria Pia Lombardo**  
**Author: Victor Regly**  
**Date: August 30, 2024**

## Abstract

This project explores machine learning models to predict music genres using track features. It employs both supervised (Random Forest, XGBoost, Neural Networks) and unsupervised learning (K-Means, Hierarchical Clustering) techniques. Dimensionality reduction methods (PCA, t-SNE) aid in visualizing data. The study addresses challenges like high dimensionality and class imbalance across 114 genres.

Dataset: https://www.kaggle.com/datasets/maharshipandya/-spotify-tracks-dataset/data

## Methodology

- **Data Preprocessing:** Cleaned and normalized data from Kaggle’s Spotify dataset.
- **Supervised Learning:** Initial models include Logistic Regression, Random Forest, XGBoost, and Neural Networks.
- **Feature Engineering:** Recursive Feature Elimination (RFE) and feature importance analysis.
- **Unsupervised Learning:** K-Means and Hierarchical Clustering to identify patterns. Gaussian Mixture Models (GMM) used for soft clustering.
- **Ensemble Methods:** Stacked ensemble model integrating Neural Network, XGBoost, and Random Forest.

## Results

- **Supervised Learning:** Neural Networks achieved the highest accuracy (33.28%), followed by XGBoost (32.91%).
- **Unsupervised Learning:** K-Means showed low cluster purity; GMM improved clustering but still faced challenges.
- **Ensemble Model:** Achieved a 99.26% accuracy, indicating strong predictive capability.

## Conclusion

While models show promise in grouping tracks based on musical similarities, genre prediction remains challenging due to feature limitations. Future work may require more nuanced features or additional context to improve genre classification.

## Tools

- **Python Libraries:** pandas, NumPy, Scikit-Learn, XGBoost, TensorFlow
- **Tools:** ChatGPT-4, Advanced Data Analysis course materials, and relevant literature.

Repository contains all code, data processing steps, and results.
