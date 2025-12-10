# K-Drama Recommendation System (Content-Based Filtering)

## Overview

This project implements a content-based recommendation system that suggests new K-Dramas based on viewing history. It utilizes **TF-IDF (Term Frequency-Inverse Document Frequency)** to quantify the features of each drama (Genre, Synopsis, Cast, Tags) and **Cosine Similarity** to find the dramas whose feature vectors are most similar to the user's aggregated preference vector.

## Key Features

* **Multi-Feature Combination:** Features (Genre, Synopsis, Cast, and Tags) for each drama.
* **Cosine Similarity Ranking:** Ranks all available dramas by their similarity to the user's Super-Vector.
* **Watched Drama Filtering:** Automatically excludes dramas already watched from the final recommendation list.

## 🛠️ Requirements

The project was constructed inside google colab and using the following libraries:
* `pandas`
* `numpy`
* `scikit-learn` (`sklearn`)

This project uses the dataset [Top 250 Korean Dramas from 'kaggle.com'](https://www.kaggle.com/datasets/ahbab911/top-250-korean-dramas-kdrama-dataset)

