Twitter Sentiment Analysis for Microsoft
========================================================

<h4>Author: Shreekar Gonuguntla Reddy </h4>




<h2>Number of tweets</h2>

Total number of tweets recorded per day is 200.

<h2>Sentiment Histograph for each day</h2>

<b>Day1</b> 

Below is the sentiment histograoh for the day 1: 12-01-2014

![day1_1_12_2014](http://138.87.44.2:8787/files/microsoftday1.png)

<b>Day2</b> 

Below is the sentiment histograoh for the day 2: 12-02-2014

![day1_1_12_2014](http://138.87.44.2:8787/files/microsoftday2.png)

<b>Day3</b> 

Below is the sentiment histograoh for the day 3: 12-03-2014

![day1_1_12_2014](http://138.87.44.2:8787/files/microsoftday3.png)

<b>Day4</b> 

Below is the sentiment histograoh for the day 4: 12-04-2014

![day1_1_12_2014](http://138.87.44.2:8787/files/microsoftday4.png)

<b>Day5</b> 

Below is the sentiment histograoh for the day 5: 12-05-2014

![day1_1_12_2014](http://138.87.44.2:8787/files/microsoftday5.png)

<h2> Comparison Graph </h2>

![plot of chunk unnamed-chunk-3](figure/unnamed-chunk-3.png) 

```
##   Dates Sentiments Stockprice_change
## 1  Day1        113                82
## 2  Day2        -33               -35
## 3  Day3        113               -38
## 4  Day4        -52                75
## 5  Day5        -29               -41
```

 In This Assignment, we are asked to calculate the sentiment analysis for Microsoft, to predict the stock prices in the real market, we are calculating the sentiment analysis by collecting data(tweets) from twitter using twitter credentials. We have created different attributes and tables to compare the sentiment analysis against stock changes on that particular day.

      We have generated 5 histographs reflecting each day's sentiment analysis on each diagram for all five days. We have also generated a table which shows the data for the sum of sentiments for each day and the Stock change for that particular day. The stock price change values are calculated using daily stock price change * 100.
      
      And a final bar graph which has the data with all the sentiment data collected against the real world stock price change, which helps us understand the predictions of the sentiment analysis data to microsoft's original stock change on daily basis. 
      
      In the bar graph, we can see that the predictions for day1 , day2 , day5 are positive , that is, sentiment analysis was able to predict the change in the stock prices correctly , whereas in case of day3 and day4 the predictions were wrong because the stock price on day3 has fallen down but our sentiment analysis has predicted that there would be a rise in the stock price for that particular day , which is wrong. Thus we can say that we cannot depend on the sentiment analysis completely for predicting the stock prices.
