# Anemia Prediction in Nigeria using Classification Models

## Overview

This repository hosts a machine learning project focused on predicting anemia prevalence in Nigeria using various classification models. The primary goal is to explore the dataset, implement and evaluate different machine learning algorithms, and provide insights into the factors influencing anemia.

## Project Motivation

Anemia is a critical health concern, especially in developing countries. Accurate prediction models can aid in identifying at-risk populations and inform targeted healthcare interventions. This project leverages machine learning to contribute to the understanding and mitigation of anemia in Nigeria.

## Dataset

The dataset utilized in this project was obtained from Kaggle ([Dataset Link](https://www.kaggle.com/datasets/adeolaadesina/factors-affecting-children-anemia-level)). It includes relevant features related to health, nutrition, and socio-economic factors that may influence the prevalence of anemia.

## Model Performance

The project includes the implementation of several classification models, with the following accuracy results:

- **Baseline Model Accuracy:** 0.61
- **Logistic Regression Accuracy:** 0.82
- **Decision Tree Accuracy:** 0.97
- **Random Forest Accuracy:** 0.97
- **Gradient Boosting Accuracy:** 0.72

These accuracy scores provide a quantitative measure of each model's effectiveness in predicting anemia.

## Project Structure

### Exploratory Notebook

- [exploration.ipynb](Data_Exploration/Data_Exploration.ipynb): This notebook dives into the dataset, providing comprehensive data exploration, visualization, and insights. It serves as a foundation for subsequent modeling efforts.

### Model Notebooks

- [logistic_regression.ipynb](Models/Logistic_Regression.ipynb): The Logistic Regression model notebook, detailing its implementation, hyperparameter tuning, and performance evaluation.

- [decision_tree.ipynb](Models/Decision_Trees.ipynb): The Decision Tree model notebook, showcasing its decision-making process, visualization, and performance metrics.

- [random_forest.ipynb](Models/Random_Forest.ipynb): The Random Forest model notebook, covering ensemble learning, feature importance, and accuracy assessment.

- [gradient_boosting.ipynb](Models/Gradient_Boosting.ipynb): The Gradient Boosting model notebook, demonstrating boosting techniques, hyperparameter tuning, and model evaluation.

### Confusion Matrices

- Confusion matrices are provided for each model, offering a detailed breakdown of true positive, true negative, false positive, and false negative predictions. These matrices facilitate a deeper understanding of model performance.

## Conclusion
The DEcision Tree Classifier as well as the Random Forest Classifier showed better accuracy , hence these models can be used for prediction.

The hemoglobin levels at different altitudes offer valuable insights into the overall health condition of individuals. There is a distinct correlation between smoking and hemoglobin levels, suggesting that this habit has an impact on hemoglobin.
