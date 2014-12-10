Twitter Sentiment Analysis for Amazon
========================================================

<h4>Author: Anand Kalukuri </h4>




<h2>Number of tweets</h2>

Total number of tweets recorded per day is 200.

<h2>Sentiment Histograph for each day</h2>

<b>Day1</b> 

Below is the sentiment histograoh for the day 1: 12-01-2014

![day1_1_12_2014](http://138.87.44.2:8787/files/amazonday1.png)

<b>Day2</b> 

Below is the sentiment histograoh for the day 2: 12-02-2014

![day1_1_12_2014](http://138.87.44.2:8787/files/amazonday2.png)

<b>Day3</b> 

Below is the sentiment histograoh for the day 3: 12-03-2014

![day1_1_12_2014](http://138.87.44.2:8787/files/amazonday3.png)

<b>Day4</b> 

Below is the sentiment histograoh for the day 4: 12-04-2014

![day1_1_12_2014](http://138.87.44.2:8787/files/amazonday4.png)

<b>Day5</b> 

Below is the sentiment histograoh for the day 5: 12-05-2014

![day1_1_12_2014](http://138.87.44.2:8787/files/amazonday5.png)

<h2> Comparison Graph </h2>

![plot of chunk unnamed-chunk-3](figure/unnamed-chunk-3.png) 

```
##   Dates Sentiments Stockprice_change
## 1  Day1         45              -373
## 2  Day2         49                10
## 3  Day3         45              -301
## 4  Day4        122                14
## 5  Day5         56              -136
```

     In this file, first we are extracting the data from twitter and calculating the sentiment analysis with the actual stock behavior to verify if sentiment analysis predicts the stock change accordingly. We totally have 7 attributes created for calculating the sentiment analysis in order to predict the stock fluctuations, each of them are explained in detail below.
  
     5 of them are histographs containing sentiment analysis data for each day starting from December 1st 2014 to December 5th 2014, 1 table which explains the sum of sentiments for each day and the Stock price change for that respective day(The stock price change values have been calculated as the daily stock price change * 100). 
     
     The bar graph plotted against the sentiment analysis collected and actual stock price change in the market. The graph has plotted all five days stock ups and downs against all 5 days sentiment analysis results side by side helping us judge the sentiment analysis prediction. From the graph we can see that the predictions were wrong for the first day as the sentiment results were positive indicating a rise in the stock price, whereas the stock has dropped originally which indicates the predictions are wrong but sentiment analysis predictions for the second day were right where the results showed that there will be a rise in the stock price and there was actually rise in the market for amazon. And for similarly for day 3 , day 4 , day 5 , predictions were negative, positive, negative, respectively. 
     
     Thus we can conclude that we cannot counting on the predictions of sentiment analysis doesn’t work all the time as the results are inconsistent.

     
  
