# 🧠 Week 1 — Machine Learning Fundamentals

A comprehensive introduction to **Machine Learning**, its different types, commonly used algorithms, Machine Learning workflow, model evaluation concepts, and Exploratory Data Analysis (EDA).

---

## ✨ Topics Covered

* 🤖 What is Machine Learning?
* 📊 Types of Machine Learning
* 🎯 Supervised Learning
* 🔍 Unsupervised Learning
* 🎮 Reinforcement Learning
* 📈 Classification Algorithms
* 📉 Regression Algorithms
* 🧩 Clustering
* 📐 Dimensionality Reduction
* 🔄 Machine Learning Development Life Cycle
* ⚖️ Bias-Variance Tradeoff
* 🔁 Cross Validation
* 🛡️ Regularization
* 🎯 Feature Selection
* 🌲 Ensemble Methods
* 📊 Exploratory Data Analysis (EDA)

---

# 🤖 What is Machine Learning?

**Machine Learning (ML)** is a branch of Artificial Intelligence that enables computers to learn patterns from data and make predictions or decisions without being explicitly programmed for every task.

---

# 📊 Types of Machine Learning

Machine Learning is mainly divided into three types:

1. **Supervised Learning**
2. **Unsupervised Learning**
3. **Reinforcement Learning**

---

## 🎯 Supervised Learning

In supervised learning, the model learns from **labeled data**, where both input features and the correct output are provided.

**Example:**
Predicting whether an email is spam or not spam.

### Classification Algorithms

| Algorithm                    | Description                                 |
| ---------------------------- | ------------------------------------------- |
| Logistic Regression          | Used for classification problems            |
| Decision Tree                | Makes decisions using tree-based rules      |
| Random Forest                | Combines multiple decision trees            |
| K-Nearest Neighbors (KNN)    | Classifies data based on nearby data points |
| Naive Bayes                  | Probabilistic classification algorithm      |
| Support Vector Machine (SVM) | Finds an optimal decision boundary          |

### Regression Algorithms

| Algorithm                | Description                                            |
| ------------------------ | ------------------------------------------------------ |
| Linear Regression        | Predicts continuous values using a linear relationship |
| Polynomial Regression    | Models non-linear relationships                        |
| Ridge Regression         | Linear regression with L2 regularization               |
| Lasso Regression         | Linear regression with L1 regularization               |
| Decision Tree Regression | Uses decision trees for continuous prediction          |
| Random Forest Regression | Uses multiple decision trees for regression            |

### Applications

* 📧 Spam Detection
* 🏠 House Price Prediction
* 🏥 Disease Prediction
* 👥 Customer Churn Prediction
* 🖼️ Image Classification
* 💰 Sales Prediction

---

## 🔍 Unsupervised Learning

In unsupervised learning, the model works with **unlabeled data** and tries to discover hidden patterns or structures.

**Example:**
Grouping customers based on their purchasing behavior.

### Clustering Algorithms

| Algorithm  | Description                                      |
| ---------- | ------------------------------------------------ |
| K-Means    | Groups data into a predefined number of clusters |
| DBSCAN     | Groups points based on density                   |
| Mean-Shift | Finds clusters based on data density             |

### Dimensionality Reduction

| Technique | Description                                                           |
| --------- | --------------------------------------------------------------------- |
| PCA       | Reduces the number of features while preserving important information |
| ICA       | Separates data into statistically independent components              |

### Applications

* 👥 Customer Segmentation
* 🚨 Anomaly Detection
* 🛍️ Market Segmentation
* 🔎 Pattern Discovery
* 📊 Data Visualization
* 📉 Feature Reduction

---

## 🎮 Reinforcement Learning

Reinforcement Learning is a type of Machine Learning where an **agent learns by interacting with an environment**.

The agent receives:

* ✅ Rewards for good actions
* ❌ Penalties for bad actions

The goal is to learn a strategy that maximizes the total reward over time.

---

# 🔄 Machine Learning Development Life Cycle

The main steps of the Machine Learning workflow are:

1. **Problem Definition**
2. **Data Collection**
3. **Data Cleaning & Preprocessing**
4. **Exploratory Data Analysis (EDA)**
5. **Feature Engineering & Selection**
6. **Model Selection**
7. **Model Training**
8. **Evaluation & Tuning**
9. **Deployment**
10. **Monitoring & Maintenance**

### ML Workflow

```text
Problem Definition
        ↓
Data Collection
        ↓
Data Cleaning & Preprocessing
        ↓
Exploratory Data Analysis
        ↓
Feature Engineering & Selection
        ↓
Model Selection
        ↓
Model Training
        ↓
Evaluation & Tuning
        ↓
Deployment
        ↓
Monitoring & Maintenance
```

