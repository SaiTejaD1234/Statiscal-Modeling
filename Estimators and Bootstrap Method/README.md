
# Finding Estimators and Confidence Intervals through Boostrap Method
    1. Project Motivation
    2. Objectives
    3. Methods Used
    4. Installation
    5. Data
    6. Implementation
    7. Result
## 1. Project Motivation
An **estimator** is a statistic that estimates some fact about the population. You can also think of an estimator as *the rule that creates an estimate*. **Method of Moments (MoM)** and **Maximum Likelihood Estimation (MLE)** are methods of estimating parameters of a probability distribution given some data. These methods have been the dominating ***means of Statistical Inference***. While these estimators are *prone to bias*, I've included the **Confidence Intervals found using Bootstrap Method**.
##    2. Objectives
*   Obtain a dataset prepare the data for Statistical Modeling
*   Fit a Distribution to the random sample
*   Obtain MoM and MLE Estimators
*   Obtain Confidence Intervals using Bootstrap method
##    2. Objectives
*   Obtain a dataset prepare the data for Statistical Modeling
*   Fit a Distribution to the random sample
*   Obtain MoM and MLE Estimators
*   Obtain Confidence Intervals using Bootstrap method
## 3. Methods Used
* Inferential Statistics
* Data Visualization
* Method of Moments
* Maximum Likelihood Estimation
* Boostrap Method
## 4. Installation
* Python versions 3.*.
* Python Libraries:
    * io
    * Pandas
    * Numpy
    * Matplotlib
    * Seaborn
    * Scipy
## 5. Data
The data has been obtained from U.S. Data and Statistics. These input data files are ***cardio_base.csv*** which is attached above. It contains about *70000 data points* for analysis.
*The csv file containing the data is attached separately.*
## 6. Implementation
In this project I've used *10000 sample points* and fitted a normal distribution to them. Further more equations have been provided in the .ipynb file to calculate MoM and MLE. Bootstrapping has been done and *10000 samples of normal distribution have been created* to find Confidence Intervals.
## 7. Result
The details of the results are shown in the code.
