## Visualizing the Twitter discourse on COVID-19

### Daily Counts
[#CoronavirusOutbreak](https://weiaiwayne.github.io/COVID19Twitter/CoronavirusOutbreak_DailyCount.html){:target="_blank" rel="noopener"}

### What data are we collecting
My research team started collecting COVID-19-related tweets in late January, 2020, shortly after the lockdown of Wuhan, and weeks before the novel coronavirus was given the official name COVID-19. The hashtags we have been tracking include: 

- _#CoronavirusOutbreak_
- _#COVID19_ 
- _#Coronvirus_
-_#nCoV2019_ 
- _#2019nCov_ 
- _#WuhanCoronavirus_ 
- _#CoronavirusChina_ 
- _#CoronaVirusUpdate_
- _#CoronavirusPandemic_
- _#Wuhanvirus_ 
- _#Wuhancoronavirus_
- _#WuhanOutbreak_
- _#Wuhanquarantine_
- _#FlattenTheCurve_ 
- _#COVID19US_, etc. 

Understandably, these are only a small part of all relevant hashtags; @jasonbaumgartne from Pushshift.io found over one million COVID-19-related hashtags [the list](https://files.pushshift.io/coronavirus_hashtags.txt).  

### How the data are collected

We started off with a low-budget and low-carbon approach to data collection: we set up five Python scripts using 5 different Twitter API tokens on a [Raspberry pi 4](https://www.raspberrypi.org/products/raspberry-pi-4-model-b/) to pull tweets from the Twitter REST API. The scripts run at 10~15-hour intervals. Our final dataset is huge, recording millions of tweets, but unlikely all-encompassing due to the rate limits of the REST API and the arbitrary time intervals. The dataset is, at best, a convenience sample of the global Twitterverse.  

The visualization you are seeing here is a spin-off of a larger project on the politicization of COVID-19. Even based on the incomplete data, the visualization should give you a glimpse into how the conversation has evolved and where it is heading.  


### Timeline

In the coming weeks/months, we will roll out the visualization one hashtag at a time. Because Pushshift.io will soon [publish 250 million tweets related to the Coronavirus](https://twitter.com/jasonbaumgartne/status/1240469078009171970), which is a much bigger dataset than the one we currently use. We plan to build a separate visualization based on the Pushshift dataset in the near future.  

### Support or Contact

Having question with the visualization? Want a collaboration on research or grants? Please contact me [@WeiaiWayne](https://twitter.com/WeiaiWayne).
