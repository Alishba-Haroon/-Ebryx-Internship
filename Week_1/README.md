# 🧠 Week 1 — Machine Learning Fundamentals & Pandas Series

A comprehensive introduction to **Machine Learning** concepts along with a hands-on **Pandas Series** notebook covering data manipulation basics.

---

## 📂 Contents

- `WEEK_1__Ml_and_types_.docx` — ML fundamentals, types, algorithms, workflow
- `pandas_series.ipynb` — Pandas Series creation, attributes, and methods

---

## ✨ Topics Covered

- 🤖 What is Machine Learning?
- 📊 Types of ML: Supervised, Unsupervised
- 🎮 Reinforcement Learning
- 🔄 ML Workflow: Problem Definition → Data Collection → Preprocessing → Model Training → Evaluation → Deployment
- ⚖️ Bias-Variance Tradeoff
- 📉 Gradient Descents (SGD, Batch, etc.)
- 🎯 Overfitting vs Underfitting
- 📏 Evaluation Metrics: Accuracy, Precision, Recall, F1-score, MSE, R²
- 🔁 Cross Validation
- 🛡️ Regularization
- 🎯 Feature Selection
- 🌲 Ensemble Methods
- 📊 Exploratory Data Analysis (EDA)
- 🐼 Pandas Series

---

# 🤖 What is Machine Learning?

**Machine Learning (ML)** is a branch of Artificial Intelligence that enables computers to learn patterns from data and make predictions or decisions without being explicitly programmed for every task.

---

# 📊 Types of Machine Learning

1. **Supervised Learning**
2. **Unsupervised Learning**
3. **Reinforcement Learning**

## 🎯 Supervised Learning
Model learns from **labeled data** (input features + correct output).
**Example:** Predicting whether an email is spam or not.

### Classification Algorithms
| Algorithm | Description |
|---|---|
| Logistic Regression | Used for classification problems |
| Decision Tree | Makes decisions using tree-based rules |
| Random Forest | Combines multiple decision trees |
| KNN | Classifies data based on nearby points |
| Naive Bayes | Probabilistic classification algorithm |
| SVM | Finds an optimal decision boundary |

### Regression Algorithms
| Algorithm | Description |
|---|---|
| Linear Regression | Predicts continuous values linearly |
| Polynomial Regression | Models non-linear relationships |
| Ridge Regression | Linear regression with L2 regularization |
| Lasso Regression | Linear regression with L1 regularization |
| Decision Tree Regression | Uses decision trees for continuous prediction |
| Random Forest Regression | Uses multiple trees for regression |

### Applications
📧 Spam Detection · 🏠 House Price Prediction · 🏥 Disease Prediction · 👥 Customer Churn · 🖼️ Image Classification · 💰 Sales Prediction

## 🔍 Unsupervised Learning
Model works with **unlabeled data** to discover hidden patterns.
**Example:** Grouping customers based on purchasing behavior.

### Clustering
| Algorithm | Description |
|---|---|
| K-Means | Groups data into predefined clusters |
| DBSCAN | Groups points based on density |
| Mean-Shift | Finds clusters based on data density |

### Dimensionality Reduction
| Technique | Description |
|---|---|
| PCA | Reduces features while preserving information |
| ICA | Separates data into independent components |

### Applications
👥 Customer Segmentation · 🚨 Anomaly Detection · 🛍️ Market Segmentation · 🔎 Pattern Discovery · 📊 Data Visualization · 📉 Feature Reduction

## 🎮 Reinforcement Learning
Agent learns by interacting with an environment — receives ✅ rewards / ❌ penalties, aiming to maximize total reward over time.

---

# 🔄 Machine Learning Development Life Cycle

1. Problem Definition
2. Data Collection
3. Data Cleaning & Preprocessing
4. Exploratory Data Analysis (EDA)
5. Feature Engineering & Selection
6. Model Selection
7. Model Training
8. Evaluation & Tuning
9. Deployment
10. Monitoring & Maintenance


---

# ⚖️ Bias-Variance Tradeoff

**High Bias:** model too simple → underfitting → poor performance on both train/test.
**High Variance:** model too complex → overfitting → great on train, poor on unseen data.
**Goal:** balance bias and variance for good generalization.

---

# 📉 Gradient Descent

**Gradient Descent** is an optimization algorithm used to minimize a model's loss/cost function by iteratively updating parameters in the direction of steepest descent.

### Common Types
- **Batch Gradient Descent** — uses the entire dataset for each update
- **Stochastic Gradient Descent (SGD)** — uses one data point at a time for each update
- **Mini-Batch Gradient Descent** — uses small batches of data for each update

---

# 🎯 Overfitting vs Underfitting

### Overfitting
- Model learns training data too well, including noise
- Performs great on training data, poorly on unseen/test data
- Caused by high model complexity / high variance

### Underfitting
- Model is too simple to capture underlying patterns
- Performs poorly on both training and test data
- Caused by high bias

### Solutions
- Regularization (L1/L2)
- Cross Validation
- More/better training data
- Feature Selection
- Simplifying or tuning model complexity

---

# 📏 Evaluation Metrics

### Classification Metrics
| Metric | Description |
|---|---|
| Accuracy | Ratio of correctly predicted observations to total observations |
| Precision | Ratio of true positives to all predicted positives |
| Recall | Ratio of true positives to all actual positives |
| F1-score | Harmonic mean of Precision and Recall |

### Regression Metrics
| Metric | Description |
|---|---|
| MSE (Mean Squared Error) | Average of squared differences between predicted and actual values |
| R² (R-squared) | Proportion of variance in the target explained by the model |

---

