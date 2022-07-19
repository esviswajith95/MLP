# MLP - Class notebooks

This is a collection of Jupyter notebooks I prepared while attending [Machine Learning Practice Course](https://onlinedegree.iitm.ac.in/course_pages/BSCCS2008.html) from [IIT Madras Online Degree Programme in Data Science and Programming](https://onlinedegree.iitm.ac.in/index.html)(Diploma Level).

The course focuses on practical implementation of machine learning algorithm using scikit-learn APIs. 

**Running Examples**
* California housing prediction for regression tasks.
* MNIST Digit recognition for classification tasks

## Table of contents

### Week 1
* Data loading
  * Basic data loading/generation features(load, fetch, make)
  
### Week 2
* Data preprocessing
  * Data cleaning
    * Feature Exraction - `DictVectorizer`
    * Data Imputation - `SimpleImputer`, `KNNImputer`
    * Feature Scaling - `MaxAbsoluteScaler`, `MinMaxScaler`, `StandardScaler`, 
  * Feature transformations
    * Polynomial Features - `PolynomialFeatures`
    * Discretization - `KBinsDiscretizer`
    * Handling categorical variables - `OrdinalEncoder`, `OneHotEncoder`, `LabelEncoder`, `MultiLabelBinarizer`, `pandas.get_dummies`, `add_dummy_feature`
    * Custom Transformers - `FunctionTransformer`
    * Composite Transformers - `ColumnTransformer`, `TransformedTargetRegressor`
  * Feature Selection
      * Filter based methods - `VarianceThreshold`, `SelectKBest`, `SelectPercentile`, `GenericUnivariateSelect`
      * Wrapper based Methods - `RFE`, `SelectFromModel`, `SequentialFeatureSelector`
  * Feature extraction
      * PCA - `PCA`
  * Pipeline - `Pipeline`, `make_pipeline`, `FeatureUnion`
  * Hyper Parameter tuning and Cross validation - `GridSearchCV`, `RandomizedSearchCV`
  * Handling imbalance(`imblearn`) -  `RandomUnderSampler`, `RandomOverSampler`, `SMOTE`
  
### Week 3
* Baseline models
  * How to build simple baseline models
* Linear Regression
  * Normal equation method(`LinearRegression`)
  * Iterative optimisation method(`SGDRegressor`)
### Week 4
* California Housing Prediction
  * Exploratory data Analysis
  * Regularised Linear regression and Hyper parameter tuning 
### Week 5
* Perceptron
  * Binary Classification
  * Multiclass Classification
### Week 6
* Logistic regression
* Naive Bayes models
### Week 7
* K Nearest Neighbour model
  * Classification 
  * Regression
* Training Large Scale ML Models
  * Learning in batches(`partial_fit()`)
### Week 8
* Softmax Regression
* Support Vector Machines
### Week 9
* Decision trees
### Week 10
* Bagging and Boosting
* RandomForest
### Week 11
* Clustering
  * K Means
  * Heirarchical Agglomerative Clustering
### Week 12
* Multi-layer Perceptron
