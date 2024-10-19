# Bangalore Property Price Prediction

This project focuses on predicting property prices in Bangalore using various regression models. The goal is to analyze the dataset, build models, and identify the best-performing model for accurate price predictions.

## Table of Contents

1. [Overview](#overview)
2. [Project Goals](#project-goals)
3. [Data Description](#data-description)
4. [Methods](#methods)
   - [1. Data Preprocessing](#1-data-preprocessing)
   - [2. Model Training and Evaluation](#2-model-training-and-evaluation)
5. [Best Model](#best-model)
6. [Technologies Used](#technologies-used)


## Overview

Bangalore's real estate market has seen significant growth in recent years. This project aims to leverage historical property data to develop a regression model that can predict property prices based on various features such as location, size, and number of bedrooms.

## Project Goals

- To analyze the factors influencing property prices in Bangalore.
- To develop and evaluate multiple regression models.
- To identify the best model for predicting property prices accurately.

## Data Description

The dataset used for this project includes various features related to property listings in Bangalore, such as:

- Location
- Size (in square feet)
- Number of bedrooms
- Number of bathrooms
- Amenities (e.g., parking, security)
- Age of the property
- Price (target variable)

## Methods

### 1. Data Preprocessing

- Cleaned the dataset by handling missing values and outliers.
- Converted categorical variables into numerical formats using techniques like one-hot encoding.
- Scaled numerical features to improve model performance.

### 2. Model Training and Evaluation

- Split the dataset into training and testing sets.
- Trained several regression models, including:
  - Linear Regression
  - Decision Tree Regression
  - Lasso
- Evaluated model performance using accuracy.

## Best Model

After comparing the performance of various regression models, the **Linear Regression** model was found to be the best fit for the dataset, achieving the highest accuracy. This model effectively captured the non-linear relationships in the data and provided accurate predictions of property prices.

## Technologies Used

- Python
- Pandas (Data manipulation)
- NumPy (Numerical computing)
- Scikit-learn (Machine learning)
- Matplotlib, Seaborn (Data visualization)

