# Lab 04 – Regression Models

## Aim
The aim of this lab is to build **Linear Regression and Logistic Regression models** and evaluate their performance using appropriate metrics. The experiments involve understanding datasets, visualizing relationships between variables, training regression models, and evaluating predictions using statistical and classification metrics.

---

## Datasets Used

### 1. TV Marketing Dataset
Dataset Link:  
https://github.com/Yashappin/Machine-Learning/blob/master/TvMarketing.csv

This dataset contains advertising budget information for **TV marketing** and the corresponding **sales generated**.  
It is used to build a **Simple Linear Regression model** to predict sales based on the TV advertising budget.

**Main Features**
- TV – Advertising budget spent on TV
- Sales – Product sales generated

---

### 2. CO2 Emission of Cars Dataset
Dataset Link:  
https://www.kaggle.com/datasets/midhundasl/co2-emission-of-cars-dataset

This dataset contains information about **car engine specifications and CO2 emissions**.  
It is used for **Multiple Linear Regression** to predict CO2 emission based on features like engine volume and vehicle weight.

**Important Features**
- Volume – Engine size
- Weight – Vehicle weight
- CO2 – Carbon dioxide emission

---

### 3. Advertisement Click Dataset
Dataset Link:  
https://www.kaggle.com/datasets/gabrielsantello/advertisement-click-on-ad

This dataset contains information about **user behaviour and advertisement interactions**.  
It is used to build a **Logistic Regression model** to predict whether a user will click on an advertisement.

**Typical Features**
- Daily Time Spent on Site
- Age
- Area Income
- Daily Internet Usage
- Ad Topic Line
- City
- Gender
- Country
- Timestamp
- Clicked on Ad (Target Variable)

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

### Experiment 1 – Simple Linear Regression
Build a linear regression model to predict **Sales** using **TV advertising budget**.

Steps include:
- Importing dataset
- Data visualization
- Train-test split (80:20)
- Training regression model
- Visualizing best-fit line
- Evaluating model using RMSE and R²

---

### Experiment 2 – Multiple Linear Regression
Build a multiple regression model to predict **CO2 emissions** using **Volume and Weight**.

Steps include:
- Data exploration
- Correlation analysis and heatmap
- Outlier detection using boxplots
- Training regression model
- Visualizing predictions
- Evaluating model using MAE, MSE, and RMSE

---

### Experiment 3 – Logistic Regression
Build a logistic regression model to predict **whether a user will click on an advertisement**.

Steps include:
- Exploratory Data Analysis
- Handling missing values and preprocessing
- Correlation analysis
- Training logistic regression model
- K-Fold cross validation
- Evaluating model using classification report
- Confusion matrix and ROC curve