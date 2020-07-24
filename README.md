


# Jacinda COVID-19 Tweet sentiment analysis 


#### -- Project Status: [Active]

## Objective
The New Zealand primeminister,Jacinda Adern has received a large amount of praise for the way she has handled COVID-19. After reading countless articles about her success and being a proud kiwi myself I wanted to see whether this sentiment was mirrored by the rest of the world. With data being the new oil and twitter being the voice of people I decided to use Twitter as a way to gauge the sentiment. The final objective is to see whether the press is mirroring the peoples real opinions. 


### Methods Used
* NLTK sentiment Analysis
* Machine Learning
* Data Visualization
* Predictive Modeling

### Technologies
* Python
* GetOldTweets.py
* Pandas, jupyter


## Project Description
Although twitter has a RESTful API unfortunately it's only possible to crawl tweets for the week previous. So I decided to use GetoldTweets3, I found this great github with a py.file attached where you can request tweets by various different parameters. Click [here](https://medium.com/analytics-vidhya/twitter-data-mining-mining-twitter-data-without-api-keys-a2a2bd3f11c) for a great article about using GetoldTweets3.

#### data sources
GetoldTweets3.py Parameters searchquery "jacinda covid-19" "jacinda corona" 01-02-2020 - 18-05-2020 

#### questions / hypothesis 

- Does the sentiment of tweets containing the words jacinda and covid-19 mirror the positive press and praise jacinda has received ? 

H0 : Overall people have a positive view of Jacindas response of COVID-19

h1 : Overall people do not have a positive view of Jacindas response of COVID-19

### challenges/ blockers

- Twitter RESTFUl API doesn't have tweets older then a week
- Twitter has a maximum amount of 1500 tweets per request/time
- First sentiment analysis didn't correctly identify polarity figures




## Getting Started

1. Clone this repo (for help see this [tutorial](https://help.github.com/articles/cloning-a-repository/)).
2. Raw Data is being kept [here](https://github.com/livvyton/jacinda-sentiment-analysis/tree/master/data) within this repo.
3. Data processing/transformation scripts are being kept [here](https://github.com/livvyton/jacinda-sentiment-analysis/blob/master/data-cleaning.ipynb)
4. Initial Analysis is [here](https://github.com/livvyton/jacinda-sentiment-analysis/blob/master/initial-sentiment-analysis.ipynb)
