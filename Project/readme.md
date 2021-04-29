# Introduction
# Santander Product Recommendation System
Our goal is to implement a product recommendation system based on user personalization and item-similarity, to help banks improve customer acquisition and revenue on products by better marketing techniques.

# Dataset
For this, we utilized the Santander Product Recommendation dataset which is available on Kaggle. 


Link - https://www.kaggle.com/c/santander-product-recommendation/data

The dataset contains 1.5 years of Spain customers behavior data from Santander bank to predict what new products customers will purchase. The data starts at 2015-01-28 and has monthly records of products a customer has, such as "credit card", "savings account", etc. Our goal is to recommend products based on customer interactions. The dataset contains around 200K rows and 49 columns.

# Algorithms
## User-Personalization recipe
Predicts items a user will interact with and performs exploration on cold items. Based on Hierarchical Recurrent Neural Networks which model the temporal order of user-item interactions.
Item-to-item similarities (SIMS)

Computes items similar to a given item based on co-occurrence of items in the user-item interactions dataset. 

