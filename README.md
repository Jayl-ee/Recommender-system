# Recommender-system

Data : Anime Recommendation Database 2020 
[ https://www.kaggle.com/hernan4444/anime-recommendation-database-2020 ]

## Content Based Filtering 

Content based filtering is a method that uses similariteis in feature to make decisions

[Process]
  1. Create Item profile
 * Item profile is a dataframe which has ID of a certain object as row, and features describing the object as columns
  2. Embedding columns
 * In order to compare the significance of IDs
  3. Use cosine similarity to compare each items
  
  
## Latent Factor Model & Matrix Factorization

-> Latent factor model uses Dimensionality Reduction on user-item matrix to find the latent factor

We use SVD ( Singular Vector Decomposition ) on User-item matrix to avoid sparsity.
  
-> Matrix factorization is a class of collaborative filtering algorithm. This improves SVD

## Factorization machine

This is a supervised algorithm that can be used for classification, regression, and ranking tasks

## Wide & Deep

This is a ranking recommendation algorithm presented from Google. 
Read the Paper in this LINK : https://arxiv.org/pdf/1606.07792.pdf
