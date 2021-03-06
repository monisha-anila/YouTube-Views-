# YouTube-Views

## Problem Statement
- ABC company want to target geographical ads based on YouTube information to decrease their Cost-to-Acquire New customer up to 10% monthly for the coming month. 

 - *Please click the highlighted blue words to check*
 - *Please use full screen mode in Tableau*
 - *GR - Growth Rate, MAVG - Moving Average , RT - Running Total(Tableau abbreviations)*
 
## Dataset
- [CSV file](https://drive.google.com/file/d/1J3s9RBfzwPlIUHfNLAkwo3omPYC-bv6G/view?usp=sharing) 

## EDA
- [Tableau](https://public.tableau.com/profile/monisha.anila#!/vizhome/YouTubeLikes/Story1) 
- [Python Notebook](https://colab.research.google.com/drive/1uQ88sNvEm-oBryeRLtU_2ALrTKGUdPLu?usp=sharing)

## Ideation
- Understand the YouTube content creators’ channels target audience behaviour to team up with them for Ads advertising.
- Define the metrics for performance (DAU,MAU,Cost-To-Acquire New customer, Satisfaction score, Net promoter score) etc.
- Do your own homework (Understand the domain keywords like performance metrics)
- Start doing Exploratory Data Analysis (EDA) using the below types (Best build dashboard to achieve best visibility)
  - Deviation
  - Correlation
  - Ranking 
  - Distribution
  - Change Over Time
  - Waterfall
  - Spatial 
- Build and train base line model Linear Regression
- To improve ML model performance train the data with Random Forest Regressor. 
- RMSE error is the ML model performance indicator.

## After Ideation
- Check with domain expertise person to further train the ML model using location to separate the main model.
- After getting reasonable ML metric value we need to start testing using Statistics (A/B).
- Before A/B testing select random samples from location based data and conduct z-test to avoid selection bias.
- Define Null and Alternative hypothesis framing with default action.
- P value = 0.05 
- If P value > 0.05 then accept null hypothesis. Else accept Alternative hypothesis.
