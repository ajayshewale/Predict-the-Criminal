
# Predict-the-Criminal
Hackerearth Problem Link: https://www.hackerearth.com/challenge/competitive/predict-the-criminal/machine-learning/predict-the-criminal/

A simplistic approach to the hackerearth problem: Predict the Criminal. The solution is a starting guide to tackle the problem, there are still plety of methods you can apply in order to acheive high score.


## Problem Statement
There has been a surge in crimes committed in recent years, making crime a top cause of concern for law enforcement. If we are able to estimate whether someone is going to commit a crime in the future, we can take precautions and be prepared. You are given a dataset containing answers to various questions concerning the professional and private lives of several people. A few of them have been arrested for various small and large crimes in the past. Use the given data to predict if the people in the test data will commit a crime. The train data consists of 45718 rows, while the test data consists of 11430 rows.
The evaluation metric is precision score.

## Data Description
Train and Test Data

### Install

This project requires **Python** and the following Python libraries installed:

- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org/)
- [matplotlib](http://matplotlib.org/)
- [scikit-learn](http://scikit-learn.org/stable/)


You will also need to install Jupyter Notebook:
[Jupyter Notebook Tutorial: Introduction, Setup, and Walkthrough](https://www.youtube.com/watch?v=HW29067qVWk)

Here is an excellent link to [How to run Jupyter Notebook](http://jupyter.readthedocs.io/en/latest/running.html)

## This repository contains following files:
- Dataset (Train and Test )

     Criminal_train.csv
     
     Criminal_text.csv 

- Graph

- Jupyter Code

     1 Predict the Criminals with Normal approach.ipynb
     
     2 Predict the Criminals with Feature Extraction.ipynb
     
     3 Predict the criminals with Bagging.ipynb
     
     4 Predict the Criminal with Ensemble Method.ipynb
     
     
 - Notebook PDF (For visualization I uploaded PDF code of the solution)

     1 Predict the Criminals with Normal approach.pdf
     
     2 Predict the Criminals with Feature Extraction.pdf
     
     3 Predict the criminals with Bagging.pdf
     
     4 Predict the Criminal with Ensemble Method.pdf  
     
     
## Solution 
Jupyter Code file contains notebook files where coding part of the problem has been given. It also contains comments on necessary steps.

## Ensemble Methods
Ensemble methods are techniques that create multiple models and then combine them to produce improved results. Ensemble methods usually produces more accurate solutions than a single model would. This has been the case in a number of machine learning competitions, where the winning solutions used ensemble methods.

### Types of Ensembling:

- Bayes optimal classifier.
- Bootstrap aggregating (bagging)
- Boosting.
- Bayesian parameter averaging.
- Bucket of models.
- Stacking.

In given solution I have used Bagging(3rd solution file) and Stacking(4th solution file) ensembling method. Short description of baaging and stacking ensembling method.


1. *Bagging* (stands for Bootstrap Aggregating) is a way to decrease the variance of your prediction by generating additional data for training from your original dataset using combinations with repetitions to produce multisets of the same cardinality/size as your original data. By increasing the size of your training set you can't improve the model predictive force, but just decrease the variance, narrowly tuning the prediction to expected outcome.

2. *Stacking* is a similar to boosting: you also apply several models to your original data. The difference here is, however, that you don't have just an empirical formula for your weight function, rather you introduce a meta-level and use another model/approach to estimate the input together with outputs of every model to estimate the weights or, in other words, to determine what models perform well and what badly given these input data.


## Accuracy: 0.95241
After submitting the result I managed to score *0.95241* accuracy which is satisfying for a newcomer.There are plenty of modifications you can apply to increase the accuracy of the solution. 
*The primary aim of the solutions is to get familiar with data and to capture the idea, to begin with, for further improvements.*
 

### Useful Links and References
[Ensemble-methods-machine-learning](https://www.toptal.com/machine-learning/ensemble-methods-machine-learning)

[What is Bagging, Boosting and stacking](https://stats.stackexchange.com/questions/18891/bagging-boosting-and-stacking-in-machine-learning)


### Collections of such solutions that will prove useful to you

http://ndres.me/kaggle-past-solutions/

https://www.kaggle.com/wiki/PastSolutions
 
https://github.com/ShuaiW/kaggle-classification/
