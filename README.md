# Model Prediction for 2025 Canadian Federal Election Liberal Party Vote Share

**Authors:** Yutong Lu, Zichen Gong 

**Date:** November 5, 2021  

## Introduction

- Utilizes data from the Canadian Election Study (2019) and General Social Survey (2017).
- Aims to predict the Liberal Party vote share in the 2025 Canadian federal election.
- Factors considered: age, gender, province, education, and total household income.
- Significance: Understanding voter perceptions and political behaviors.

## Data

### Data Sources

- Survey conducted by Canadian Election Study in 2019.
- General Social Survey on families from 2017.

### Data Cleaning Process

- Variables selected: citizenship status, age, sex, province, education, and family income.
- Adjustments made for compatibility between census and survey data.

## Important Variables

- Liberal votes, age status, gender, province, education, and family income.

## Methods

- Multilevel Regression (MR) and Multilevel Regression Post-stratification (MRP) used for model construction.
- Akaike’s Information Criterion (AIC) and Bayesian Information Criterion (BIC) for model selection.

## Results

- The model predicts a 33.36% vote share for the Liberal Party in the 2025 election.
- Age groups showed different political attitudes.
- Education and province were significant predictors of Liberal Party vote share.

## Conclusions

- The study predicts over one-third of the popular vote for the Liberal Party in 2025.
- Highlights the impact of demographic factors on political attitudes.
- Acknowledges limitations due to data time difference and the exclusion of young voters not eligible during the data collection period.
- Future research could explore different level 2 variables and incorporate candidate features.

## Discussion

- The popular vote does not directly translate to election victory due to the nature of the electoral system.
- The study provides insights for strategic planning in electoral districts.

_All analysis for this report was programmed using R version 4.1.1._
