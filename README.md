# Statistical data analysis with R
R codes for statistical and econometrics models applied to transport data 
 
This R code corresponds with the two most common Random Parameters count regression models: Random Parameters Negative Binomial (RPNB) and Random Parameters Poisson models. Although this code has been written for crash count data, it may be used for any dependent variable that is of count nature (e.g. number of patients at hospitals, animal death counts, etc).

Prior to running the code, make sure to have "maxLik" and "randtoolbox" packages installed. 

The code also includes two global goodness of fit measures (i.e. Mean Absolute Deviance and Mean Squared Predictive Error). Please note that these two measures are used as goodness of fit measures rather than predictive measures.
