# ECON-323-Final-Project
Machine learning applied to the determinants of heart failure. The idea that social awareness leads to reduced risk of death due to heart failure using web-scraped Twitter data.

### ECON323 Final Project

This project will be in two parts:

#### 1) Data Cleaning and LASSO Regression
First, I will clean heart failure clinical records data provided by Davide Chicco and Giuseppe Jurman.

I will then run a group LASSO regression on the data to assess the effect of anaemia, creatinine phosphokinase, diabetes, ejection fractions, high blood pressure, platelet count, serum creatinine, serum sodium, gender, smoking status, and whether death occurred following heart failure.

#### 2) Data Scraping and Data Visualization

Then, I will scrape Twitter data to examine the social awareness of heart disease and heart failure in the media. I will compare the awareness of heart disease and heart failure to the number of heart disease-related deaths that occur by month, in the year 2018, in Canada.

The purpose of this project was to focus on heart and stroke data in Canada.

### Section 1: Datasets

There are multiple datasets used in this project: (1) heart failure clinical records provided by Davide Chicco; (2) heart and stroke data scraped from Twitter; and (3) monthly fatalities data provided by Stats Canada.

1. I limit my data set to heart failure events that resulted in death. The heart failure records specifically focus on the effect of anaemia, creatinine phosphokinase (ATP in the heart), diabetes, ejection fractions (how well your heart pumps blood), high blood pressure, platelet count, sodium levels, gender, and smoking on the age of a heart attack.
2. I used the key word 'heart attack' to gather data from Twitter.

### Section 2: LASSO Regression

I first fit my data to a LASSO Regression.

### Section 3: Neural Network

Next, I fit my data to a neural network.

### Section 4: Scraping Twitter Data

Data from Twitter was scraped using snscrape

### Section 5: Plotting Twitter Data

February is considered 'Heart Health' month. As can be seen, there is an increase in relevance of tweets that contain reference to 'heart attacks' in that time period. What is potentially interesting is that we can see a small decrease in the number of deaths due to heart failure in the months that followed February/March, which suggests social awareness of heart failure may lead to decreased deaths due to heart failure.

