---
layout: post
title: "🏆 Ballon d'Or Winner and Nominees Prediction 2025 (Men's soccer) ⚽ "
date: 2025-04-29
category: Data Science
excerpt: "Leveraging AI and Machine Learning with Football Expertise for Real-World Sports Analytics: <b> Feature Engineering, Machine Learning, Classificaiton (XGBoost + LightGBM), Regression and Ranking (PCA Regression),Python, FBref, SoccerData</b>"
feature: https://e0.365dm.com/22/10/768x432/skysports-lionel-messi-cristiano-ronaldo_5934657.jpg?20221018103356
comments: true
---
<center>
    <div class="btn-group">
        <a href="https://drive.google.com/file/d/1igaEFs5nHkyyLjSEiyOA6QbjsFDWskEw/view?usp=sharing" class="btn btn-success">Report</a>
    </div>

</center>
<hr>

# Introduction & Problem Definition

The Ballon d’Or is the most prestigious award in football (soccer), presented annually by Groupe Amaury (French magazine
France Football) and UEFA to the world’s best performing player (for both men and women) since 1956. The award is
determined by an international jury of specialized journalists with one representative per country from the top 100 in the
latest FIFA rankings. Each juror ranks their top ten players out of 30 nominees, assigning them points as follows: 15, 12,
10, 8, 7, 5, 4, 3, 2, and 1. The player with the highest total points wins the Ballon d’Or. The award is based on three main
criteria:

1. Individual performance, decisive and impressive character
2. Team performance and achievements
3. Class and fair play
   However, predicting the winner remains a challenge due to the subjective nature of voting and the variety of factors
   influencing the decision. This project aims to develop data-driven models to identify the key predictors of Ballon d’Or top
   30 nominations and the winner using historical data from 2020 to 2024 and current-season performance metric
   
However, predicting the winner remains a challenge due to the subjective nature of voting and the variety of factors
influencing the decision. This project aims to develop data-driven models to identify the key predictors of Ballon d’Or top
30 nominations and the winner using historical data from 2020 to 2024 and current-season performance metrics. The goal
is to classify the 2025 Ballon d’Or top 30 nominees and predict the winner with a ranking-based methodology.

### We have achieved the following in our project:

- Project Goal: Predict the 2025 Ballon d'Or winner and top 30 nominees.
- Data Acquisition: Gathered player statistics and historical records from multiple football data platforms, including FBref.com, FIFA, UEFA, and France Football.(Our raw data has 11,360 players with 117 features. )
- Data Scope: Analyzed player statistics from Europe’s top 5 leagues, World Cup, UEFA Champions League, Euro Cup and Copa America (2020-2024).
- Data Preprocessing: Cleaned and preprocessed the data by handling missing values, removing duplicates, and filtering out goalkeepers.
- Feature Engineering: Developed and normalize 117 player features, including passing, defensive, possession, and standard statistics, individual awards, team achievements, and social media reach; normalized key performance metrics per 90 minutes played and average seasonal playing time; combined statistics across tournaments using weighted strategies based on tournament prestige; and created percentage features, such as percentage of short pass completion and successful take-ons.
  - For example, if Lionel Messi played for PSG in tournaments such as Ligue1, Champions League, and World Cup during 2021-2022 season then we multipled the three rows with weights and summed them to form one row for 2021-2022 season. 'Playing Time_Min' and 'Playing Time_90s' were aggregated using sum across the tournaments rather than weighted sum because it preserves the actual playing time as the denominator for the rate statistics like ‘goals_per90min’, while weighted sums of other statistics capture the impact of tournament prestige on their overall output.
  - To avoid inflation by low-minute players for per_90min_played stats, we multiplied a player’s stats with the ratio of playing time and mean season playing time if they player played less minutes than season average playing time.
- Nominees Classification Model Development: Built a classification model (using stacked ensembles of Gradient Boosting, XGBoost, and LGBM) to predict Ballon d'Or top 30 nominees.
    - Address Class Imbalance: Implemented SMOTE and class weighting techniques to handle the imbalance between nominees and non-nominees.
- Feature Selection: Identifed the most influential features for nominee prediction, including availability, offensive productivity, tactical involvement, and team success.
- Winner Ranking Model: Trained a regression model (PCA Regression) to rank the predicted nominees, focusing on the top 3.
- Model Evaluation: Evaluated model performance using metrics like F1 score, ROC AUC, precision, recall, RMSE, and average precision at K=3.
- 2025 Prediction: Applied the trained models to the 2024-2025 season data to predict the 2025 Ballon d'Or winner and nominees.
- Result Analysis: Analyzed the model's predictions, compare them with expert opinions, and discuss the key factors influencing the 2025 Ballon d'Or outcome.
- Address Limitations: Acknowledged and discussed limitations of the model, such as bias towards attacking players and the exclusion of the 2010-2020 period.

### How to get started with the project?

- [Coming Soon](https://github.com/gurungkshitij/Ballon_dor_award) for all the Nuts and Bolts 🛠️⚙️ 

<center>
    <div class="btn-group">
        <a href="https://drive.google.com/file/d/1igaEFs5nHkyyLjSEiyOA6QbjsFDWskEw/view?usp=sharing" class="btn btn-success">Report</a>
        <a href="https://github.com/gurungkshitij/Ballon_dor_award" class="btn btn-info">Source Code Coming Soon</a>

    </div>

</center>
<hr>

<iframe src="https://www.linkedin.com/embed/feed/update/urn:li:ugcPost:7324982715483590656?collapsed=1" height="850" width="720" frameborder="0" allowfullscreen="" title="Embedded post"></iframe>

### 2025 Top 30 Nominees classification and Model Evaluation

<figure class="half">
    <a href='/assets/img/ballondor/2025top30.png'><img src='/assets/img/ballondor/2025top30.png'></a>
    <a href='/assets/img/ballondor/top30modelcomp.png'><img src='/assets/img/ballondor/top30modelcomp.png'></a>
</figure>

### 2025 Top 10 Nominees Ranking and Feature Importance

<figure class="half">
    <a href='/assets/img/ballondor/2025top10.png'><img src='/assets/img/ballondor/2025top10.png'></a>
    <a href='/assets/img/ballondor/Ballondfeatureimp.png'><img src='/assets/img/ballondor/Ballondfeatureimp.png'></a>

</figure>

### EDA and Appendix

<figure class="half">
    <a href='/assets/img//ballondor/EDA.png'><img src='/assets/img//ballondor/EDA.png'></a>
    <a href='/assets/img//ballondor/Appendixballon.png'><img src='/assets/img//ballondor/Appendixballon.png'></a>
</figure>
