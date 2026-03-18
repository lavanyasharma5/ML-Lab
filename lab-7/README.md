# ML Lab 07 – Ensemble Learning

## Aim
The aim of this lab is to implement **Ensemble Learning models** such as Random Forest and AdaBoost and evaluate their performance using classification metrics. The lab also analyzes how hyperparameters like number of estimators, tree depth, learning rate, and weak learners affect model accuracy.

---
## Dataset

### Iris Dataset

Dataset Link:  
https://archive.ics.uci.edu/dataset/53/iris

The **Iris dataset** is one of the most popular datasets in machine learning.  
It contains measurements of iris flowers from three different species and is commonly used for classification tasks.

### Dataset Features
- sepal length
- sepal width
- petal length
- petal width
- species (target class)

Total samples: 150  
Classes: 3

The dataset is suitable for testing classification algorithms and ensemble models.

---

## Libraries Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## Experiments

### Experiment 1 – Random Forest Classifier
Implement Random Forest classifier on Iris dataset and analyze the effect of:
- number of estimators
- maximum depth

Evaluate using:
- Accuracy
- Confusion Matrix
- Classification Report
- Precision-Recall curve

---

### Experiment 2 – AdaBoost Classifier
Implement AdaBoost ensemble classifier on the same dataset.

Analyze the effect of:
- number of weak learners
- learning rate

Evaluate using:
- Accuracy
- Confusion Matrix
- Classification Report
- Precision-Recall curve