# 🔁 Cross Validation
Evaluates model performance by splitting data into multiple parts and training/testing repeatedly.
**Benefits:** reliable evaluation, detects overfitting, better data utilization.

# 🛡️ Regularization
Reduces overfitting by penalizing model complexity.
- **L1 (Lasso)**
- **L2 (Ridge)**

# 🎯 Feature Selection
Selecting the most relevant features.
**Benefits:** reduces unnecessary features, improves performance, cuts computational cost, reduces overfitting.

# 🌲 Ensemble Methods
Combine multiple models to improve prediction performance.
**Examples:** Random Forest, Bagging, Boosting, Voting

# 📊 Exploratory Data Analysis (EDA)

### Main Steps
1. Load the dataset
2. Understand dataset structure
3. Check data types
4. Check missing values
5. Check duplicate values
6. Analyze statistical information
7. Detect outliers
8. Visualize data and identify patterns

### Techniques
Descriptive Statistics · Histograms · Box Plots · Scatter Plots · Correlation Analysis · Distribution Analysis

---

# 🐼 Pandas Series — Notebook Overview

### What is Pandas
Pandas is a fast, powerful, flexible, and easy-to-use open source data analysis and manipulation tool built on Python.

### What is a Series
A Pandas Series is like a column in a table — a 1-D array holding data of any type.

### Topics Practiced in Notebook
- Creating a Series from a **list** (string & integer data)
- Creating a Series with a **custom index**
- Setting a **name** for a Series
- Creating a Series from a **dictionary**
- **Series attributes:** `size`, `dtype`, `name`, `is_unique`, `index`, `values`
- Creating a Series using **`read_csv`**
- Series **math methods** and operations
- `astype` — memory optimization (`sys.getsizeof`)
- `between()` — range filtering
- `clip()` — bounding values
- `duplicated()` / `drop_duplicates()`
- Handling missing data: `isnull()`, `dropna()`, `fillna()`
- `isin()` — membership filtering
- Boolean indexing / filtering with conditions

### Example Snippet
```python
import pandas as pd
import numpy as np

# Series from a list
country = ["Pakistan", "UK", "USA", "south Korea", "Turkey"]
pd_series = pd.Series(country)

# Series with custom index
marks = [50, 80, 66, 79, 34]
subject = ["urdu", "english", "math", "computer Science", "Chemistry"]
custom_index = pd.Series(marks, index=subject, name='Ali Marks')

# Series from dict
dict_series = {'Name': 'ALi', 'class': 12, 'subject': 80, 'Section': 'C'}
dict1 = pd.Series(dict_series, name='ali info')
```

---

# 🎥 Learning Resources

## 📚 GeeksforGeeks
- [Introduction to Machine Learning](https://www.geeksforgeeks.org/machine-learning/introduction-machine-learning/ml/)
- [Types of Machine Learning](https://www.geeksforgeeks.org/machine-learning/types-of-machine-learning/types/)
- [Machine Learning Lifecycle](https://www.geeksforgeeks.org/machine-learning/machine-learning-lifecycle/)
- [ML Bias-Variance Tradeoff](https://www.geeksforgeeks.org/machine-learning/ml-bias-variance-trade-off/)
- [Exploratory Data Analysis (EDA)](https://www.geeksforgeeks.org/data-analysis/what-is-exploratory-data-analysis/)

## 🎬 YouTube
- [What is Machine Learning? | 100 Days of ML](https://youtu.be/ZftI2fEz0Fw)
- [Types of Machine Learning for Beginners](https://youtu.be/81ymPYEtFOw)
- [Machine Learning Development Life Cycle](https://youtu.be/iDbhQGz_rEo)
- [Bias-Variance Tradeoff](https://youtu.be/O-qONAxkvK0)
- [Gradient Descent](https://youtu.be/ORyfPJypKuU)

---

# 📝 Week 1 Summary

During Week 1, I learned the fundamentals of **Machine Learning** — including types, workflow, bias-variance tradeoff, gradient descent, overfitting vs underfitting, evaluation metrics, and EDA — plus hands-on practice with **Pandas Series** for 1-D data manipulation.

### Key Takeaways
- 🤖 ML enables systems to learn patterns from data
- 🎯 Supervised Learning uses labeled data
- 🔍 Unsupervised Learning discovers patterns in unlabeled data
- 🎮 Reinforcement Learning learns through rewards and penalties
- 🔄 ML Workflow: Problem definition → Data Collection → Preprocessing → Model Training → Evaluation → Deployment
- ⚖️ Bias-Variance Tradeoff explains under/overfitting
- 📉 Gradient Descent optimizes model parameters (Batch, SGD, Mini-Batch)
- 🎯 Overfitting vs Underfitting — knowing the difference and how to fix each
- 📏 Evaluation Metrics: Accuracy, Precision, Recall, F1-score, MSE, R²
- 🔁 Cross Validation gives reliable model evaluation
- 🛡️ Regularization reduces overfitting
- 🎯 Feature Selection identifies important features
- 📊 EDA is essential before model building
- 🐼 Pandas Series is the building block for handling 1-D data

---

## 📌 Week 1
**Focus:** Machine Learning Fundamentals + Pandas Series

**Covered this week:**
- What is ML? Types of ML: Supervised, Unsupervised
- ML Workflow: Problem definition → Data Collection → Preprocessing → Model Training → Evaluation → Deployment
- Bias-Variance Tradeoff
- Exploratory Data Analysis
- Gradient Descents (SGD, Batch, etc.)
- Overfitting vs Underfitting
- Evaluation Metrics: Accuracy, Precision, Recall, F1-score, MSE, R²
- Pandas Series
