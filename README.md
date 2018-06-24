# Quora-Identifying-Questions-with-same-intent

## Project Overview

### Domain Background:

Quora is a place to gain and share knowledge—about anything. It’s a platform to ask questions and connect with people who contribute unique insights and quality answers. This empowers people to learn from each other and to better understand the world.
Over 100 million people visit Quora every month, so it's no surprise that many people ask similarly worded questions. Multiple questions with the same intent can cause seekers to spend more time finding the best answer to their question, and make writers feel they need to answer multiple versions of the same question. Quora values canonical questions because they provide a better experience to active seekers and writers, and offer more value to both of these groups in the long term.
 
### Problem Statement

The goal of the project is to build a binary classification model using a simulated dataset containing a pair of questions and a binary class label stating whether a pair is duplicate or not. In this project, I will be handling this problem by applying advanced techniques (Random Forest, K-Means, SVM, XGBoost etc.) to classify whether question pairs are duplicates or not. After applying several models, I’ll be comparing the accuracy obtained with each model.

Doing so will make it easier to find high quality answers to questions resulting in an improved experience for Quora writers, seekers, and readers.

## Datasets and Inputs:

I’ll be using the Quora dataset provided on the Kaggle Competition ( 4,04,351 records) :
https://www.kaggle.com/quora/question-pairs-dataset

• id - the id of a training set question pair – (Numeric)
• qid1, qid2 - unique ids of each question (only available in train.csv) – (Numeric)
• question1, question2 - the full text of each question – (String)
Target Variable:
• is_duplicate - the target variable, set to 1 if question1 and question2 have essentially the same meaning, and 0 otherwise. – (Numeric)

## Environment Used:
The project will be written in Python 3.5 and the following libraries will be used:
• Pandas
• Numpy
• Scikit-Learn
• MatplotLib
• XGBoost
• Seaborn

