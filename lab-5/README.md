# ML Lab 05 – Supervised Learning

## Aim
The aim of this lab is to build **Naïve Bayes and Decision Tree classification models** and evaluate their performance using appropriate metrics such as accuracy, confusion matrix, classification report, and precision-recall analysis.

---

## Dataset

### Breast Cancer Wisconsin (Diagnostic) Dataset

Dataset Link:  
https://archive.ics.uci.edu/dataset/17/breast+cancer+wisconsin+diagnostic

The **Breast Cancer Wisconsin (Diagnostic)** dataset is a widely used benchmark dataset for **binary classification** problems in machine learning. The dataset is used to classify tumors as **malignant (cancerous)** or **benign (non-cancerous)** based on features extracted from digitized images of breast cell nuclei.

### Dataset Characteristics
- Total instances: **569**
- Benign cases: **357**
- Malignant cases: **212**
- Number of features: **30 numerical attributes**

### Example Features
- Radius
- Texture
- Perimeter
- Area
- Smoothness
- Compactness
- Concavity
- Symmetry
- Fractal dimension

These features are computed from cell nuclei images and help in identifying patterns related to cancer diagnosis.

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

### Experiment 1 – Naïve Bayes Classification
Build a **Naïve Bayes classifier** using the Breast Cancer dataset to predict class labels.

Tasks include:
- Loading the dataset
- Splitting into training and testing sets
- Training a Naïve Bayes model
- Predicting test labels
- Evaluating performance using accuracy, confusion matrix, classification report, and precision-recall curve

---

### Experiment 2 – Decision Tree Classification
Build a **Decision Tree classifier** using the same dataset and evaluate its performance.

Tasks include:
- Training a Decision Tree model
- Predicting class labels
- Evaluating using accuracy, confusion matrix, classification report, and precision-recall curve
- Visualizing the decision tree

---

### Experiment 3 – Model Comparison
Compare the performance of **Naïve Bayes and Decision Tree models** using visualization techniques.

Comparison methods include:
- Bar chart comparing training and testing accuracy
- ROC curve comparison
- Confusion matrix heatmap comparison