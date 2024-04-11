### Researching the relationship between stock market performance and involuntary CEO dismissal. 
1. This repository
2. Objectives
3. Predictive Question
4. Variables

## 1. This repository

This repository will explore the relationship between a company's financial performance and Involuntary CEO Dismissal. The first stage of the project is to build a custom dataset that will track the financial performance of the S&P 500 companies including adjusted close and trading volume this information will be acquired from finance -- Python library for accessing and downloading financial data from Yahoo Finance. After downloading the financial data for all 500 companies in the S&P 500 index we will create a longitudinal panel dataset that will track each company's financial performance, its industry, sub-industry, and the CEO dismissal. The last stage of the project will focus on predicting the CEO's dismissal based on available financial information. 
Navigating this repository is quite easy since it is divided into 2 main folders. Folder 1 contains Jupyter Notebooks with all the codes. The second folder contains relevant datasets. 
#### 2. Objectives: 
The primary goal of this project is to predict CEO dismissal in S&P 500 companies using Python's PyMC library and available financial data. After achieving these objectives I aim to publish findings on my dev blog through Medium/Substack. 
#### 3. Predictive question: 
1. How can we use historical financial data and CEO turnover events at Apple Inc. to predict the likelihood of involuntary CEO dismissals in the future?"

### 4. Variables

|  | Variables |
| ------------- | ------------- |
|  1. | CEO Dismissal  |
|  2. | Adjusted Close Price |

1. CEO Dismissal: Outcome variable. Binary, 1/0 = Yes/No. Tracks whether or not the CEO was dismissed involuntarily.
2. Adjusted Close Price: Predictor variable. discrete variable factoring in anything affecting the stock price after the market closes. The adjusted close price is the moving average of the daily adjusted close price. Although the price is a continuous variable, the variable is discrete in the sense of a data point (price has a decimal point. See Nasdaq reference). 


