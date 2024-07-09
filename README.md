# Eating Habits and Weight Analysis

## Overview
In this project, we analyze data from a survey conducted by Fabio Mendoza Palechor and Alexis de la Hoz Manotas. The survey asked people about their eating habits and weight. The data was obtained from the UCI Machine Learning Repository. Categorical variables were changed to numerical ones to facilitate analysis.

## Objectives
1. Fit a logistic regression model to predict whether survey respondents are obese based on their answers to survey questions.
2. Use three different wrapper methods to select a smaller feature subset:
   - Sequential Forward Selection (SFS)
   - Sequential Backward Floating Selection (SBFS)
   - Recursive Feature Elimination (RFE)
3. Evaluate and compare the model accuracy on the resulting smaller feature subsets with the model accuracy using all available features.

## Datasets
The dataset is available at the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Eating+Habits).

## Tasks
1. **Data Preparation**
   - Load the dataset and preprocess it by changing categorical variables to numerical ones.

2. **Logistic Regression Model**
   - Fit a logistic regression model to predict obesity based on survey responses.
   - Evaluate the model accuracy using all available features.

3. **Feature Selection**
   - **Sequential Forward Selection (SFS)**
     - Implement SFS to select a smaller subset of features.
     - Evaluate the model accuracy on the selected feature subset.
   - **Sequential Backward Floating Selection (SBFS)**
     - Implement SBFS to select a smaller subset of features.
     - Evaluate the model accuracy on the selected feature subset.
   - **Recursive Feature Elimination (RFE)**
     - Implement RFE to select a smaller subset of features.
     - Evaluate the model accuracy on the selected feature subset.

4. **Comparison of Model Accuracies**
   - Compare the model accuracies obtained using the different feature subsets with the model accuracy using all available features.
   - Discuss which feature selection method performed the best.

## Extensions
- Explore other feature selection methods and compare their performance.
- Analyze the impact of different preprocessing techniques on model accuracy.
- Try different machine learning models and compare their performance on this dataset.

