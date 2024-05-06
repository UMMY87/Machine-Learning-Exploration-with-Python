# Machine Learning Exploration with Python

This repository contains a Python code snippet that explores various aspects of machine learning, including linear regression, polynomial regression, and binary classification using neural networks. Below is a breakdown of the key points covered in the code:

## Linear Regression:
- The code begins by importing necessary libraries and loading the dataset from a text file.
- It splits the dataset into training, cross-validation, and test sets.
- Features are scaled using z-score normalization.
- A linear regression model is trained using the scaled training set.
- Mean Squared Error (MSE) is computed for both training and cross-validation sets.

## Polynomial Regression:
- Polynomial features are added to the dataset, increasing the complexity of the model.
- The dataset is scaled again using z-score normalization.
- Linear regression is performed on the transformed dataset.
- Training and cross-validation MSEs are computed for polynomial models of degrees ranging from 1 to 10.
- The degree of polynomial with the lowest cross-validation MSE is selected.

## Neural Network Classification:
- The dataset for binary classification is loaded and split into training, cross-validation, and test sets.
- Features are scaled using z-score normalization.
- Binary classification is performed using neural networks with varying architectures.
- Training and cross-validation classification errors are computed for each model.
- The model with the lowest cross-validation error is selected.
- Test set classification error is computed for the selected model.

## Model Evaluation and Selection:
- Model performance is evaluated using metrics such as MSE for regression tasks and classification error for binary classification.
- Cross-validation is utilized to assess the generalization performance of the models.
- The model with the lowest cross-validation error is selected for further evaluation on the test set.
- Test set performance is computed to validate the selected model's performance on unseen data.

## Visualization:
  Throughout the code, various visualizations are used to illustrate the dataset, model performance, and errors.
- **Plot Data of file data_w3_ex1**
![Plot-dataset](https://github.com/UMMY87/Machine-Learning-Exploration-with-Python/assets/117314436/1c488024-9fb8-44e7-871d-11fa0eb02584)

- **Plot Training CV Test Data of file data_w3_ex1**
![Plot-training-cv-test-data](https://github.com/UMMY87/Machine-Learning-Exploration-with-Python/assets/117314436/9231bda8-91b3-4304-b665-443c7a37d3fa)

- **Plot Scaled Data of file data_w3_ex1**
![Plot-Scaled-Data](https://github.com/UMMY87/Machine-Learning-Exploration-with-Python/assets/117314436/eea198c7-383e-4e28-8df8-4d5783667703)

- **Plot MSEs**
![Plot-MSEs](https://github.com/UMMY87/Machine-Learning-Exploration-with-Python/assets/117314436/5630e879-3073-4ba7-ac36-461f317ea763)

- **Plot Data x1 vs x2 of file data_w3_ex2**
![Plot-data-x1-vs-x2](https://github.com/UMMY87/Machine-Learning-Exploration-with-Python/assets/117314436/443aa5ea-7568-49e4-9b01-d5b866dfab9f)


In summary, this code provides a comprehensive exploration of regression and classification tasks using both traditional machine learning techniques (linear regression) and deep learning (neural networks). It demonstrates data preprocessing, model training, evaluation, and selection processes, making it a valuable learning resource for practitioners and enthusiasts in the field of machine learning.
