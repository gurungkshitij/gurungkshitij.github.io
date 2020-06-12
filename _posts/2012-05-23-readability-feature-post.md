---
layout: post
title: "Salary, Market Value, and Overall Rating Prediction (Football: Soccer)"
date: 2020-06-12
excerpt: "An exciting project for Football (soccer) fans."
project: true
tags: [sample post, readability, test, image, feature]
feature: https://library.kissclipart.com/20180919/syq/kissclipart-pes-18-icon-clipart-cristiano-ronaldo-fifa-18-pro-f5da5d3ace6914be.png
comments: true
---

## Introduction
Have you ever wondered what sets apart high earning soccer players from other players? What attributes might significantly contribute in achieving such a high salary and market value?

In this exciting project, we implemented different machine learning algorithms on Fifa 18 data sets in an attempt to analyze various attributes of players (age, speed, finishing, passing, etc), and aimed to achieve accurate predictions for salary, market value, and overall rating prediction. We also tried to investigate how well the performances of a player in real-life predict their “Overall” Fifa rating. Naturally, if a player is considered good, their overall might be high, but the public’s conceptions of what makes a “good” player are very subjective, and Fifa is forced to meet the challenge of quantifying it. We wanted to see how well we could predict a future FIFA overall rating based on a set of real-life performance statistics.

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




