# 🎵 Predicting Song Popularity Across Digital Platforms

## An SVM Approach Using Spotify Audio Features

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.10-blue?logo=python">
  <img src="https://img.shields.io/badge/Machine%20Learning-SVM-green">
  <img src="https://img.shields.io/badge/Dataset-Spotify-brightgreen">
  <img src="https://img.shields.io/badge/Accuracy-98.19%25-success">
  <img src="https://img.shields.io/badge/Data%20Analysis-EDA-orange">
  <img src="https://img.shields.io/badge/Visualization-Matplotlib-yellow">
  <img src="https://img.shields.io/badge/Libraries-Scikit--Learn-red">
  <img src="https://img.shields.io/badge/Status-Completed-success">
</p>

-Overview
This project explores how machine learning can be used to predict song popularity using Spotify audio features. By leveraging the Support Vector Machine (SVM) algorithm, the model classifies songs into high popularity and low popularity categories based on characteristics such as energy, tempo, danceability, acousticness, and valence.

The research demonstrates how audio-based features can provide strong predictive insights into listener preferences and music popularity trends on digital streaming platforms like Spotify.

-Project Objectives
- Analyze the relationship between Spotify audio features and song popularity
- Build a machine learning classification model using SVM.
- Evaluate model performance using standard classification metrics.
- Provide insights for music recommendation systems, marketing strategies, and trend analysis.

-Dataset

| Information | Details |
|---|---|
| Dataset Name | Spotify Music Dataset |
| Source | Kaggle |
| Total Records | 4,831 Songs |
| Popular Songs | 3,145 |
| Unpopular Songs | 1,686 |
| Data Type | Audio Features & Metadata |
| Features Used | Energy, Tempo, Danceability, Valence, Acousticness, Speechiness |
| Target Variable | Song Popularity Classification |
| Dataset Link | https://www.kaggle.com/datasets/solomonameh/spotify-music-dataset/data |

-Machine Learning Approach
Algorithm: Support Vector Machine (SVM)

-Workflow
1. Data Collection
2. Data Cleaning
3. Feature Engineering
4. Data Transformation & Scaling
5. Train-Test Split (80:20)
6. Model Training
7. Model Evaluation

-Libraries Used
1. pandas
2. numpy
3. scikit-learn
4. matplotlib
5. seaborn

-Data Preprocessing

The preprocessing stage included:

- Handling missing values using dropna()
- Feature normalization
- Date transformation
- Feature engineering
- Encoding and scaling numerical features

Additional engineered features:

- Energy-to-danceability ratio
- Valence-energy interaction
- Song age calculation

-Model Performance
Confusion Matrix
