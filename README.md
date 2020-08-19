## Logistic regression to Classify Excessive Absenteeism
This notebook uses logistic regression to predict excessive absenteeism in the workplace. It includes data cleaning and preprocessing, modeling, model evaluation and suggested future work to improve the model. 

## Structure of the Project
The notebook is made up of the following sections:

### Data Cleaning and Proprocessing
This section includes feature engineering and one-hot encoding to ensure the data is in the correct form beform using the data to train a model.

### Modeling
This section includes creation of the target variable, normalising the data, modeling the data on both train and test sets and cross-validation.

### Model Evaluation
This section includes using ROC curves and ROC AUC scores to assess the model, precision-recall curves and F1 scores, feature and permutation importances plots to analyse how features are adding to model predictive power and a brief analysis of the intercept and coefficients of the model.

## Results Summary
The results include an average cross-validation ROC AUC of 82.8% on the training set and 79.3% on the test set.

