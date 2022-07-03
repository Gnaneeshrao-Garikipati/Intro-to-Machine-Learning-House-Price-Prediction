### INTRODUCTION 
This is the first dataset we are handling after learning the introduction to machine learning. 
   1. This dataset is from kaggle which is a competition and is still active. 
   2. ### LINK TO THE COMPETITION : https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques/overview
   3. The goal of this dataset is to predict the sale price of the house. 
   4. This dataset has two csv files they are train and test, features of this dataset are combination of both categorical and numerical. 
   5. Train consists, 1460 rows of house Id's and 80 columns(Features) excluding Id column. 
   6. Test consists 1459 rows and 79 columns excluding Id column(Does not contain Sale Price column which have to be predicted). 
   7. The evaluation of the dataset is based on RMSE(root mean squared error). 
 

### WORKFLOW
This dataset needs a lot of preprocessing as it contains 80 features
   1. First we started droping columns with missing values more than 50%.
   2. We had seperated the data into two datasets i.e., categorical and numerical.
   3. The missing values in categorical data had been filled with previous row data or mode.
   4. The misssing values in numerical data had been filled with previous row or mean.
   5. The categorical values had been converted to numerical values using label encoder.
   6. The categorical and numerical datasets had been concat.
   7. Different models like linear regression, gradient boost, xgboost are used on the dataset.

### SUBMISSIONS
1. Submission 1 : Linear regression has been used on dataset
2. Submission 2 : Gradient boost has been used
3. Submission 3 : Xgboost has been used on dataset
4. Submission 4 : Voting Regressor with preprocessing on dataset

### RESULTS
1. Submission 1 : Rank 3700
2. Submission 2 : Rank 3700 to 3100
3. Submission 3 : Rank 3100 to 1500
4. Submission 4 : Rank 1500 to 1054

###THANK YOU
