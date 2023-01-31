# Data-Scientist-Salary-Prediction
Here , I have done the project based on topic Data Scientist Salary Prediction in which we have predicted salaries of data scientist based on different features on which salary depends . 
In this project , we have taken dataset from glassdoor jobs .
Here we have done following steps-
#Exploratory Data Analysis & Data Cleaning
1.Plotting bargraphs and countplots for numerical and categorical features respectively.
2.Removing unwanted columns
3.Handling NaN/missing values
4.Removing unwanted alphabet/special characters from the features

#Feature Engineering
1.Creating new features from existing features
2.Trimming Columns
3.Handling ordinal and nominal categorical features
4.Feature Selection

#Model Building & Evaluation
Metric: Negative Root Mean Squared Error (NRMSE)

1.Multiple Linear Regression: -27.523 NRMSE
2.Lasso Regression (L1 Regularization): -27.993 NRMSE
3.Random Forest (Ensemble): -17.637 NRMSE
4.Gradient Boosting: -24.429 NRMSE
5.Voting (Random Forest + Gradient Boosting): -19.136 NRMSE

#Results :
*Random Forest & Gradient Boosting algorithms are selected amongst all the other algorithms because they have the highest value for Negative Root Mean Squared Error 
(NRMSE) i.e. lowest value for Root Mean Squared Error (RMSE) metric. And fed to Voting algorithm to reduce the error!
*Voting algorithm too did not perform well as compared to Random Forest algorithm, hence Random Forest algorithm is selected for predicting the results of this problem statement.
