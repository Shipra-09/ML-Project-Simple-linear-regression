# Prediction-with-regression
Using simple linear regression: (i) Predicting the delivery time using the sorting time data. (ii) Predicting the salary hike using year of experience data. 
Exploring Insights/Inferences by performing EDA on the given data. Relevant graphs were plotted to get some insights on data using seaborn package. Model fitting via linear regression by Importing sklearn package. Selecting the best fitted model via python programming.   

Delivery Time data Probelm: 
File name: Project-SimpleReg-Delivery-Time.ipynb

(a) EDA concluded that the distribution of delivery time and sorting time is normally distributted since skewness lies between -1 and 1
(b) Box plot shows that there are no outliers present in the data.
(c) Scatter plot shows that Delivery time does depend on sorting time but only to certain extent, since for the same sorting time there are different delivery time that means it also depend on other parameters.
(d) Delivery time and sorting time are moderately correlated since correlation came out to be 82%.
(e) The model data is then divided into train and test data by importing train_test_split from sklearn.model_selection package.
(f) The model data is then fitted by importing linear regression from sklearn.linear_model
(g) The fitted model is then used for the prediction of values which is done using the test data.
(h) The error is calculated by importing r2_score, mean_squared_earror from sklear.metrics
(i) The strength of the model is came out to be 0.697 which is strong.
(j) The RMSE came out to be 1.739.
(k) The model is saved by importing joblib package (Delivery_Prj1)

Salary Hike data Probelm: 
File name: Project-SimpleReg-Salary-Hike.ipynb

(a) EDA concluded that the distribution of years of experience and salary hike is normally distributted since skewness lies between -1 and 1
(b) Box plot shows that there are no outliers present in the data.
(c) Scatter plot shows that hike in Salary does depend on the years of experience.More is the experience, larger is the salary hike.But it also depend on other parameters, may be efficiency of the employee or other factors.
(d) years of experience and salary hike are strongly correlated since correlation came out to be ~98%.
(e) The model data is then divided into train and test data by importing train_test_split from sklearn.model_selection package.
(f) The model data is then fitted by importing linear regression from sklearn.linear_model
(g) The fitted model is then used for the prediction of values which is done using the test data.
(h) The error is calculated by importing r2_score, mean_squared_earror from sklear.metrics
(i) The strength of the model is came out to be 0.96 which is very strong.
(j) The RMSE came out to be 5591.6.
(k) The model is saved by importing joblib package (Salary_Prj1)
