# Credit-Card-Fraud-Detection

This is a simple **Credit Card Fraud Detection Program** in Python using Machine Learning by implementing:

**Logistic Regression**

**Random Forest Classifier**

**Decision Tree Classifier**

## Introduction
In terms of card payments, unauthorized card payment is considered fraudulent. These are transactions in which cardholders are not direct or indirectly involved in the transactions. Fraudulent transactions can happen in different ways; for example Account -Take-Over where the fraudster takes ownership of the cardholder's account, cone of the cardholder's card, and more.

There's a need for the **card issuers** to have measures to prevent unauthorized payments/activities. We know that some **card issuers** use chargebacks to retrieve money back for some unauthorized payments; however, it is not 100% guaranteed the recovery of funds, and in some cases becomes an inconvenient for the cardholders to have unauthorized payments.

## Objective
The object of this project is to analyze the dataset to grasp the content and have a better insight into legit and fraudulent transactions in order to create fraud prevention models using machine learning algorithms with Python.

## Preparing dataset

### 1. Dataset Introduction
The dataset contains transactions activities of credit card made in Setpember 2013 by Europen cardholders. The sensitive informations are named V1 to v28

dataset structure:
Dataset Size: 284807 x 31

Contains data of 284,807 transactions

Out of 31 columns, 28 columns are named V1, V2, … , V28.

The other three columns are named Time, Amount and Class.

legit= df[df.Class==0] --> Represent legit transactions

fraud= df[df.Class==1] --> Represent fraudelent transactions

Source: (Kaggle, https://www.kaggle.com/mlg-ulb/creditcardfraud)

### 2. Dataset Analysis and Pre-process
I have analyzed the dataset to find any unnecessary information to be removed and standardized dataset, and I opted to use 429 samples for both legit and fraudulent for the machine learning algorithms implementation.

### 3. Modelling
Train-Test Split: Selected dataset 0.9 is used for training the models and 0.1 for testing the model accuracy.

Modelling: I have used 3 different ML modelling algorithms to train the dataset:

 1. Logistic Regression

 2. Random Forest Classifier

 3. Decision Tree Classifier
 
**Getting started**
get the code from the repository

git clone: https://github.com/Calivala-86/Credit-Card-Fraud-Detection

download the dataset that will be used to train a transaction classifier. Unzip it and put the content (creditcard.csv) under main folder (Credit-Card-Fraud-Detection)

install required python packages if previously not installed:

download link: https://www.python.org/downloads/ Instructions: https://www.tutorialspoint.com/how-to-install-python-in-windows

Install Jupyter notebook and necessary dependencies:

link: https://jakevdp.github.io/blog/2017/12/05/installing-python-packages-from-jupyter/

References
https://www.kaggle.com/datasets

Hands-On Machine Learning with Scikit-Learn and TensorFlow Concepts, Tools, and Techniques to Build Intelligent Systemsby Aurélien Géron

Python for Data Analysis_ Data Wrangling with Pandas, NumPy, and IPython by Wes McKinney

https://www.youtube.com/watch?v=EqRsD3gqeCo&list=PLZoTAELRMXVOnN_g96ayzXX5i7RRO0QhL

https://github.com/anujdutt9/Feature-Selection-for-Machine-Learning
