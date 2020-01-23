Market-Moving Twitter Personalities

## Contributors
Yishuang Chen, Jeff Peng, Edward Tiong, Jidapa Thanabhusest, Jing Wang

## Introduction

In August 2018, Elon Musk tweeted that he “[is] considering taking Tesla private at $420” and that “funding is secured”. Within the next four hours, TSLA’ s market cap increased by $12 billion. As a matter of fact, some of Elon’s controversial tweets have had a history of moving Tesla’s share prices significantly. Recent similar events include how Snapchat stock price plummeted after Kylie Jenner’s tweet and how Trump’s tweets have affected the US stock market. 

We aim to discover characteristics from tweets that contribute to the prediction of trading volume changes and discover market-moving twitter personalities. Specifically, this project focuses on answering the question by predicting how the tweets of influential user (Elon Musk) affect the stock market (Tesla).

## Data
- Twitter: 6,286 tweets 3,199,477 comments (Since 2012)
- Google Trends: 151 data points (Since 2016)
- Yahoo Finance: 5,089 data points (Since 2016)

## Model
* 21 features were generated including sentiment scores, search popularity and time variables  
* Trading volume precentage with customized window size was used as the label for the supervised learning task 
* Auto Regressive, Random Foreast, Xtreme Gradiant Boosting and Stacked model were trained with random search
* Cross validation and bootstrapping confidence intervals for performance metrics were applied 

## Reference
1. Musk, Elon. “Am Considering Taking Tesla Private at $420. Funding Secured.” Twitter, Twitter, 7 Aug. 2018, twitter.com/elonmusk/status/1026872652290379776.
2. Dugan, Kevin, et al. “Tesla Shares Rise 11 Percent after Musk's Shocking Tweet.” New York Post, New York Post, 7 Aug. 2018, nypost.com/2018/08/07/tesla-shares-rise-11-percent-after-musks-shocking-tweet/.
3. Yurieff, Kaya. “Snapchat Stock Loses $1.3 Billion after Kylie Jenner Tweet.” CNNMoney, Cable News Network, 23 Feb. 2018, money.cnn.com/2018/02/22/technology/snapchat-update-kylie-jenner/index.html.
4. Popina, Elena, and Sarah Ponczek. “Trump Rattles Stocks With His Tweets.” Bloomberg.com, Bloomberg, 6 Apr. 2018, www.bloomberg.com/news/articles/2018-04-06/trump-tweets-toy-with-stocks-as-trade-bluster-shakes-wa ll-street.
