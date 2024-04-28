# Project: Bank Marketing Campaign Optimization using Model based Features Selection: Exploring PySpark
## Overview
This Jupyter Notebook contains the code and analysis for optimizing a bank's marketing campaign using PySpark. The goal is to predict whether a client will subscribe to a term deposit based on various features related to direct marketing campaigns conducted by a Portuguese banking institution.
## Dataset [(bank-marketing)](https://archive.ics.uci.edu/dataset/222/bank+marketing))
The UCI Bank Marketing Dataset contains information related to direct marketing campaigns conducted by a Portuguese banking institution through phone calls. The dataset is multivariate, consisting of 45211 instances and 16 features. The goal of the classification task associated with this dataset is to predict whether a client will subscribe to a term deposit, indicated by the variable 'y'. The features in the dataset include both categorical and integer types, and the dataset is primarily used for business-related classification tasks.
# Project Structure
## 1. Data Exploration and Preparation
#### >> PySpark SQL queries for data exploration
#### >> Missing value analysis and handling
#### >> Cardinality analysis for categorical features
#### >> StringIndexer for categorical feature encoding
#### >> PCA analysis for dimensionality reduction
## 2. Feature Importance Calculation
#### >> Random Forest, Decision Tree, and Logistic Regression for feature importance
#### >> Threshold-based feature selection
## 3. Classification Algorithm
#### >> Logistic Regression
#### >> Decision Tree
#### >> Random Forest
#### >> Gradient Boosting
## 4. Performance Evaluation
#### >> ROC curves for algorithm performance comparison
#### >> Confusion matrices for detailed performance analysis
#### >> Selection of optimal features based on thresholding
## 5. Tools and Technologies Used
#### >> PySpark for big data processing
#### >> Python libraries for data analysis and machine learning
#### >> Matplotlib and Seaborn for data visualization
# Usages
####  Clone the repository & Install dependencies:
```bash
git clone https://github.com/Nazmul92/ML-PySpark.git

pip install pyspark
pip install seaborn
pip install matplotlib
