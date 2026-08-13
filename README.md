# Gradient Boosting Classification

## :pushpin: Project Overview

In this project, I implemented the Gradient Boosting Classifier using Python and Scikit-learn.

Gradient Boosting is an ensemble learning algorithm that builds models sequentially, where each new model tries to improve the mistakes made by the previous models.

## :bar_chart: Dataset

For this project, I used the Breast Cancer Wisconsin dataset, which is available directly through Scikit-learn.

I used a built-in dataset to make the project easier to practice and reproduce without downloading an external dataset.

The dataset contains numerical features related to breast cancer cases and is used for binary classification.

## 🤖 Algorithm

The main algorithm used in this project is:

Gradient Boosting Classifier

Gradient Boosting combines multiple decision trees sequentially to create a stronger predictive model.

## :arrows_counterclockwise: Cross-Validation

I used 5-Fold Cross-Validation on the training data to get a more reliable estimate of the model's performance.

The test set was kept separate and was used only for the final evaluation.

## ⚙ Important Parameters

Some of the important Gradient Boosting parameters explored in this project are:

- n_estimators → Number of boosting stages
- learning_rate → Controls the contribution of each tree
- max_depth → Controls the maximum depth of the individual trees
- random_state → Makes the results reproducible

## :straight_ruler: Feature Scaling

Feature scaling was not required for this model.

Gradient Boosting is based on decision trees, and tree-based models generally do not require feature scaling in the same way that distance-based or gradient-based algorithms such as KNN or SVM may.

## :chart_with_upwards_trend: Results

The model achieved approximately:

- Cross-Validation Mean: 95%
- Test Accuracy: 94%

The results show that the model performed well on both the cross-validation folds and the unseen test data.

## 🛠 Libraries

- Python
- NumPy
- Pandas
- Matplotlib
- Scikit-learn

## :dart: What I Practiced

Through this project, I practiced:

- Gradient Boosting
- Ensemble Learning
- Train/Test Split
- Cross-Validation
- Classification
- Model Evaluation
- Hyperparameter exploration
- Understanding tree-based models

## :books: Purpose

This project was created as part of my machine learning practice to better understand different supervised learning algorithms and their parameters.

