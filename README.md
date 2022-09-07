# Breast-cancer-prediction


## Project Intro/Objective
The purpose of this project is to predict whether the tissue is benign or malignant or predicting whether the person has cancer or nor not. 

### Methods Used
* Statistics
* Machine Learning
* Data Visualization
* Predictive Modeling

### Technologies
* Python
* Pandas,Numpy, Scikit-learn, jupyter, SHAP (top important feature extraction)
 

## Project Description
This is a binary classificaiton problem. The aim is to correctly classify the tissue respectively. The target class is somewhat balanced. 

## Models used

- Random Forest Classifier
- Logistic Regression
- Support Vector Classifier
- Decision Tree
- XGBoost Classifier

## Metrics used for evaluation of models
Here we cannot completely depend on accuracy alone because its imbalanced dataset. Other metrics used are as follows

- Accuracy
- Confusion Matrix
- Precision Score
- Recall Score 
- F-beta Score

## Metric Importance
- Though our main focus metric is f2(giving more weightage to recall considering both precision and recall) and recall i.e patients having cancer are predicted as not having cancer we should give importance to both FP and FN as in case of FP if patient is falsely classifed as having cancer he might go under certain treatments which may affect his health considering a long term effect.
- Again its upto domain expert to decide on which metric is more critical towards decision making on model selection.
 
