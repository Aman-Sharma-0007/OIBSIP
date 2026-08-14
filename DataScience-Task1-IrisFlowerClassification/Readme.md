# Iris Flower Classification

A machine learning project built as part of my internship evaluation. The goal is to classify iris flowers into three species — Setosa, Versicolor, and Virginica — using physical measurements like petal and sepal dimensions.

---

## Dataset

- Source: `sklearn.datasets.load_iris()` — no external download needed
- Total samples: **150**
- Features: **4** (sepal length, sepal width, petal length, petal width)
- Classes: **3** (Setosa, Versicolor, Virginica)
- Class distribution: perfectly balanced — **50 samples per class**
- Missing values: **None**

---

## Tech Stack

| Tool | Purpose |
|------|---------|
| Python 3 | Core language |
| pandas | Data loading and manipulation |
| numpy | Numerical operations |
| matplotlib | Plotting |
| seaborn | Statistical visualisations |
| scikit-learn | ML models and evaluation |
| Jupyter Notebook | Development environment |

---

---

## What's Covered

- Exploratory Data Analysis — shape, dtypes, null check, descriptive statistics
- Visualisations — pairplot, boxplots per feature, correlation heatmap
- Feature selection discussion backed by correlation values and RF importances
- Train/test split — 80/20 with stratification
- Four classifiers trained and evaluated
- Best model declared with written justification

---

## Models Trained

| Model | Test Accuracy |
|-------|--------------|
| Logistic Regression | 96.67% |
| K-Nearest Neighbours | 96.67% |
| Decision Tree | 96.67% |
| Random Forest | 96.67% |

> Note: Accuracy values may vary slightly depending on your environment. Above results are from `random_state=42`.

---

## Key Findings

**Feature Importance (from Random Forest):**

| Feature | Importance Score |
|---------|-----------------|
| petal length (cm) | ~0.44 |
| petal width (cm) | ~0.42 |
| sepal length (cm) | ~0.10 |
| sepal width (cm) | ~0.04 |

- Petal length and petal width together account for **~86%** of the model's decision making
- Sepal width is the least useful feature — nearly uncorrelated with species
- Setosa is **linearly separable** from the other two species
- Versicolor and Virginica have slight overlap, visible in the pairplot

---

## Best Model

**Random Forest** — chosen for the following reasons:
- Ensemble of 100 decision trees, reduces variance through averaging
- Handles feature interactions and non-linear boundaries well
- Most robust to overfitting compared to a single Decision Tree
- Consistent performance even without heavy hyperparameter tuning

---


## Author
Aman Sharma
B.Tech CSE-AIML, UIET, KUK