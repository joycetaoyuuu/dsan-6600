# DSAN-6600 Project: Student Essay Score Predicting with Neural Networks

## Introduction

Essay writing is a method to evaluate student academic outcomes, but essay grading is time-consuming for educators to grade manually. Developing a reliable automated essay scoring (AES) system can not only help educators to save time, but also provide in-time feed back for the students, making it highly worthy of research.

The goal of this project is to build a neural network model to predict student essay scores that assists essay grading system.

## Methods

This project utilized student essays (text data) to predict their corresponding essay scores (numerical targets). The dataset can be retrieved from [Kaggle](https://www.kaggle.com/competitions/learning-agency-lab-automated-essay-scoring-2/overview). 

Basic exploratory data analysis (EDA) techniques are applied to check some features inside the essay, including the distribution of scores, word count, and vocabulary size and possible topics. 

Deep learning models, like LSTM (RNN-based), DistilBERT, and DeBERTa (transformer-based) models, are used for modeling.

## Results

The outcomes indicated that deep learning models are able to identify patterns that influence essay scores, making this project possible. Furthermore, the training and validating result showed that transformer-based models overperform RNN models.



