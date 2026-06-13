# Breast Cancer Prediction Using K-Nearest Neighbors (KNN)

## Project Overview

This project implements a K-Nearest Neighbors (KNN) classification model using the Breast Cancer Wisconsin dataset from Scikit-learn. The objective is to classify tumors as malignant or benign while demonstrating a complete machine learning workflow including data exploration, preprocessing, feature scaling, hyperparameter tuning, model evaluation, and prediction.

---

## Dataset

**Dataset:** Breast Cancer Wisconsin Dataset

**Source:** Scikit-learn (`load_breast_cancer()`)

### Dataset Information

* 569 observations
* 30 numerical features
* Binary target variable:

  * 0 = Malignant
  * 1 = Benign

The dataset contains measurements computed from digitized images of breast mass cell nuclei.

---

## Project Workflow

### 1. Data Loading and Exploration

* Loaded dataset using Scikit-learn
* Examined dataset structure
* Reviewed feature names
* Generated descriptive statistics

### 2. Data Cleaning

* Checked for missing values
* Checked for duplicate records
* Standardized column names

### 3. Exploratory Data Analysis (EDA)

* Visualized feature distributions using histograms
* Examined feature relationships using a correlation heatmap

### 4. Data Preprocessing

* Split data into training and testing sets using an 80/20 ratio
* Applied StandardScaler to normalize feature values

### 5. Model Development

* Built an initial K-Nearest Neighbors classifier
* Trained the model on scaled training data

### 6. Hyperparameter Tuning

* Evaluated multiple k values using Stratified K-Fold Cross Validation
* Compared model performance across different neighbor settings
* Selected the optimal k value based on mean cross-validation accuracy

### 7. Model Evaluation

The final model was evaluated using:

* Accuracy Score
* Precision Score
* Recall Score
* F1 Score
* Confusion Matrix

### 8. Prediction

Generated predictions on unseen test data and new sample observations.

---

## Results

The KNN classifier achieved strong classification performance on the Breast Cancer dataset after feature scaling and hyperparameter tuning.

Key findings:

* Feature scaling significantly improved KNN performance.
* Cross-validation helped identify the most effective value of k.
* The model demonstrated strong predictive capability on unseen data.
* Multiple evaluation metrics provided a more complete assessment than accuracy alone.

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

---


## Running the Project

Open the notebook:

```bash
jupyter notebook breast_cancer_prediction.ipynb
```

Run all cells sequentially to reproduce the analysis and results.

---

## Key Learning Outcomes

* Understanding distance-based machine learning algorithms
* Importance of feature scaling for KNN
* Using cross-validation for model selection
* Evaluating classification models with multiple metrics
* Building an end-to-end machine learning workflow

---

## Author

Taiwo Olaniyi Toheeb

Data Analyst | Aspiring Data Scientist | Transportation Management Graduate
