# Heart-disease-prediction-decision-tree-model

This project explores the application of decision tree algorithms in predicting heart disease. It serves as a learning project to gain practical experience with machine learning for healthcare data analysis.

## Problem Statement

We aim to create a simple decision tree model that looks at patient information to predict if they have heart disease or not. This model can be really helpful in healthcare by spotting people who might be at risk early on.

## Data Set

The project employs a heart disease dataset containing various attributes considered risk factors for heart disease. Here's a breakdown of the attributes:

* **age** (int): Patient's age in years.
* **gender** (int): Gender of the patient (0=Male, 1=Female).
* **chest pain** (int): Type of chest pain experienced (details depend on specific data set).
* **rest bps** (int): Blood pressure of the patient while resting (in mm Hg).
* **cholesterol** (int): Patient's cholesterol level (in mg/dl).
* **fasting blood sugar** (int): Blood sugar level of the patient while fasting (> 120 mg/dl considered abnormal).
* **rest ecg** (int): Resting electrocardiographic results (details depend on specific data set).
* **thalach** (int): Maximum heart rate achieved by the patient.
* **exer angina** (int): Presence of exercise-induced angina (0=No, 1=Yes).
* **old peak** (float): ST depression induced by exercise relative to rest.
* **slope** (int): Slope of the peak exercise ST segment on the ECG recording (0=Up-sloping, 1=Flat, 2=Down-sloping).
* **ca** (int): Number of major vessels (0-3) colored by fluoroscopy (likely indicates the number of narrowed or blocked coronary arteries).
* **thalssemia** (int): Results of a heart stress test (details depend on specific data set). May be a data collection error as thalassemia is a blood disorder typically not associated with coronary blockages.
* **target** (int): Presence of heart disease (1=Yes, 0=No).

## Learning Project

This project is a learning experience, and there's always room for improvement. Here are some potential areas for future development:

* **Data exploration and pre-processing:** Further investigate data characteristics, handle missing values, and potentially scale numerical features.
* **Model hyperparameter tuning:** Explore different decision tree algorithm parameters to optimize model accuracy.
* **Model evaluation:** Evaluate model performance using various metrics beyond accuracy (e.g., precision, recall).
* **Visualization:** Create visualizations to depict the decision tree structure and model performance.


