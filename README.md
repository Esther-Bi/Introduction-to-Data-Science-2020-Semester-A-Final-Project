# Introduction to Data Science 2020 Semester A  Final Project

This is a final project in 'Introduction to Data Science' course.
During the semester we learned about models used to predict outcomes for classification-type problems and regression-type problems.
We learned about the difference between the two types of prediction:
A classification classifies the data according to the classes to which the data belongs (e.g. dog or cat) while a regression predicts some amount (e.g. prediction of apartment prices) and will never be 100% accurate.

Notebook 1 is a solution to questions about probability, base law and random variables.

Notebook 2 is a solution to questions about the Python programming language. In this notebook I was writing codes to solve finding a particular data from a data set etc.

Notebook 3 and Notebook 4 are the notebooks that deal with classification and regression.

Classification:
The purpose of Notebook 3 is to classify whether a person is sick or not with heart disease according to various data such as age, blood pressure, etc. This notebook analyzes the information obtained from the data set to understand the relationship between the various factors and having heart disease.
After understanding the information, there is a use of different models which divide the data into training set and testing set, and after training on the training set the model tests his abilities on the testing set.
There is a comparison between the different models and finally choosing the best one.

Regression:
The purpose of Notebook 4 is to predict the price of a second hand car based on various data such as kilometers, number of years of use, engine horsepower, price on the road, etc. This notebook analyzes the information obtained from the data set to understand the relationship between the various factors and price of the cars, in order to be able to accurately predict the price of the car.
After understanding the information, there is a use of different models which divide the data into training set and testing set, and after training on the training set the model tests his abilities on the testing set.
There is a comparison between the different models and a comparison between taking parts of the data and using them only, in order to perhaps optimize the model.
From the results of the various models it is possible to understand who is the most accurate model for predicting the prices of second hand cars.

Models:

Linear Regression-
Linear regression attempts to model the relationship between two variables by fitting a linear equation to observed data. One variable is considered to be an explanatory variable, and the other is considered to be a dependent variable. For example, a modeler might want to relate the weights of individuals to their heights using a linear regression model.

Random Forest-
Random forest, like its name implies, consists of a large number of individual decision trees that operate as an ensemble. Each individual tree in the random forest spits out a class prediction and the class with the most votes becomes our model�s prediction

Decision Tree-
A decision tree is arriving at an estimate by asking a series of questions to the data, each question narrowing our possible values until the model gets confident enough to make a single prediction. The order of the question as well as their content are being determined by the model. In addition, the questions asked are all in a True / False form.

Logistic Regression-
Logistic regression is a statistical model that in its basic form uses a logistic function to model a binary dependent variable.

KNN-
KNN classifier determines the class of a data point by majority voting principle. If k is set to 5, the classes of 5 closest points are checked. Prediction is done according to the majority class.
