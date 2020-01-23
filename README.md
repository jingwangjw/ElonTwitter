Analyze Market Moving Twitter Personalities. Predict how the influential user (Elon Musk) effects the stock price.

## Introduction
In August 2018, Elon Musk tweeted that he “[is] considering taking Tesla private at $420” and that “funding is secured” [1]. Within the next four hours, TSLA’ s market cap increased by $12 billion. As a matter of fact, some of Elon’s controversial tweets have had a history of moving Tesla’s share prices significantly. Recent similar events include how Snapchat stock price plummeted after Kylie Jenner’s tweet and how Trump’s tweets have affected the US stock market. 

We are interested in examining whether the tweets of other celebrities or influencers on Twitter also possess the power to sway share prices of well-known companies or the market in general. Our project aims to discover characteristics from tweets that contribute to the prediction of trading volume changes and discover market-moving twitter personalities.

## Data
- Twitter: 6,286 tweets 3,199,477 comments (Since 2012)
- Google Trends: 151 data points (Since 2016)
- Yahoo Finance: 5,089 data points (Since 2016)

## Model
21 features were generated including sentiment scores, search popularity and time variables from three data sources above. Trading volume precentage with customized window size was used as the label for the supervised learning task. Mutiple models were trained including Auto Regressive, Random Foreast, Xtreme Gradiant Boosting and Stacked model, with cross validation and bootstrapped metrics. 
