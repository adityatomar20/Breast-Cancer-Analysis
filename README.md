# Diagnostic-Breast-Cancer-Data-Analysis

I'll be analyzing data from breast cancer research to predict if a breast mass is benign or malignant. 

### About Data
We have total 569 data points and 32 attributes. 
The first attribute is an ID column, second is our target variable and rest 30 are features of the mass, computed from a digitized image of a fine needle aspirate (FNA). 
The target class distribution for these sample points is 357 benign and 212 malignant.

In the [first notebook](https://github.com/additanwar/Breast-Cancer-WDBC-Data-Analysis/blob/main/WDBC_Data_Analysis_1.ipynb), I have basic implementations of 4 classification algorithms: a Majority classification (Benchmark), KNN, Decision Tree and Logistic Regression.

In the [second notebook](https://github.com/additanwar/Breast-Cancer-WDBC-Data-Analysis/blob/main/WDBC_Data_Analysis_2.ipynb), I have also implemented hyperparameter tuning for these algrithms(, and SVM) using Bayesian Search.

#### Lift Curve
<img width="617" alt="image" src="https://github.com/additanwar/Breast-Cancer-WDBC-Data-Analysis/assets/85642859/dba2578f-8bc7-4ae2-a92a-cb773f6d296a">
