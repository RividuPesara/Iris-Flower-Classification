# Iris Flower Classification using Machine Learning

## Problem Statement

The iris flower is a distinctive genus of flowering plants. There are three primary species: *Iris setosa*, *Iris versicolor*, and *Iris virginica*. These species exhibit variations in their measurements in sepal length, sepal width, petal length, and petal width.

## Objective

To develop machine learning models capable of learning from the measurements of iris flowers and accurately classifying them into their species.

## Project Details

- **Iris Species:** The dataset contains 3 species *setosa*, *versicolor*, and *virginica*.
- **Key Measurements:** The essential characteristics used for classification include sepal length, sepal width, petal length, and petal width.
- **Machine Learning Models:** The project involves training Logistic Regression and Support Vector Machine (SVM) models to classify iris flowers based on their measurements.

## Results

Logistic Regression model was tuned with different regularization parameters, and the best cross validated accuracy was  with:  
    C = 2.0 : Accuracy = 95.53%

- **Manual Rule-based Classifier Accuracy:** 96.43%  
- **Final Logistic Regression Model (C=2) Test Accuracy:** 97.37%

### Exploratory Data Analysis  
<p align="center">
  <img src="https://github.com/user-attachments/assets/060702a1-9aed-44de-95b1-a80e38d66165" alt="pairplot_species" width="800" />
</p>

### Model Prediction Accuracy on Test Data  
<p align="center">
  <img src="https://github.com/user-attachments/assets/4827a19a-a908-4f86-aaa3-ef2643227cd3" alt="test_predictions_correct_incorrect" width="600" />
</p>

### Confusion Matrix of SVM Model on Test Data  
<p align="center">
  <img src="https://github.com/user-attachments/assets/59a7309c-1f65-47e7-9bec-ee91b22ca816" alt="svm_confusion_matrix" width="600" />
</p>


