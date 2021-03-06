# Kaggle-Titanic Project
The sinking of Titanic is one of the most infamous shipwrecks in history. 1502 out of 2224 passengers and crew were killed in this tragedy. The main reason leading to such loss of life was that there were not enough lifeboats for all the people. Although there was some element of luck involved in surviving the sinking, some groups of people were more likely to survive than others, such as women, children, and the upper-class.

In this project, I try to analyze what sorts of people were likely to survive and apply the tools of machine learning to predict which passengers survived the tragedy.

## Table of Contents
* [Summary](#summary)
* [Data](#data)
* [Result](#result)
* [Dependencies](#dependencies)
* [Reference](#reference)

## Summary
Predict the survival of passengers in testing data based on training data.<br>
* Worked on various phases of data science project like data analysis, data cleaning, and model building
* Model building(Random Forest, Deep Learning) with Scikit-learn, TensorFlow and Keras

## Data
train.csv: 891 passengers with 12 attributes, including the labels (survived or dead)<br>
test.csv: 418 passengers with 11 attributes

Data analysis: [Data_analysis.ipynb](Data_analysis.ipynb)

## Result
training accuracy: 83%<br>
testing accuracy: 80%<br>
around top 10% of all the participating team

ML model train and predict: [Model_Prediction.ipynb](Model_Prediction.ipynb)

## Dependencies
* numpy
* pandas
* scikit-learn
* seaborn
* matplotlib
* TensorFlow
* Keras

## Reference
Kaggle-Titanic: [here](https://www.kaggle.com/c/titanic).
