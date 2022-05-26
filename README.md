## Hand made Gradient Boosting Machine 
### (Base model - Logistic Regression, Poisson bootsrap)
Enssemble algorithm, written on Python from scratch for binary classification problem.
As a base model Logistic Regression was choicen.

This machine evaluates residuals per estimators.

![](residuals.png)

Provide error estimation.

![](errors.png)

Also evaluate ROC and PRC curves.

![](curves.png)

Cherry on a cake - predictions sampled with a Poisson bootstrap. It allowed to evaluate variance of a model metrics.

![](bootstrap.png)