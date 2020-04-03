## Visualizing the Social Media discourse on COVID-19

## Reddit Discourse

- [Top Domains Over Time](https://weiaiwayne.github.io/COVID19Twitter/Reddit/Vis_Daily_TopDomains.html){:target="_blank" rel="noopener"}

## Twitter Hashtags

### _#CoronavirusOutbreak_
- [Daily Counts](https://weiaiwayne.github.io/COVID19Twitter/CoronavirusOutbreak_DailyCount.html){:target="_blank" rel="noopener"}

- [Twitter Bio Hashtag Networks - Jan. 2020](https://weiaiwayne.github.io/COVID19Twitter/CoronavirusOutbreak_Bio_Hashtag_Networks_jan.html){:target="_blank" rel="noopener"}
- [Twitter Bio Hashtag Networks - Feb. 2020](https://weiaiwayne.github.io/COVID19Twitter/CoronavirusOutbreak_Bio_Hashtag_Networks_feb.html){:target="_blank" rel="noopener"}
- [Twitter Bio Hashtag Networks - Mar. 2020](https://weiaiwayne.github.io/COVID19Twitter/CoronavirusOutbreak_Bio_Hashtag_Networks_march.html){:target="_blank" rel="noopener"}

- [Tweet Hashtag Networks - Jan. 2020](https://weiaiwayne.github.io/COVID19Twitter/CoronavirusOutbreak_Tweet_Hashtag_Networks_jan.html){:target="_blank" rel="noopener"}
- [Tweet Hashtag Networks - Feb. 2020](https://weiaiwayne.github.io/COVID19Twitter/CoronavirusOutbreak_Tweet_Hashtag_Networks_feb.html){:target="_blank" rel="noopener"}
- [Tweet Hashtag Networks - Mar. 2020](https://weiaiwayne.github.io/COVID19Twitter/CoronavirusOutbreak_Tweet_Hashtag_Networks_march.html){:target="_blank" rel="noopener"}

- [Galaxy-look of the Bio Hashtag Networks - Week 1](https://weiaiwayne.github.io/COVID19Twitter/grapher/w1_coronavirusoutbreak_b.html){:target="_blank" rel="noopener"}
- [Galaxy-look of the Bio Hashtag Networks - Week 2](https://weiaiwayne.github.io/COVID19Twitter/grapher/w2_coronavirusoutbreak_b.html){:target="_blank" rel="noopener"}
- [Galaxy-look of the Bio Hashtag Networks - Week 3](https://weiaiwayne.github.io/COVID19Twitter/grapher/w3_coronavirusoutbreak_b.html){:target="_blank" rel="noopener"}
- [Galaxy-look of the Bio Hashtag Networks - Week 4](https://weiaiwayne.github.io/COVID19Twitter/grapher/w4_coronavirusoutbreak_b.html){:target="_blank" rel="noopener"}
- [Galaxy-look of the Bio Hashtag Networks - Week 5](https://weiaiwayne.github.io/COVID19Twitter/grapher/w5_coronavirusoutbreak_b.html){:target="_blank" rel="noopener"}
- [Galaxy-look of the Bio Hashtag Networks - Week 6](https://weiaiwayne.github.io/COVID19Twitter/grapher/w6_coronavirusoutbreak_b.html){:target="_blank" rel="noopener"}
- [Galaxy-look of the Bio Hashtag Networks - Week 7](https://weiaiwayne.github.io/COVID19Twitter/grapher/w7_coronavirusoutbreak_b.html){:target="_blank" rel="noopener"}
- [Galaxy-look of the Bio Hashtag Networks - Week 8](https://weiaiwayne.github.io/COVID19Twitter/grapher/w8_coronavirusoutbreak_b.html){:target="_blank" rel="noopener"}

### _#COVID19_ 
### _#Coronvirus_
### _#nCoV2019_ 
### _#2019nCov_ 
### _#WuhanCoronavirus_ 
### _#CoronavirusChina_ 
### _#CoronaVirusUpdate_
### _#CoronavirusPandemic_
### _#Wuhanvirus_ 
### _#Wuhancoronavirus_
### _#WuhanOutbreak_
### _#Wuhanquarantine_
### _#FlattenTheCurve_ 
### _#COVID19US_, etc. 

## How the data are collected
My research team started collecting COVID-19-related tweets in late January, 2020, shortly after the lockdown of Wuhan, and weeks before the novel coronavirus was given the official name COVID-19. Understandably, the hashtags included in the project are only a small part of all relevant hashtags; @jasonbaumgartne from Pushshift.io found over one million COVID-19-related hashtags [the list](https://files.pushshift.io/coronavirus_hashtags.txt). 

We started off with a low-budget and low-carbon approach to data collection: we set up five Python scripts using 5 different Twitter API tokens on a [Raspberry pi 4](https://www.raspberrypi.org/products/raspberry-pi-4-model-b/) to pull tweets from the Twitter REST API. The scripts run at 10~15-hour intervals. Our final dataset is huge, recording millions of tweets, but unlikely all-encompassing due to the rate limits of the REST API and the arbitrary time intervals. The dataset is, at best, a convenience sample of the global Twitterverse.  

The visualization you are seeing here is a spin-off of a larger project on the politicization of COVID-19. Even based on the incomplete data, the visualization should give you a glimpse into how the conversation has evolved and where it is heading.  


## Timeline

In the coming weeks/months, we will roll out the visualization one hashtag at a time. Because Pushshift.io will soon [publish 250 million tweets related to the Coronavirus](https://twitter.com/jasonbaumgartne/status/1240469078009171970), which is a much bigger dataset than the one we currently use. We plan to build a separate visualization based on the Pushshift dataset in the near future.  

## Support or Contact

Having question with the visualization? Want a collaboration on research or grants? Please contact me [@WeiaiWayne](https://twitter.com/WeiaiWayne).

## Public COVID19 Tweet Datasets

[Data from Georgia State University's Panacea Lab](http://www.panacealab.org/covid19/?author_id=66014285&dt_dapp=1&dt_platform=com.douban.activity.wechat_friends&from=singlemessage)

[Data from University of Southern California](https://github.com/echen102/COVID-19-TweetIDs)
