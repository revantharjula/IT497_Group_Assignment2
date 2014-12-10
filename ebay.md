Twitter Sentiment Analysis for Ebay
========================================================

<h4>Author: Revanth Reddy Arjula </h4>





<h2>Number of tweets</h2>

Total number of tweets recorded per day is 200.

<h2>Sentiment Histograph for each day</h2>

<b>Day1</b> 

Below is the sentiment histograoh for the day 1: 12-01-2014

![day1_1_12_2014](http://138.87.44.2:8787/files/ebayday1.png)

<b>Day2</b> 

Below is the sentiment histograoh for the day 2: 12-02-2014

![day1_1_12_2014](http://138.87.44.2:8787/files/ebayday2.png)

<b>Day3</b> 

Below is the sentiment histograoh for the day 3: 12-03-2014

![day1_1_12_2014](http://138.87.44.2:8787/files/ebayday3.png)

<b>Day4</b> 

Below is the sentiment histograoh for the day 4: 12-04-2014

![day1_1_12_2014](http://138.87.44.2:8787/files/ebayday4.png)

<b>Day5</b> 

Below is the sentiment histograoh for the day 5: 12-05-2014

![day1_1_12_2014](http://138.87.44.2:8787/files/ebayday5.png)

<h2> Comparison Graph </h2>

![plot of chunk unnamed-chunk-3](figure/unnamed-chunk-3.png) 

```
##   Dates Sentiments Stockprice_change
## 1  Day1         51                -2
## 2  Day2         73                27
## 3  Day3         51               -42
## 4  Day4         91               -22
## 5  Day5         54                26
```

In this assignment we are extracting the data from twitter to calculate sentiment analysis to compare the stock with sentiment analysis results. The resultant graph is plotted against the current day stock and the sentiment we have calculated for that particular day.

First, we have displayed the histographs containing the sentiment values for the tweets for all the five days. Next we try to compare the final sum sentiment value for each day with the stock price change for that particular day to see if the twitter has predicted correctly.

The above table shows the data for the sum of sentiments for each day and the Stock price change for that respective day. The stock price change values have been calculated as the daily stock price change * 100.

With sentiment analysis we are unable to predict the stock change properly, The graph shows that the sentiment is negative on the first day which means it predicted that the stock price will change decrease , which is a failure, as the stock price for dec 1st was positive for ebay. But for day 2 of our sentiment analysis i.e on dec 2nd the sentiment analysis prediction was right, the sentiment analysis predicted that there will be a rise in the stock price of ebay and there was a rise in the stock price of ebay on that day. Again for day 3 that is, on dec 3rd the prediction was right , so there is an inconsistency in prediting the stock using sentiment analysis for ebay. thus we cannot blindly trust sentiment analysis and predict the stock.     
