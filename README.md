Linear regression (LR) is a method used to model the linear relationship between a dependent variable (target) and one or more independent variables (predictors). 
Observed data: Y=mx+c or Y=m1x1+m2x2+…+mpxp+c+error
Predicted data: Y’=m1x1+m2x2+…+mpxp+c
Error: 		     error=Y-Y’

The MLR model is based on several assumptions (e.g., errors are normally distributed with zero mean and constant variance). Provided the assumptions are satisfied, the regression estimators are optimal in the sense that they are unbiased, efficient, and consistent. 

Unbiased means that the expected value of the estimator is equal to the true value of the parameter. 
Efficient means that the estimator has a smaller variance than any other estimator. 
Consistent means that the bias and variance of the estimator approach zero as the sample size approaches infinity.

How good is the model?		
R2 also called as coefficient of determination summarizes the explanatory power of the regression model and is computed from the sums-of-squares terms.
R2 describes the proportion of variance of the dependent variable explained by the regression model. If the regression model is “perfect”, SSE is zero, and R2 is 1. If the regression model is a total failure, SSE is equal to SST, no variance is explained by regression, and R2 is zero. It is important to keep in mind that there is no direct relationship between high R2 and causation.

Model Selection		
A frequent problem in data mining is to avoid predictors that do not contribute significantly to model prediction. First, It has been shown that dropping predictors that have insignificant coefficients can reduce the average error of predictions. Second, estimation of regression coefficients are likely to be unstable due to multicollinearity in models with many variables. Finally, a simpler model is a better model with more insight into the influence of predictors in models.  There are two main methods of model selection:		
Forward selection, the best predictors are entered in the model, one by one.
Backward Elimination, the worst predictors are eliminated from the model, one by one.
