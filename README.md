# Loan_Prediction
The major aim of this project is to predict which of the customers will have their loan paid or not. we are developing loan prediction system using machine learning, so the system automatically selects the eligible candidates. we are predicting the loan data by using some machine learning algorithms like Decision Tree, Logistic Regression, Random Forest, XGBoost and Support Vector Machine (SVM).
#To determine the loan status, several collections of information from previous loan applicants use various features. This data, which may be static or time-series, can be examined by a machine learning model to estimate the likelihood that the loan would be authorized. Now let's examine a few of these datasets.

Dataset:
In dataset there are 614 rows and 13 columns. 12 independent variable and target variable: (614, 13).
The machine learning model is trained using the training data set. Every new applicant details filled at the time of application form acts as a test data set. On the basis of the training data sets, the model will predict whether a loan would be approved or not. We have 13 features in total out of which we have 12 independent variables and 1 dependent variable i.e. Loan_Status in train dataset and 12 independent variables in test dataset. The Loan_ID, Gender, Married, Dependents, Education, Self_Employed, Property_Area, Loan_Status are all categorical data.

Algorithms:
In this project we have built five different models and tested with data. The five algorithms are:

	Decision Tree
 	Random Forest
	XGBoost 
	Logistic Regression
	Support Vector Machine (SVM)
	
Conclusion:

	 We did Exploratory data Analysis on the features of this dataset and saw how each feature is distributed.

	We analysed each variable to check if data is cleaned and normally distributes

	We cleaned the data and removed NA values 

	We also generated hypothesis to prove an association among the independent variables and the Target variable. And based on the results, we assumed whether or not there is an association. 

	We calculated correlation between independent variables and found that applicant income and loan amount have significant relation.

	 We created dummy variables for constructing the model

	 We constructed models taking different variables into account and found through odds ratio that credit credit history is creating the most impact on loan giving decision 

	Finally, we got a model with coapplicant income and credit history as independent variable with highest accuracy. 

	We tested the data and got the accuracy of 83 %
