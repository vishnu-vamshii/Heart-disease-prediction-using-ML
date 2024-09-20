# Heart Disease Prediction

## Overview
This project uses a heart disease dataset to predict the likelihood of heart disease using machine learning algorithms. The dataset contains clinical attributes such as age, cholesterol levels, and other factors that contribute to heart health. The primary goal is to apply different machine learning models to predict the presence of heart disease.

## Table of Contents
- [Data](#data)
- [Data Exploration](#data-exploration)
- [Data Visualization](#data-visualization)
- [Machine Learning Models](#machine-learning-models)
- [Conclusion](#conclusion)

## Data
The dataset used in this project contains 303 observations and 14 features, including one target variable (indicating the presence or absence of heart disease). There are no missing values, and the dataset is well-suited for classification tasks.

## Data Exploration
We start by exploring the dataset:
- Summary statistics (mean, std, etc.)
- Data types and structure
- Missing values check

## Data Visualization
Visualization plays a crucial role in understanding the relationships between variables. Some key visualizations include:
- Scatter plot of age vs. cholesterol levels
- Count plots of categorical features like gender and fasting blood sugar
- Crosstab analysis of age and heart disease occurrence

## Machine Learning Models
We implement several models to predict heart disease:
1. **K-Nearest Neighbors (KNN)**
2. **Decision Trees**
3. **Logistic Regression**
4. **Lasso Regression**
5. **KMeans Clustering**

The dataset is split into training and test sets for evaluation. Models are trained, normalized, and evaluated using performance metrics such as RMSE and silhouette scores for clustering models.

## Conclusion
This notebook demonstrates the entire process of predictive modeling, from data exploration to advanced machine learning techniques. The goal is to understand which model performs best for heart disease prediction and to provide insights into the contributing factors.

---

## Usage
To run the notebook, you'll need the following libraries installed:
- pandas
- seaborn
- matplotlib
- sklearn
- numpy

You can install them using pip:
```bash
pip install pandas seaborn matplotlib scikit-learn numpy

