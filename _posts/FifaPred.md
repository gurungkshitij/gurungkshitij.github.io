---
layout: post
title: "Salary, Market Value, and Overall Rating Prediction (Soccer)"
date: 2020-06-12
excerpt: "A ton of text to test readability with image feature."
tags: [sample post, readability, test, image, feature]
comments: true
---

# Salary, Value, and Overall Rating prediction: Football (Soccer)

### Introduction
This is a very intersting project specially for the football fans who always wonder about impact of various attirbutes of players (age, speed, finishing, passing) on determining their salary, market value, and overall fifa rating. In this project, we tried to implememted various machine learning algorithms on fifa 18 data set and aimed to achieve accurate predictions for salary, market value, and overall rating prediction. We also attemped to investigate how well the performances of a player in real-life predicts their “Overall” fifa rating. Naturally, if a player is considered good, their overall might be high, butthe public’s conceptions of what makes a “good” player is very subjective, and FIFA is forced to meet the challenge of quantifying it. We wanted to see how well we could predict a future FIFA overall rating based on a set of real life performance statistics.

The project is broken into two main sections. 

1) **Salary, Market Value Prediction** ( Numerical and catagorical). We also catagorized the *salary* and *value* to high, medium, and low and performed classification predictions. We implemeted following algorithms and compared the results. 

- Penalized Lasso regression
- Penalized Ridge regression
- Forward selection
- Backward selection
- KNN regression
- Decision Trees
- Bagging
- RandomForest
- Boosting

2) **Overall Rating prediction.** We wanted to see how well we could predict a future FIFA overall rating based on a set of real life performance statistics.

- PCA
- Cluestering
- Penalized Ridge regression
- RandomForest
- Boosting

### How users can get started with the project?

- [FiFaPred.Rmd](https://github.com/gurungkshitij/fifaPrediction/blob/master/FiFaPred.Rmd) is the main file 
- After you download all the files, change the directories of the datasets as you read in the csv files in FifaPred.Rmd 
- Everythign should run smoothly. Knit the file if you want the pdf/html report version
- The final report is [FinalReport-Fifa.pdf](https://github.com/gurungkshitij/fifaPrediction/blob/master/FinalReport-Fifa.pdf)
