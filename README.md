# Statistical Data Analysis: Data Clustering PCA and Regression
This projects performs a statistical analysis of a nutritional dataset containing various sweet products

## Methodology & Results:
### 1. EDA, Data Transformation and PCA
* variable distribution and severe skewness
* tested normality QQ-plot and shapiro-wilk
* applied data transformations to mitigate non-normality and skewness
* performed both classical and robust PCA
### 2. Clustering and Multiple Linear Regression
* cluster tendency using Euclidean and Manhattan dissimilarity matrices, then compared PAM and AGNES
* built a multiple linear regression model to predict energy content
* checked for multicollinearity using VIF
* performed model selection via Forward Selection based on AIC

## Tools:
* **Language:** R
* **Libraries:** `car`, `moments`, `cluster`, `robustbase`, `factoextra`, `caret`, `MASS`
* **Core competencies:** Data Wrangling, Box-Cox Transformation, K-medoids Clustering, Hierarchical Clustering, Robust PCA, Mahalanobis Distance, Multiple Linear Regression, AIC Model Selection, Residual Diagnostic
## Repository Contents:
* `EDA and Robust PCA.pdf`: Rmarkdown PDF containing exploratory data analysis and robust PCA 
* `EDA and Robust PCA.Rmd`: Rmarkdown R code containing exploratory data analysis and robust PCA
* `Clustering and Multiple Regression.pdf`: Rmarkdown PDF containing clustering and multiple regression
* `Clustering and Multiple Regression.Rmd`: Rmarkdown R code containing clustering and multiple regression
