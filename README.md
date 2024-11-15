# README: Predicting Alcohol Consumption in Youth Using Machine Learning
### Overview

Alcohol consumption among youth is a significant public health concern, requiring effective interventions and analysis. This project employs machine learning techniques to investigate how various everyday choices, particularly in the scholastic environment, influence alcohol consumption among students.

The dataset used in this study was collected during the 2005-2006 academic year from two schools in Portugal's Alentejo region. This research aims to predict alcohol consumption levels using classification methods and analyze the contributing factors.
Objectives

The primary goals of this project include:
* Predicting students' alcohol consumption levels using machine learning models.
* Identifying factors influencing higher alcohol consumption.
* Evaluating different classification techniques to determine the most effective approach.

### Methodology

The project is divided into four main phases:
* Data Preparation:
  * Merge and shuffle datasets to form a single dataset.
  * Add a source identifier for the records.

* Preprocessing:
  * Select and optimize the target variable by aggregating weekday and weekend alcohol consumption data.
  * Convert the target variable into a binary classification problem with a threshold.
  * Perform discretization and feature selection.

* Classification:
  * Train and evaluate various machine learning classifiers, including Naïve Bayes, Support Vector Machine (SVM), and Random Forest.
  * Use different validation techniques such as Holdout, Iterated Holdout, Cross-Validation, and Leave-One-Out Cross-Validation.

* Evaluation:
  * Compare models using performance metrics such as accuracy and F-measure.

### Data Description

The dataset consists of **1044 student records with 34 attributes**, including demographic, familial, and scholastic factors, as well as alcohol consumption patterns. The features were carefully preprocessed to ensure high-quality inputs for classification tasks.

**Target variable**:
 AlcoholConsumpt: Aggregated alcohol consumption levels derived from weekday and weekend data, converted into binary values based on a threshold.

**Key attributes**:

  * sex-male (binary): Gender of the student.
  * studytime (numeric): Weekly study time.
  * failures (numeric): Past class failures.
  * goout (numeric): Frequency of going out with friends.
  * G3 (numeric): Final grade.
  * And others identified through feature selection.

### Tools and Techniques

The project was implemented using KNIME Analytics Platform, a user-friendly software for designing machine learning workflows.

**Key classifiers**:

  * Naïve Bayes (NB)
  * Support Vector Machine (SVM)
  * Random Forest (RF)

**Validation techniques**:

  * Holdout
  * Iterated Holdout
  * Cross Validation
  * Leave-One-Out Cross Validation

### Results and Conclusions

Performance evaluation revealed varying **accuracy, F-measure and ROC Curve** values for each classifier and validation technique. The findings highlight the importance of proper feature selection and validation for achieving reliable predictions.

By analyzing the results, we identified key factors influencing alcohol consumption among students and provided insights into the most effective classification methods for this problem.
Dataset Source

The dataset, Student Alcohol Consumption, is publicly available on Kaggle. It includes data from two school courses (Math and Portuguese) merged for this analysis.
