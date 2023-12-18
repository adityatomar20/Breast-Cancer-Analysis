### Dataset Overview
The dataset comprises a total of 569 data points with 32 attributes.
The first attribute serves as an ID column, the second is our target variable, and the remaining 30 attributes represent features extracted from digitized images of fine needle aspirates (FNA).
The target variable has two classes: benign and malignant.
Class distribution: 357 benign samples and 212 malignant samples.

### Notebooks Summary
#### Notebook 1: Initial Implementations - [first notebook](https://github.com/additanwar/Breast-Cancer-WDBC-Data-Analysis/blob/main/WDBC_Data_Analysis_1.ipynb)
In this notebook, I have laid the groundwork with basic implementations of four classification algorithms:

#### Majority Classification (Benchmark):

Establishing a baseline for performance comparison.
##### KNN (K-Nearest Neighbors):
Utilizing the KNN algorithm for classification.

##### Decision Tree:
Implementing a Decision Tree classifier.

##### Logistic Regression:
Applying Logistic Regression for Predictive Modeling.

#### Notebook 2: Hyperparameter Tuning - [second notebook](https://github.com/additanwar/Breast-Cancer-WDBC-Data-Analysis/blob/main/WDBC_Data_Analysis_2.ipynb)
Building upon the initial implementations, the second notebook introduces hyperparameter tuning for enhanced model performance. The following algorithms undergo optimization:

##### KNN (K-Nearest Neighbors):
Fine-tuning hyperparameters using Bayesian Search.

##### Decision Tree:
Optimizing Decision Tree parameters for improved accuracy.

##### Logistic Regression:
Refining Logistic Regression settings for enhanced predictive power.
##### SVM (Support Vector Machine):
Implementing hyperparameter tuning to optimize SVM model performance.

#### Lift Curve
<img width="617" alt="image" src="https://github.com/additanwar/Breast-Cancer-WDBC-Data-Analysis/assets/85642859/dba2578f-8bc7-4ae2-a92a-cb773f6d296a">

### Conclusion
This dual-notebook analysis provides a comprehensive exploration of breast cancer diagnostic predictions. From initial algorithm implementations to advanced hyperparameter tuning, the project aims to enhance predictive accuracy and identify the most effective model for distinguishing between benign and malignant breast masses.
