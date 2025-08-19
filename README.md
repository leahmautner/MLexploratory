# Project
Music & Mental Health: using machine learning methods to assess if musical preferences predict self-reported depression scores 

# Methods
Following brief descriptive statistics and data visualization, the sample contained 716 individuals and 25 features. The following regression models were fit on a 70% training set and evaluated on a 30% test set: OLS linear regression (null & full), ridge regression (L2 penalty; tuned via 10-fold CV), lasso regression (L1 penalty; tuned via 10-fold CV, decision tree pruned using CV deviance, random forest, KNN regression with 10-fold CV. Model performances assessed using R^2 and MSE for train and test.

# Key Findings 
Full and operationalized models only slighlty outperform the null, and no model was able to explain more than 5% of variance in depression severity score. Non-parametric models slightly outperform linear, suggesting subtle nonlinear patterns. Although overall predictie performance was subpar, the stability of specific predictors (i.e., metal, rock, country) is notable. 
