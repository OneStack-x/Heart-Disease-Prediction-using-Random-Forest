# Heart Disease Prediction using Random Forest

## Overview

This project builds a machine learning model to predict whether a patient has heart disease using the Heart Disease dataset. The model is trained using the **Random Forest Classifier** from Scikit-learn.

The project follows a standard machine learning workflow, including data exploration, preprocessing, model training, evaluation, and feature importance analysis.

---

## Dataset

The dataset contains patient medical information and a target column named **HeartDisease**, where:

* **0** = No Heart Disease
* **1** = Heart Disease

---

## Project Workflow

### 1. Data Loading

* Loaded the dataset using Pandas.
* Inspected the dataset structure using:

  * `head()`
  * `shape`
  * `info()`
  * `describe()`

### 2. Data Exploration

* Checked for missing values.
* Checked for duplicate rows.
* Examined the distribution of the target variable.
* Generated a correlation matrix.
* Visualized feature distributions using histograms.
* Identified potential outliers using boxplots.

### 3. Data Preprocessing

* Verified that the dataset contained no missing values.
* Verified that there were no duplicate records.
* Encoded categorical features using One-Hot Encoding (`pd.get_dummies()`).
* Split the dataset into training and testing sets.

> Since Random Forest is a tree-based algorithm, feature scaling was not required.

### 4. Model Training

* Trained a **Random Forest Classifier** using Scikit-learn.

### 5. Model Evaluation

The model was evaluated using:

* Accuracy
* Precision
* Recall
* F1 Score


### 6. Feature Importance

* Calculated feature importance scores using the trained Random Forest model.
* Visualized the most important features with a bar chart.

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

---


## Learning Outcomes

Through this project, I learned how to:

* Explore and understand a real-world medical dataset.
* Perform exploratory data analysis (EDA).
* Handle categorical features using One-Hot Encoding.
* Train a Random Forest classification model.
* Evaluate a classification model using multiple performance metrics.
* Interpret feature importance to understand which variables contributed most to the model's predictions.

---

