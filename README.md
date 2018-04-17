# README

## Project Summary

Do the labs from '[An Introduction to Statistical Learning](http://www-bcf.usc.edu/~gareth/ISL/index.html)' book, in Python. (The labs are done in R in the book.) The book is available for free download on the author's [website](http://www-bcf.usc.edu/~gareth/ISL/index.html) along with slides, video tutorials, and some datasets.

## Data

The labs require the datasets listed below. These datasets are available on the [CRAN GitHub repo](https://github.com/cran/ISLR/tree/master/data).

* `Auto`: Gas mileage, horsepower, and other information for cars.
* `Boston`: Housing values and other information about Boston suburbs.
* `Caravan`: Information about individuals offered caravan insurance.
* `Carseats`: Information about car seat sales in 400 stores.
* `College`: Demographic characteristics, tuition, and more for USA colleges.
* `Default`: Customer default records for a credit card company.
* `Hitters`: Records and salaries for baseball players.
* `Khan`: Gene expression measurements for four cancer types.
* `NCI60`: Gene expression measurements for 64 cancer cell lines.
* `OJ`: Sales information for Citrus Hill and Minute Maid orange juice.
* `Portfolio`: Past values of financial assets, for use in portfolio allocation.
* `Smarket`: Daily percentage returns for S&P 500 over a 5-year period.
* `USArrests`: Crime statistics per 100,000 residents in 50 states of USA.
* `Wage`: Income survey data for males in central Atlantic region of USA.
* `Weekly`: 1,089 weekly stock market returns for 21 years.

## Requirements

```shell
$ pip install -r requirements.txt
```

## Work Summary

3 Regression:  
  * Simple Linear Regression:
    * Coefficient of Determination
    * Residual Plot
  * Multiple Linear Regression:
    * Non-linearity
    * Heteroscedasticity
    * Leverage Statistic
    * Studentized Residuals
    * Correlation Heatmap
    * Variance Inflation Factor (VIF)

4 Classification:  
  * Logistic Regression:
      * Confusion Matrix
      * Sensitivity
      * Precision
      * F1 score
  * K-Nearest Neighbors (KNN)   
  ~~* Linear Discriminant Analysis~~   
  ~~* Quadratic Discriminant Analysis~~  

5 Resampling Methods:  
  ~~* Validation Set~~  
  ~~* Leave-One-Out Cross-Validation~~  
  ~~* k-fold Cross-Validation~~  
  ~~* Bootstrap~~  

6 Linear Model Selection and Regularization:  
7 Moving Beyond Linearity:  

8 Tree-Based Methods:
  * Decision trees  
  ~~* Bagging~~  
  ~~* Random Forests~~  
  ~~* Boosting~~

9 Support Vector Machines:  

10 Unsupervised Learning:
  * Principal Component Analysis (PCA)
  * K-Means Clustering  
  * Hierarchical Clustering  
  ~~* Gaussian Mixture Models (GMM) Clustering~~  
  ~~* Spectral Clustering~~    
  ~~* Mean-Shift Clustering~~  
  ~~* DBSCAN~~
