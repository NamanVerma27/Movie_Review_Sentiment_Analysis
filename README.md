# Movie Review Sentiment Analysis

## Overview

This project focuses on sentiment analysis of IMDb movie reviews, where the goal is to classify reviews as **positive**, **negative**, or **neutral** based on the textual content. Multiple machine learning models were employed, and their performances were compared based on several metrics such as accuracy, precision, recall, and F1-score.

The following models were evaluated:
- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier
- AdaBoost Classifier

## Project Structure


## Dataset

The dataset consists of 150,000 IMDb movie reviews, along with the corresponding ratings (from 1 to 10). For the purpose of classification:
- Ratings 1-4 are categorized as **negative**.
- Ratings 5-6 are categorized as **neutral**.
- Ratings 7-10 are categorized as **positive**.

The dataset was preprocessed to clean the text, remove stopwords, and balance the classes.

## Models and Techniques

### 1. Logistic Regression
- **Accuracy**: 88%
- Logistic Regression was used as the baseline model, providing fast computation and interpretability for linear relationships.

### 2. Decision Tree Classifier
- **Accuracy**: 68%
- This model provided quick insights but struggled with overfitting, particularly on non-linear features.

### 3. Random Forest Classifier
- **Accuracy**: 84%
- This ensemble method improved upon the Decision Tree, reducing overfitting and providing feature importance.

### 4. AdaBoost Classifier
- **Accuracy**: 82%
- AdaBoost focused on misclassified instances and boosted weak learners, balancing accuracy with robustness.
