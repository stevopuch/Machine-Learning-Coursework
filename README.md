# Machine-Learning-Coursework
Practical machine learning using Python
# Machine Learning Coursework: Regression, Classification & Clustering

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![Pandas](https://img.shields.io/badge/Pandas-Data_Analysis-150458?logo=pandas)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-Machine_Learning-F7931E?logo=scikitlearn)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter)

## Project Overview

This repository contains a practical machine learning project completed as part of my **CDS 3301 Machine Learning coursework**.

The project explores three major machine learning approaches: supervised learning through regression and classification, and unsupervised learning through clustering.

Using Python and Scikit-learn, I performed exploratory data analysis, data preprocessing, model development, performance evaluation, cross-validation, and data visualization.

## Project Objectives

- Understand the differences between supervised and unsupervised learning.
- Implement and evaluate regression algorithms.
- Build classification models and compare their performance.
- Apply K-Means clustering to identify customer segments.
- Use Principal Component Analysis (PCA) for dimensionality reduction and visualization.
- Evaluate machine learning models using appropriate performance metrics.

## Technologies & Libraries

| Technology | Purpose |
|---|---|
| Python | Programming language |
| Pandas | Data manipulation and analysis |
| NumPy | Numerical computations |
| Matplotlib | Data visualization |
| Seaborn | Statistical visualization |
| Scikit-learn | Machine learning algorithms |
| Jupyter Notebook | Interactive development environment |

## Datasets & Analysis

### 1. Diabetes Dataset — Regression

**Objective:** Predict disease progression using patient-related features.

Algorithms implemented:
- Linear Regression
- Decision Tree Regressor

Evaluation metrics:
- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R-squared (R²)
- 5-fold cross-validation

**Key finding:** Linear Regression performed better than the Decision Tree Regressor on the evaluated test set and cross-validation.

| Model | MAE | RMSE | R² |
|---|---:|---:|---:|
| Linear Regression | 48.197 | 57.481 | 0.399 |
| Decision Tree Regressor | 68.009 | 86.403 | -0.357 |

### 2. Ionosphere Dataset — Classification

**Objective:** Classify radar returns as either good or bad.

Algorithms implemented:
- Logistic Regression
- Random Forest Classifier

Evaluation techniques:
- Confusion matrices
- Accuracy
- Precision
- Recall
- F1-score
- ROC-AUC
- Stratified 5-fold cross-validation

**Key finding:** Random Forest achieved a higher mean cross-validation F1-score than Logistic Regression.

| Model | Mean 5-fold CV F1 |
|---|---:|
| Logistic Regression | 0.905 |
| Random Forest | 0.950 |

### 3. Wholesale Customers Dataset — Clustering

**Objective:** Identify customer spending patterns and segment customers into meaningful groups.

Techniques implemented:
- Data preprocessing and standardization
- K-Means clustering
- Elbow method
- Silhouette analysis
- Cluster profiling
- Principal Component Analysis (PCA)

**Key findings:**
- Evaluated cluster counts from K=2 to K=8.
- Selected K=2 based on the silhouette score and elbow analysis.
- Achieved a silhouette score of 0.553.
- Identified two customer groups containing 53 and 387 customers.
- Reduced six spending features to two principal components.
- The two PCA components explained 72.5% of the total variance.

## Key Skills Demonstrated

- Python programming
- Data cleaning and preprocessing
- Exploratory Data Analysis (EDA)
- Supervised Machine Learning
- Unsupervised Machine Learning
- Regression and Classification
- K-Means Clustering
- Model Evaluation and Cross-Validation
- Data Visualization
- Dimensionality Reduction using PCA

## How to Run the Project

### 1. Clone the repository

```bash
git clone https://github.com/stevopuch/machine-learning-coursework.git
```

### 2. Navigate into the project directory

```bash
cd machine-learning-coursework
```

### 3. Install the required libraries

```bash
pip install numpy pandas matplotlib seaborn scikit-learn jupyter
```

### 4. Launch Jupyter Notebook

```bash
jupyter notebook
```

Open the `.ipynb` file and run the notebook cells sequentially.

**Note:** An internet connection may be required to retrieve the UCI datasets used in the notebook.

```
## Conclusion

This project provided practical experience in applying machine learning techniques to different types of real-world datasets. It strengthened my understanding of model selection, performance evaluation, data preprocessing, clustering, and visualization.

It also demonstrated that choosing an appropriate machine learning model requires careful evaluation rather than relying on algorithm complexity alone.
---
**Author:** Steve Odhiambo (stevopuch) 
**Field:** Data Science  
**Project:** Machine Learning Coursework
