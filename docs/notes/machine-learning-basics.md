# Machine Learning Basics

## What is Machine Learning?

Machine Learning is a subset of AI that enables systems to learn and improve from experience without being explicitly programmed.

## Categories of ML

### Supervised Learning
- **Classification** — Predicting discrete labels (e.g., spam vs. not spam)
- **Regression** — Predicting continuous values (e.g., house prices)

### Unsupervised Learning
- **Clustering** — Grouping similar data points (e.g., K-means)
- **Dimensionality Reduction** — Simplifying data (e.g., PCA)

### Reinforcement Learning
- Agent learns by interacting with an environment
- Maximizes cumulative reward through trial and error

## Common Algorithms

1. Linear Regression
2. Logistic Regression
3. Decision Trees & Random Forests
4. Support Vector Machines (SVM)
5. K-Nearest Neighbors (KNN)
6. Neural Networks

```python
from sklearn.model_selection import train_test_split
from sklearn.ensemble import RandomForestClassifier

X_train, X_test, y_train, y_test = train_test_split(X, y, test_size=0.2)
model = RandomForestClassifier(n_estimators=100)
model.fit(X_train, y_train)
accuracy = model.score(X_test, y_test)
print(f"Accuracy: {accuracy:.2%}")
```
