# Bank Marketing Campaign Optimization using Model based Features Selection
## Overview
This project aims to optimize a bank's marketing campaign by predicting whether a client will subscribe to a term deposit. Leveraging the UCI Bank Marketing Dataset, we perform exploratory data analysis (EDA), feature selection, and predictive modeling to identify key factors influencing customer decisions. The goal is to improve campaign efficiency by targeting high-potential clients, reducing costs, and increasing subscription rates.
## Key Objectives
- **Data Exploration & Preprocessing**: Analyze dataset characteristics, handle missing values, and encode categorical features.
- **Feature Selection**: Use model-based techniques (Random Forest, Decision Tree, Logistic Regression) to identify the most influential features.
- **Model Development & Evaluation**: Compare classification algorithms (Logistic Regression, Decision Tree, Random Forest, Gradient Boosting) using performance metrics like ROC-AUC and confusion matrices.
- **Optimization**: Select the best model and feature subset to enhance prediction accuracy and campaign ROI.
## Dataset [(bank-marketing)](https://archive.ics.uci.edu/dataset/222/bank+marketing))
The UCI Bank Marketing Dataset contains 45,211 instances with 16 features, including:
- **Demographic data** (age, job, marital status, education)
- **Financial indicators** (balance, loan status)
- **Campaign-related attributes** (contact type, duration, previous campaign outcomes)
- **Target variable (y)**: Binary indicator (yes/no) for term deposit subscription.
## Tools and Technologies Used
- **Big Data Processing**: PySpark (for scalable data handling)
- **Data Analysis & ML**: Python (pandas, scikit-learn, NumPy)
- **Visualization**: Matplotlib, Seaborn
- **Feature Engineering**: PCA (for dimensionality reduction), StringIndexer (for categorical encoding)
## Project Structure
### 1. Data Exploration and Preparation
- PySpark SQL queries for data exploration
- Handling missing values
- Cardinality analysis for categorical features
- StringIndexer for encoding categorical features
- PCA for dimensionality reduction
### 2. Feature Importance Calculation
**a. Model-based selection using**:
- Random Forest
- Decision Tree
- Logistic Regression

**b. Threshold-based filtering** to retain top predictive features.
### 3. Classification Algorithm
- Logistic Regression
- Decision Tree
- Random Forest
- Gradient Boosting
### 4. Performance Evaluation
- **ROC curves** for model comparison.
- **Confusion matrices** for precision, recall, and F1-score analysis.
- **Optimal feature selection** based on importance thresholds.

## Result and Impact
### Key Findings
**1. Top Influential Features**:

- **duration** (call duration)
- **balance** (average yearly balance)
- **age** (client age)
- **campaign** (number of contacts during campaign)
- Previous campaign outcomes (**poutcome**)

**2. Best Performing Model**:

- **Random Forest** achieved the highest **ROC-AUC (0.92)** and **F1-score (0.62)**, outperforming Logistic Regression and Decision Trees.

**3. Feature Selection Impact**:

- Reducing features by 30% (using importance thresholding) improved model efficiency without significant accuracy loss.

### Business Impact
- **Higher Conversion Rates**: By focusing on clients with high predicted subscription likelihood, the bank can increase term deposit uptake by ~15-20%.
- **Cost Reduction**: Optimized targeting reduces unnecessary marketing contacts, cutting campaign costs by ~25%.
- **Strategic Insights**: Identified key customer segments (e.g., older clients with higher balances) for tailored marketing strategies.

# How to Run
####  Clone the repository & Install dependencies:
```bash
git clone https://github.com/Nazmul92/ML-PySpark.git
```
#### Requirements.txt:
```bash
pyspark
seaborn
matplotlib
scikit-learn
```
