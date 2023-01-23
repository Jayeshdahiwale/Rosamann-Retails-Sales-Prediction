# RegressionCapstoneProjectII
This report looks at store and sales data for Rossmann drug stores, a large drug store chain that operates several thousand stores all across Europe (Rossmann Store Sales, 2015). It looks at data covering more than a thousand stores, with information ranging from store model, distance from competitor stores, to promos currently running. It also looks at the number of customers and number of sales for each store on a daily level over a period of more than two and a half years.

## Table of Content
  * [Project Summary](#project-summary)
  * [Business Objective](#business-objective)
  * [Dataset](#dataset)
  * [Project Structure](#project-structure)
  * [Conclusion](#conclusion)

## Project Summary
Rossmann operates over 3,000 drug stores in 7 european countries. So our porject aim is to predict their daily sales for upto six weeks in advance. Stores sales are influenced by many factors, including promotions, competitions,school and state holidays, seasonality and locality. So In this project we have been provided the data from 1,500 Rossmann stores. So our task is to forecast the "Sales" column for the test

Provided there are two datasets, one is Store dataset having 1,115 observations in it with 10 columns and It gives us static information about each store such as the model and assortment of the store, information about the nearest competitor store, and whether or not they participate in the consecutive promotion "Promo2". Largely we're looking at numerical and date data, but Store Type and Assortment are flagged with letters to indicate store models and assorment level, per the variable explanations, as well as the PromoInterval column listing abbreviated months.

Other datatset is about Sales dataset having 1,017,209 observations in it with 9 columns and It gives us static information about each store such as the model and assortment of the store, information about the nearest competitor store, and whether or not they participate in the consecutive promotion "Promo2". Largely we're looking at numerical and date data, but Store Type and Assortment are flagged with letters to indicate store models and assorment level, per the variable explanations, as well as the PromoInterval column listing abbreviated months.

## Business Objective
Increase the number of sales by predicting the rates at optimal rate and finding the best suitalbe condition which attract the customers thereby increasing the profit for the Drug Store.

## Dataset
Provided there are two datasets, one is Store dataset having 1,115 observations in it with 10 columns and It gives us static information about each store such as the model and assortment of the store, information about the nearest competitor store, and whether or not they participate in the consecutive promotion "Promo2". Largely we're looking at numerical and date data, but Store Type and Assortment are flagged with letters to indicate store models and assorment level, per the variable explanations, as well as the PromoInterval column listing abbreviated months.

Other datatset is about Sales dataset having 1,017,209 observations in it with 9 columns and It gives us static information about each store such as the model and assortment of the store, information about the nearest competitor store, and whether or not they participate in the consecutive promotion "Promo2". Largely we're looking at numerical and date data, but Store Type and Assortment are flagged with letters to indicate store models and assorment level, per the variable explanations, as well as the PromoInterval column listing abbreviated months.

## Project Structure
```
├── README.md
├── Data 
│   ├── Rossmann Stores Data.csv
│    ├── store.csv
│
├── model_pickle
│    
├── Regression Capstone Project 2 Report.pdf
│
├── Regression_Capstone_Project_2_Rossamann.ipynb
│   ├── Project Summary
│   ├── Busniess Objective
│   ├── Variable Explaination
│   ├── Multivariate Analysis
│   ├── Import and reading the data
│   ├── Data Summary
│   ├── Merging of Data Resources
│   ├── Summary Statistics
│   ├── Data Cleaning
│       ├── DateTime
│       ├── Duplicates
│       ├── Text and Expected Values
│       ├── Removing Rows and Columns
│       ├── Outliers
│           ├──Sales Outliers
│           ├──Customer Outliers
│           ├──Comeptiontion Distance Outliers
│       ├── Missing Values
│       ├── Adding an UPT column
│       ├──Review of Sumary statistics Post cleaning
│   ├── Exploratory Insights
│   ├── Applying Regression Models
│       ├── Simple Linear Regression
│       ├── Lasso Reularisation
│       ├── Ridge Regularisation
│       ├── Elastic Net Regression
│   
│   ├── Conclusins


```



