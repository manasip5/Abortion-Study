# Predicting Sentiment from Tweets on Abortion

**Team Members**  
* Manasi Phadnis
* Mayarak Quintero

## Set Up
The following modules were used for this analysis:
```
gender_guesser
pandas
tweepy 
webbrowser
time 
re 
seaborn 
string
nltk
wordcloud
snscrape
numpy
sklearn
torch
random
```
#### `GenderDetection.ipynb`  
*lines of code: 2543*

Uses gender_guesser to detect the user's gender. Use to generate gender plots and analyze differences in trends between male and female opinions towards abortion on social media. 

#### `GettingTwitterData_Cleaning_Preprocessing.ipynb`
*lines of code: 2543*

Scrape the data with snscrape and store it into nine different dataframes, one for each combination between hashtag and year. 
Also collects location and user name information from Twitter API. 
Appends the data, clean it and preprocess it. 

This file takes several days to run because of the twitter API. 

This notebook uses [**VADER**](https://github.com/cjhutto/vaderSentiment#installation) to determine and score positive, negative and neutral tweet sentiment.

#### `TwitterDataModeling.ipynb`
*lines of code: 765*  

Builds the CNNs, train it and test it. 

#### `clean_pp.ipynb`  
*lines of code: 1048*
Cleans it and preprocess the data. 

#### `lda_gender.ipynb`
*lines of code: 1572*
