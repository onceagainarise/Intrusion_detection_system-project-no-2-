
# Intrusion Detection System using Machine Learning

This Intrusion Detection System (IDS) is implemented using machine learning models, including Decision Tree Classifier, Random Forest Classifier, and Gaussian Naive Bayes. The system aims to identify and classify network traffic as either normal or potentially malicious.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Data](#data)
- [Preprocessing](#preprocessing)
- [Model Training](#model-training)
- [Model Evaluation](#model-evaluation)
- [Results](#results)
- [Acknowledgements](#acknowledgements)

## Introduction

Intrusion Detection Systems play a crucial role in securing computer networks by identifying and responding to malicious activities. This project utilizes machine learning algorithms to build an IDS capable of distinguishing between normal and malicious network traffic.
It includes implementation of decidion tree classifier ,RFC and Naive Bayes model and based on the accuracy uses the best one.

## Features

- Implementation of Decision Tree Classifier, Random Forest Classifier, and Gaussian Naive Bayes models.
- Feature engineering, data preprocessing, and scaling for effective model training.
- Model comparison and evaluation using metrics such as accuracy, precision, recall, and ROC curves.
- Visualization of results through confusion matrices and precision-recall curves.

The dataset used in this project is the UNSW_NB15 dataset, which is available here. The training and testing sets were reversed, and the data was preprocessed for model training.

## Preprocessing
Removal of unnecessary features such as 'id' and 'attack_cat'.
Encoding categorical features using LabelEncoder.
Data correlation analysis and removal of highly correlated features.
Splitting the dataset into training and testing sets.
Scaling features using StandardScaler.
Model Training
The implemented models include Decision Tree Classifier, Random Forest Classifier, and Gaussian Naive Bayes. Additionally, a Random Forest Classifier with Recursive Feature Elimination (RFE) is employed for feature selection.

## Model Evaluation
Models are evaluated based on training score, accuracy, precision, recall, and training time.
Visualizations include ROC curves, precision-recall curves, and confusion matrices.

## Results
The Random Forest Classifier is identified as the best-performing model, showcasing superior accuracy and performance.

## Acknowledgements
This code was learned and adapted from a GitHub repository. Special thanks to that  GitHub Id(its been too long and sorry😓 I forgot their id) for their valuable contribution and insights.





