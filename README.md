# case_study_2

## Big Data 

After connecting to the dataset via spark, we noticed that there are intricate schema, so we narrowed it down to fewer features: 
* columns = <br>
    name, tweet(text), followers count, friends count, language, hashtags, time zone, time stamps, verified, retweet count, favorite count. 
* We only used 20% of samples from french_tweets.json. 

There were many null values so we dropped those rows given time constraints.  

Below we can see the  distribution of language used in French Tweets. 

![](images/lang1.png)


Below are the top 25 time zones tweeted from. 

![](images/country1.png)

Below is the graph of the timezone mentioned above. 

![](images/country2.png)

Changed the date type from string to datetime object.

![](images/code_for_volume.png)

## 

![](images/volume.png)



