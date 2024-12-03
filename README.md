# Bank Marketing Campaign Optimization using Model based Features Selection
## Overview
This project focuses on optimizing a bank's marketing campaign by predicting whether a client will subscribe to a term deposit. It leverages the UCI Bank Marketing Dataset to perform data exploration, feature selection, and model evaluation using Python Spark (PySpark), Scikit-learn, Pandas, NumPy. The goal is to build an efficient model by selecting important features and applying various classification algorithms.
## Dataset [(bank-marketing)](https://archive.ics.uci.edu/dataset/222/bank+marketing))
The dataset contains 45,211 instances and 16 features, including both categorical and numerical attributes related to a Portuguese bank's marketing campaign. The task is to predict if a client will subscribe to a term deposit (target variable 'y').
## Tools and Technologies Used
- PySpark for big data processing
- Python Libraries: pandas, scikit-learn, matplotlib, seaborn for data analysis and machine learning
- Visualization: Matplotlib, Seaborn for creating informative visualizations
## Project Structure
### 1. Data Exploration and Preparation
- PySpark SQL queries for data exploration
- Handling missing values
- Cardinality analysis for categorical features
- StringIndexer for encoding categorical features
- PCA for dimensionality reduction
### 2. Feature Importance Calculation
- Use Random Forest, Decision Tree, and Logistic Regression for feature importance
- Apply threshold-based feature selection
### 3. Classification Algorithm
- Logistic Regression
- Decision Tree
- Random Forest
- Gradient Boosting
### 4. Performance Evaluation
- ROC curve for algorithm comparison
- Confusion matrices for performance analysis
- Selection of optimal features based on thresholding

# How to Run
####  Clone the repository & Install dependencies:
```bash
git clone https://github.com/Nazmul92/ML-PySpark.git

pip install pyspark
pip install seaborn
pip install matplotlib
