# This report will go through
- Problem/ Description
- Code Preperation
	- Import Packages
- Data
	- Read in data
	- Data information
	- Data Visulization
- Analysis
	- Research Question 1: What Factors Affect Monthly Income?
		- Prepare variables
		- Do partition
		- Fit/ evaluate the model on training data
		- Use the model to obtain predictions on the test data
		- Visualize the predicted vs. actual values
		- Evaluate the model
	- Research Question 2: What Factors Affect An Employee's Decision of Attrition?
		- Prepare variables
		- Do partition
		- Fit/ evaluate the model on training data
		- Marginal effects
		- AIC and BIC
		- ROC curve
- Conclusion

## Problem/Description
Our dataset comes from Kaggle: https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset. It's a fictional dataset conducted by IBM data scienctist to analysis employee attrition and performance. Employee turnover and employee salary estimation can be challenging for HR departments. With this dataset, we plan to help HR departments better manage their employees and hiring processes.
In the first part, we wanted to provide a reasonable way to predict employee salaries. We used a Linear Regression model to predict employees' monthly earnings, explored the impact of different factors, such as age and gender, on monthly earnings, evaluate our models with visualization and MAE. In the second section, we use Generalized Linear Models to predict whether employees will leave, explore what factors contribute to employee turnover, and evaluate our model using AIC, BIC, and ROC curves.
