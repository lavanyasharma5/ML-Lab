# ML Lab 06 – Supervised Learning (KNN & SVM)

## Aim
The aim of this lab is to build **K-Nearest Neighbour (KNN) and Support Vector Machine (SVM) classification models** and evaluate their performance using appropriate metrics such as accuracy, confusion matrix, classification report, precision-recall curve, and ROC curve.

---

## Dataset

### Breast Cancer Wisconsin (Diagnostic) Dataset

Dataset Link:  
https://archive.ics.uci.edu/dataset/17/breast+cancer+wisconsin+diagnostic

The **Breast Cancer Wisconsin (Diagnostic)** dataset is a benchmark dataset used for binary classification problems.  
The task is to classify tumors as **malignant** or **benign** based on numerical features extracted from images of cell nuclei.

### Dataset Details
- Total samples: 569
- Benign: 357
- Malignant: 212
- Features: 30 numerical attributes

### Example Features
- radius
- texture
- perimeter
- area
- smoothness
- compactness
- concavity
- symmetry
- fractal dimension

This dataset is widely used for testing classification algorithms in machine learning.

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

### Experiment 1 – K-Nearest Neighbour Classification
Build a KNN classifier using the Breast Cancer dataset.

Steps:
- Load dataset
- Train-test split
- Train KNN model
- Predict labels
- Evaluate using accuracy, confusion matrix, classification report, precision-recall curve

---

### Experiment 2 – Support Vector Machine Classification
Build an SVM classifier using the same dataset.

Steps:
- Load dataset
- Train-test split
- Train SVM model
- Predict labels
- Evaluate using accuracy, confusion matrix, classification report, precision-recall curve

---

### Experiment 3 – Model Comparison
Compare KNN and SVM models using visualization.

Methods:
- Accuracy comparison bar chart
- ROC curve comparison
- Confusion matrix heatmap