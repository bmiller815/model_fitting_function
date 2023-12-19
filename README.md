# model_fitting_function

In this class project, I built an R function, my_glm2, that manually fits generalized linear models (GLM) to any given data frame and formula input. This function was required to be created without the use of existing model fitting functions, providing a fun and unique challenge. The function supports linear, logistic, and Poisson regression models, providing users with detailed regression tables, model family information, Fisher scoring iterations, and deviance values.

To construct my_glm2, I developed multiple helper functions, each tailored to a specific model family type. Within these helper functions, I implemented self-built Fisher scoring algorithms and performed manual calculations for standard errors, test statistics, and p-values. The process involved extensive utilization of linear algebra techniques to manually compute every facet of the output. For a more in-depth understanding, additional details are available within the project code.

**Features**

+ **Flexible Model Fitting**: Fit linear, logistic, or Poisson regression models using your data frame and formula input.
+ **Customizable Iterations**: Specify the maximum number of iterations for Fisher scoring.
+ **Comprehensive Output**: Retrieve regression tables with coefficients, standard errors, test scores, and p values.
+ **Detailed Model Information**: Obtain the model's family, the number of iterations used, and the model's deviance.
