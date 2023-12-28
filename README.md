Task 1: Predict the Percentage of a Student Based on Study Hours using Linear Regression algorithm as it involves 2 variables.It is done by using python programming langauge.What will be the predicted score if the student studies for 9.25 hours per day?
install and import required libraries like pandas(data cleaning library),numpy(linear algebra library),matplotlib(basic visualization library).
DATA COLLECTION:The dataset is loaded from a EXCEL file, and it will have two columns: 'Hours' and 'Percentage'
DATA UNDERSTANDING:It is done by correlation coefficient,shape(),describe(),info()
SPLIT THE DATA INTO INPUT AND OUTPUT as this X and y
SPLIT THE DATA INTO TRAINING AND TESTING using from sklearn.model_selection import train_test_split
ML TRAINING using linear regression algorithm(y=mx+c).Here we have known coefficients and intercepts
ML TESTING as y_pred=model.predict(X_test)
Let's plot our data points on 2-D graph to eyeball our dataset and see if we can manually find any relationship between the X_test,y_test and X_test,y_pred
EVALUATE THE MODEL-train accuracy and test accuracy using from sklearn.metrics import r2_score
Now we will predict score if the student studies for 9.25 hours per day using new_score = model.predict(new_hours)
Results
The model is trained on the dataset, and the mean absolute error is calculated to evaluate its performance. Additionally, the script predicts the percentage score for a student who studies for 9.25 hours per day.
