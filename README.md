In this Challenge, various techniques are used to train and evaluate a model based on loan risk. I have used following class activity as a reference:

https://git.bootcampcontent.com/Rutgers-University/PSEG-RUT-VIRT-DATA-PT-10-2023-U-LOLC/-/blob/main/01-Lesson-Plans/20-Supervised-Learning/2/Activities/03-Ins_Decision_Trees/Solved/decision_trees_solution.ipynb?ref_type=heads

**The instructions for this Challenge are divided into the following subsections:**

1. plit the Data into Training and Testing Sets

2. Create a Logistic Regression Model with the Original Data

3. Write a Credit Risk Analysis Report

**Open the starter code notebook and use it to complete the following steps:**

Read the lending_data.csv data from the Resources folder into a Pandas DataFrame.

Create the labels set (y) from the “loan_status” column, and then create the features (X) DataFrame from the remaining columns.



**Create a Logistic Regression Model with the Original Data**

Use your knowledge of logistic regression to complete the following steps:

Fit a logistic regression model by using the training data (X_train and y_train).

Save the predictions for the testing data labels by using the testing feature data (X_test) and the fitted model.

Evaluate the model’s performance by doing the following:

**Generate a confusion matrix.**

**Print the classification report.**

**Answer the following question:** How well does the logistic regression model predict both the 0 (healthy loan) and 1 (high-risk loan) labels?

**Write a Credit Risk Analysis Repor**t
Write a brief report that includes a summary and analysis of the performance of the machine learning models that you used in this homework. You should write this report as the README.md file included in your GitHub repository.

Structure your report by using the report template that Starter_Code.zip includes, ensuring that it contains the following:

**An overview of the analysis: Explain the purpose of this analysis.**
Prpose of this analysis is to get train the model so that it can predict low risk and high risk loans based on other fators such as income, interest rate, loan size, total debt. Data has been split onto training data and test data. Based on training data we are checking how accurate test data would perform to prdict low risk and high risk loans. Please refer jupiter notebook for code. We are using linear regression model in this case. Linear regression is an algorithm that provides a linear relationship between an independent variable and a dependent variable to predict the outcome of future events.

**The results: Using a bulleted list, describe the accuracy score, the precision score, and recall score of the machine learning model.**

Precision can be seen as a measure of quality, and recall as a measure of quantity. Higher precision means that an algorithm returns more relevant results than irrelevant ones, and high recall means that an algorithm returns most of the relevant results (whether or not irrelevant ones are also returned).

A summary: Summarize the results from the machine learning model. Include your justification for recommending the model for use by the company. If you don’t recommend the model, justify your reasoning.
