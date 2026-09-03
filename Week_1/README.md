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
