# TikTok Claim Status Classification

## Project Overview

This project is part of the Google Advanced Data Analytics Certificate and focuses on classifying TikTok claim statuses using machine learning techniques. The goal is to develop a model that can accurately predict the claim status based on various features extracted from the data.

## Table of Contents

- [Introduction](#introduction)
- [Data](#data)
- [Methodology](#methodology)
- [Modeling](#modeling)
- [Results](#results)
- [Conclusion](#conclusion)
- [Future Work](#future-work)

## Introduction

In the realm of social media, managing claims and content moderation is crucial. This project aims to automate the classification of claim statuses on TikTok using machine learning models. The project includes data preprocessing, feature engineering, model training, evaluation, and interpretation of results.

## Data

The dataset used for this project consists of TikTok claim records with various features. The data includes the following columns:

- `video_id`: Unique identifier for each video
- `video_like_count`: Number of likes the video received
- `video_comment_count`: Number of comments on the video
- `claim_status`: Status of the claim (e.g., 'claim', 'opinion')
- `video_viewcount`: Number of views by video

The dataset was preprocessed to handle missing values, outliers, and to perform feature engineering.

## Methodology

1. **Data Preprocessing**: 
   - Handling missing values
   - Removing or capping outliers
   - Encoding categorical variables

2. **Feature Engineering**:
   - Creating new features based on domain knowledge
   - Normalizing numerical features

3. **Modeling**:
   - Splitting the data into training , validating and test sets
   - Training multiple machine learning models (e.g., Logistic Regression, Random Forest, XGBoost)
   - Hyperparameter tuning using Grid Search or Random Search

4. **Evaluation**:
   - Evaluating model performance using metrics such as accuracy, precision, recall, and F1-score
   - Comparing different models and selecting the best one

## Results

The best-performing model was Random forest , which achieved an Recall score of near perfect on the test set. 

The model was able to correctly classify the claim statuses with a high degree of Recall.

## Conclusion

This project successfully demonstrated the use of machine learning techniques to classify TikTok claim statuses. The results indicate that Random Forest is an effective model for this task. This automated classification can help in efficiently managing claims on the platform.

## Future Work

- Exploring advanced feature engineering techniques
- Incorporating additional data sources for better model performance
- Experimenting with deep learning models for improved accuracy
- Implementing the model in a real-time environment for automated claim classification


