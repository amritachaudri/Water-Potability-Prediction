# Water-Potability-Prediction

## Project Overview
This project aims to predict the potability of water based on specific quality metrics, addressing a fundamental human right and a key element of health protection policies. Using a dataset of 3,276 water bodies, we implement and evaluate various classical machine learning models to determine if water is safe for consumption.

## Dataset
* **Total Samples:** 3,276 entries 
* **Target Variable:** Potability (Binary)
  
## Implementation Phases

### Phase 1: Data Exploration & Pre-processing
* **Exploratory Data Analysis (EDA):** Sanity checks, class imbalance visualization, and correlational analysis.
* **Cleaning:** Identifying and handling null/missing values, outliers, and skewed data.
* **Feature Engineering:** Applying transformations such as Standardization and Normalization.
* **Data Balancing:** Exploring latest techniques to address class imbalance and their effects on evaluation.

### Phase 2: Model Development
This project strictly utilizes classical Machine Learning techniques; Deep Learning models are not permitted.

**Baseline Models:**
* Logistic Regression
* Decision Tree

**Advanced Classifiers:**
* K-Nearest Neighbors (K-NN) 
* Support Vector Machine (SVM)
* Naive Bayesian
* Random Forest
* AdaBoost

### Phase 3: Hyperparameter Fine-Tuning
To optimize performance, we utilize hyperparameter optimization techniques:
* **Grid Search** 
* **Randomized Search** 

## Performance Evaluation
Models are assessed using the following metrics to ensure a detailed analysis of their effectiveness:
* **Accuracy** 
* **Precision & Recall** 
* **F-score** 
* **Misclassification Rate** 

---
*Developed as part of the AIMLCZG565 Machine Learning course - First Semester, 2023-24.* [cite: 21, 22]
