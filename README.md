# SOEN471-Big-Data

Abstract

The covid-19 pandemic has led to an immense loss around the globe affecting the health care system, food system, global economy and not the least, people's mental health. There have been millions of deaths around the world. The lockdowns imposed across the world took a huge toll on the global economy. In this project, we aim to explore the impact of Covid-19 on the global economy.  The dataset chosen shows the economical impact of this pandemic in 170 countries. The overall size of the data is 9.56 mb consisting of raw data (5.54 mb) and transformed data (4.03 mb). The latest information on the economy is till October 18th, 2020. The transformed data file contains 9 columns: code, country, date, human development index, total cases, total deaths, stringency index, population and GDP per capita. On the other hand, the raw data file contains 14 columns (9 columns are same as transformed data file), whereas the data is not well defined in 5 columns.

We will analyse the dataset and will perform predictive analysis on the dataset to forecast the impact on the GDP per capita after October 2020 by taking all the parameters into account.

Introduction :

The novel coronavirus ( Covid-19) has led to the economic downfall of countries around the world. Due to lockdowns, the economy of the countries has been badly affected. While some countries like New Zealand have successfully managed to control the virus, countries like Italy, US etc have not been able to manage the coronavirus and have imposed stringent lockdowns to control the virus which has led to a huge economic impact on the countries. So, in this project, we want to analyse the data of several countries collected during the Covid pandemic to predict the future GDP per capita.

In this project, we will be using multiple polynomial regression analysis that falls under the category of Supervised machine learning. This project is based on the data of several countries collected during the Covid pandemic. This data includes the daily extent of effect of Covid on countries including human development index, number of people dead, number of total cases for Covid, stringency_index (definition from google - It is a computable measure that indicates the effectiveness of a lockdown in the country), population and GDP per capita. The objective is to analyse the data (input - human development index, number of people dead, number of total cases for Covid, stringency_index and population and output - GDP per capita) of the countries and train the model using 80% of this data. Then, we will test our model using the remaining 20% of this data to check the accuracy of our model in predicting the GDP of the countries over the next few days. This will also help us in predicting the future GDP patterns in case of another pandemic like situation. 

Summary of tools and technologies to be used - We will be using multiple polynomial regression algorithm technique that falls under supervised machine learning. For language, we will be using python version 3.5. We will use the Scikit-learn library of python language.


Materials and Methods-

Dataset - The overall size of the data is 9.56 mb consisting of raw data (5.54 mb) and transformed data (4.03 mb). We will be using the transformed dataset as it does not include irrelevant columns.  We will use 70% of this dataset to be the training data set and the remaining 30% will be used as the testing dataset. If after testing, the predicted results are still not close to the test data, we will increase the percentage of data included for training dataset to 80% and the testing dataset would be reduced to 20%. The dataset is available at "https://www.kaggle.com/shashwatwork/impact-of-covid19-pandemic-on-the-global-economy". The latest information on the economy is till October 18th, 2020. 

Technologies - 

Algorithms - 
