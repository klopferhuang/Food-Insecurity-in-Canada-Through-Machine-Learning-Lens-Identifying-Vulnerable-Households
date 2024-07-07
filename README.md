# Food Insecurity in Canada Through Machine Learning Lens: Identifying Vulnerable Households

## Introduction

This research tackles predicting household food insecurity in Canada using machine learning tech- niques. Specifically, we leveraged ensemble methods and regularisation to predict food insecurity using the Canadian Income Survey (CIS) 2018 dataset. The most effective model was the Reg- ularised Random Forest, which outperformed others in recall rate and test accuracy. Notably, this model demonstrated consistency and reliability when applied to the 2019 CIS data. 

Feature importance measures revealed key factors influencing food insecurity, such as the age of the oldest household member, provincial tax credits, and education level of the primary earner. The study’s findings provide a foundation for policy prioritisation and decision-making, emphasizing the poten- tial of machine learning in predicting food insecurity and informing effective interventions in the context of developed countries such as Canada.

You can view the [full article](https://github.com/klopferhuang/Food-Insecurity-in-Canada-Through-Machine-Learning-Lens-Identifying-Vulnerable-Households/blob/main/Predictive%20Modeling%20of%20Food%20Insecurity%20Severity%20in%20Canadian%20Households.ipynb) at here.

## Methodology
The repository includes the following steps and components:

[1. **Exploratory Analysis**: Initial data exploration and visualization](https://github.com/klopferhuang/Food-Insecurity-in-Canada-Through-Machine-Learning-Lens-Identifying-Vulnerable-Households/blob/main/Explanatory%20Analysis.ipynb).
[2. **Data Imputation**: Handling missing data in the dataset](Imputing Data.ipynb).
3. **Logistic Model**: Building and evaluating a logistic regression model (`logistic_model.py`).
4. **Decision Tree**: Building and evaluating a decision tree model (`decision_tree.py`).
5. **Random Forest**: Building and evaluating a random forest model (`random_forest.py`).
6. **Gradient Boosting**: Building and evaluating a gradient boosting model (`gradient_boosting.py`).
7. **Regularization with Random Search and Grid Search**: Optimizing models using regularization techniques (`regularization_search.py`).
8. **SHAP Value Analysis**: Analyzing feature importance using SHAP values for the best-performing model (`shap_analysis.py`).
9. **Robustness Test**: Testing the model's robustness using the 2019 CIS data (`robustness_test.py`).