---

# ⚖️ Bias-Variance Tradeoff

The **Bias-Variance Tradeoff** describes the balance between model bias and model variance.

### High Bias

* Model is too simple
* Can lead to **underfitting**
* Performs poorly on training and testing data

### High Variance

* Model is too complex
* Can lead to **overfitting**
* Performs very well on training data but poorly on unseen data

### Goal

Find a balance between **bias and variance** so that the model generalizes well to unseen data.

---

# 🔁 Cross Validation

**Cross Validation** is a technique used to evaluate the performance of a Machine Learning model.

The dataset is divided into multiple parts, and the model is trained and tested multiple times using different portions of the data.

### Benefits

* More reliable model evaluation
* Helps detect overfitting
* Makes better use of available data

---

# 🛡️ Regularization

**Regularization** is a technique used to reduce overfitting by adding a penalty to the model's complexity.

### Common Types

* **L1 Regularization (Lasso)**
* **L2 Regularization (Ridge)**

---

# 🎯 Feature Selection

**Feature Selection** is the process of selecting the most relevant features from a dataset.

### Benefits

* Reduces unnecessary features
* Improves model performance
* Reduces computational cost
* Helps reduce overfitting

---

# 🌲 Ensemble Methods

**Ensemble Methods** combine multiple Machine Learning models to improve prediction performance.

### Examples

* Random Forest
* Bagging
* Boosting
* Voting

The basic idea is to combine multiple models instead of relying on a single model.

---

# 📊 Exploratory Data Analysis (EDA)

**EDA** is the process of analyzing and understanding a dataset before building a Machine Learning model.

### Main Steps

1. Load the dataset
2. Understand the dataset structure
3. Check data types
4. Check missing values
5. Check duplicate values
6. Analyze statistical information
7. Detect outliers
8. Visualize data and identify patterns

### Common EDA Techniques

* Descriptive Statistics
* Histograms
* Box Plots
* Scatter Plots
* Correlation Analysis
* Distribution Analysis

---

# 🎥 Learning Resources

## 📚 GeeksforGeeks Resources

* [Introduction to Machine Learning – GeeksforGeeks](https://www.geeksforgeeks.org/machine-learning/introduction-machine-learning/ml/)
* [Types of Machine Learning – GeeksforGeeks](https://www.geeksforgeeks.org/machine-learning/types-of-machine-learning/types/)
* [Machine Learning Lifecycle – GeeksforGeeks](https://www.geeksforgeeks.org/machine-learning/machine-learning-lifecycle/)
* [ML Bias-Variance Tradeoff – GeeksforGeeks](https://www.geeksforgeeks.org/machine-learning/ml-bias-variance-trade-off/)
* [Exploratory Data Analysis (EDA) – GeeksforGeeks](https://www.geeksforgeeks.org/data-analysis/what-is-exploratory-data-analysis/)

---

## 🎬 YouTube Resources

### 1️⃣ What is Machine Learning?

[What is Machine Learning? | 100 Days of Machine Learning](https://youtu.be/ZftI2fEz0Fw?si=ttf16ZmjzDkiQ48G)

### 2️⃣ Types of Machine Learning

[Types of Machine Learning for Beginners](https://youtu.be/81ymPYEtFOw?si=Qz-UyWrdbqoFrb_S)

### 3️⃣ Machine Learning Development Life Cycle

[Machine Learning Development Life Cycle | MLDLC](https://youtu.be/iDbhQGz_rEo?si=etEs1Llw7PBP3eiZ)


# 📝 Week 1 Summary

During Week 1, I learned the fundamentals of **Machine Learning**, including its major types, commonly used algorithms, Machine Learning workflow, model evaluation concepts, and Exploratory Data Analysis.

### Key Takeaways

* 🤖 Machine Learning enables systems to learn patterns from data.
* 🎯 Supervised Learning uses labeled data.
* 🔍 Unsupervised Learning discovers patterns in unlabeled data.
* 🎮 Reinforcement Learning learns through rewards and penalties.
* 🔄 The ML lifecycle includes data preparation, training, evaluation, deployment, and monitoring.
* ⚖️ Bias-Variance Tradeoff helps understand underfitting and overfitting.
* 🔁 Cross Validation provides reliable model evaluation.
* 🛡️ Regularization helps reduce overfitting.
* 🎯 Feature Selection identifies important features.
* 📊 EDA helps understand and analyze data before model development.

---

## 📌 Week 1

**Focus:** Machine Learning Fundamentals

**Next:** 
• Gradient Descents (SGD, Batch, etc.)
• Overfitting vs Underfitting
• Evaluation Metrics: Accuracy, Precision, Recall, F1-score, MSE, R²
