# Sparkify-App
![](https://forthebadge.com/images/badges/made-with-python.svg)

## Overview
### Motivation
Honing skills of:  
1. Loading large datasets into Spark and manipulating them using Spark SQL and Spark Dataframes
2. Using the machine learning APIs within Spark ML to build and tune models
3. Integrating the skills I've learned in the Spark course and the Data Scientist Nanodegree program

### Task and Datasets 
Our primary task is to predict churned users based on logs of a music app. The size of original datasets is 12GB. Due to the limited computation power of free version of IBM Cloud, a medium-sized sub-datasets is utilized.

### Frameworks & Libraries
- Pyspark SQL and Pyspark ML

## Summary of Project
1. Data Preprocessing
2. Exploratory Data Analysis
3. Feature Engineering
4. Modeling
5. Evaluation

## Methodology
**LogisticRegression** was implemented to predict the churn of a customer.

**Prediction on test set** - Area under ROC - 0.9333 , Accuracy - 83.87% (After Tuning Hyperparameters)

## View a detailed analysis report on Medium
[Medium Post](https://medium.com/@rowhitswami/customer-churn-prediction-of-a-music-app-using-pyspark-d65b8f5be047)

## Files in the repo
- `sparkify.ipynb` - Analysis in Jupyter Notebook

## Acknowledgement
- Dataset by Udacity
- Jupyter Notebook instruction by Udacity

## License
[![MIT license](http://img.shields.io/badge/license-MIT-brightgreen.svg)](http://opensource.org/licenses/MIT)

**Copyright (c) 2019 Rohit Swami**

This project is licensed under the MIT License - see the LICENSE file for details

