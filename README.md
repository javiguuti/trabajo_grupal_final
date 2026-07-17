# Adult Income Classification using Machine Learning

## Overview

This project was developed as part of the Bachelor's Degree in Data Science & Business Analytics at ESIC University.

It follows a complete supervised machine learning workflow, from exploratory data analysis and preprocessing to model development and performance evaluation.

The project includes:

- Exploratory Data Analysis (EDA)
- Data preprocessing
- Feature engineering
- Machine Learning model training
- Model comparison
- Model evaluation

Education vs Income:

<img width="1101" height="607" alt="image" src="https://github.com/user-attachments/assets/625bfe01-a0e4-42c6-ba7a-d5efb686f44b" />

## Dataset

**Adult Income Dataset (UCI Machine Learning Repository)**

- 48,842 observations
- 15 original variables
- Binary classification problem

The notebooks use relative paths so that the project can be executed on any computer without modifying the source code.

```python
df = pd.read_csv("../data/income_data.csv")
```

## Repository Contents
The repository contains a complete Exploratory Data Analysis (EDA) with more than 20 visualizations and statistical analyses. The full notebook is available for review.

### Exploratory Data Analysis (EDA)

- Missing value analysis
- Univariate analysis
- Bivariate analysis
- Multivariate analysis
- Correlation analysis
- Data visualization

### Data Preprocessing

- Missing value imputation
- Feature engineering
- Standardization
- One-Hot Encoding
- Train/Test Split
- Pipeline creation

### Machine Learning

- Logistic Regression
- Decision Tree
- Random Forest
- Model comparison
- Model evaluation

## Results

Three classification models were trained and evaluated:

- Logistic Regression
- Decision Tree
- Random Forest

Model performance was assessed using:

- Accuracy
- Precision
- Recall
- F1-score
- ROC-AUC
- Confusion Matrix

  ## Conclusions

The project demonstrates a complete machine learning pipeline for binary income classification.

The exploratory analysis revealed clear relationships between educational attainment and annual income, while multivariate analysis highlighted the importance of combining demographic and employment-related variables for prediction.

The comparison of several classification algorithms illustrates how different models perform on the same dataset and emphasizes the importance of appropriate preprocessing and evaluation.

## About Me

I am a Data Science & Business Analytics undergraduate at ESIC University in Madrid, Spain.

I am currently building my portfolio with projects in exploratory data analysis, machine learning and applied data science.
My goal is to pursue a research-oriented Master's degree and contribute to interdisciplinary research projects as a Graduate Student Researcher (GSR).
I am particularly interested in applying data science and machine learning to healthcare, agriculture and real-world decision-making problems.

My research interests include:

- Healthcare Data Science
- Agricultural Data Science
- Business Analytics
- Machine Learning

## Connect with Me

GitHub:
https://github.com/javiguuti


## Author

Javier Gutiérrez Esqués

Data Science & Business Analytics

ESIC University
