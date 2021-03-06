# Housing_Prices_Prediction

**XGBoosted Tree Regression.**

My contribution to the [Housing Prices Competition](https://www.kaggle.com/c/home-data-for-ml-course) on Kaggle.

#### Current Score (MAE): 
14930.20588

[Housing Prices](https://github.com/Josep-at-work/Housing_Prices_Prediction/blob/master/Housing%20Prices%20v0.ipynb) is the result of all the new concepts I've learnt in the [introductory](https://www.kaggle.com/learn/intro-to-machine-learning) and [intermediate](https://www.kaggle.com/learn/intermediate-machine-learning) ML micro-courses on Kaggle. 

## Key concepts:
+ List/Dict comprehension.
+ Imputation of missing values with `SimpleImputer()` method from sklearn.
+ One-Hot Encoding of categorical variables with `OneHotEncoder` class of sklearn.
+ Ensemble the preprocessing concepts with `ColumTransformer` from sklearn.
+ Use Cross-Validation on the hyperparameter searching step. 
+ Optimized a XGBoost Regression model for the prediction of sale prices. Used the implementation of the scikit-learn API.
+ With the `Pipeline` class from sklearn I've ensambled the preprocessing steps with the model.
+ Data Leakage
