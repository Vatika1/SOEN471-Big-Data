# SOEN471-Big-Data

Abstract

The covid-19 pandemic has led to an immense loss around the globe affecting the health care system, food system, global economy and not the least, people's mental health. There have been millions of deaths around the world. The lockdowns imposed across the world took a huge toll on the global economy. In this project, we aim to explore the impact of Covid-19 on the global economy.  The dataset chosen shows the economical impact of this pandemic in 170 countries. The overall size of the data is 9.56 mb consisting of raw data (5.54 mb) and transformed data (4.03 mb). The latest information on the economy is till October 18th, 2020. The transformed data file contains 9 columns: code, country, date, human development index, total cases, total deaths, stringency index, population and GDP per capita. On the other hand, the raw data file contains 14 columns (9 columns are same as transformed data file), whereas the data is not well defined in 5 columns.

We will analyse the dataset and will perform predictive analysis on the dataset to forecast the impact on the GDP per capita after October 2020 by taking all the parameters into account.

Introduction 

The novel coronavirus ( Covid-19) has led to the economic downfall of countries around the world. Due to lockdowns, the economy of the countries has been badly affected. While some countries like New Zealand have successfully managed to control the virus, countries like Italy, US etc have not been able to manage the coronavirus and have imposed stringent lockdowns to control the virus which has led to a huge economic impact on the countries. So, in this project, we want to analyse the data of several countries collected during the Covid pandemic to predict the future GDP per capita.

In this project, we will be using multiple polynomial regression analysis that falls under the category of Supervised machine learning. This project is based on the data of several countries collected during the Covid pandemic. This data includes the daily extent of effect of Covid on countries including human development index, number of people dead, number of total cases for Covid, stringency_index (definition from google - It is a computable measure that indicates the effectiveness of a lockdown in the country), population and GDP per capita. The objective is to analyse the data (input - human development index, number of people dead, number of total cases for Covid, stringency_index and population and output - GDP per capita) of the countries and train the model using 80% of this data. For testing purposes, we will test our model using the remaining 20% of this data to check the accuracy of our model in predicting the GDP of the countries over the next few weeks. This will also help us in predicting the future GDP patterns in case of another pandemic like situation. We will be using multiple polynomial regression algorithm technique that falls under supervised machine learning. For language, we will be using python version 3.5. We will use the Scikit-learn library of python language.



Materials and Methods

The chosen dataset displays the impact of covid-19 on the global economy from December 2019 till October 2020 with the columns: iso code, country, date, total cases, total deaths, stringency index, gdp per capita, human development and population. The dataset is available at Impact of Covid-19 Pandemic on the Global Economy | Kaggle consists of raw data and transformed data with a total size of 9.56 MB. 

Supervised machine learning techniques will be used because we want to predict the outcome of covid-19 on the global economy after October 2020. Algorithm to be used is multiple polynomial regression analysis. Multiple polynomial Regression is supervised learning technique where two or more independent variables are used to predict the values of dependent variables. Choosing multiple polynomial regression instead of multiple linear regression will allow us to develop a stronger model by giving a better accuracy. 

Another way to increase the accuracy of the results is to increase the percentage allocated to the training set and decrease the testing set. A general equation can be obtained from the training set by using multiple curves of best fit. The general equation is of the form  y = ax^n + bx^n-1 + …+ c, where y is the value to be predicted, a and b are constants, n is the degree of the equation and c is the value of y when x is equal to 0. The value of n must be chosen precisely since increasing the value of n will increase the complexity of the model as well. Choosing a low value for n will lead to underfitting of the data and choosing a high value of n implies overfitting of the data. Overfitting and underfitting can cause poor performance of the algorithms.

For start, we will allocate 80% to the training set and 20% to the testing set to analyze the data. However, depending on the accuracy of predictions, we may increase the percentage of training data. GDP per capita will be chosen as the dependent variable y. In the case of independent variables, date, human development index, stringency index, total cases, total deaths and population will be chosen. Initially due to lack of knowledge and experience in this field, we will start by choosing second degree polynomial (n = 2). However, if the algorithms have poor performance, we will increase or decrease the polynomial degree depending on the fitting.

Lastly, Scikit learn, a popular machine learning library for python. Fortunately, python provides several methods to find relationships between data points.




References


How regression analysis works:  https://towardsdatascience.com/how-regression-analysis-works-10f44c37b20a

Machine Learning Polynomial regression : https://www.w3schools.com/python/python_ml_polynomial_regression.asp

Polynomial Regression With Scikit-learn : https://towardsdatascience.com/polynomial-regression-with-scikit-learn-what-you-should-know-bed9d3296f2

Overfitting and Underfitting curves
Overfitting and Underfitting With Machine Learning Algorithms (machinelearningmastery.com)
