## Visualizing the Twitter discourse on COVID-19

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


### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/weiaiwayne/COVID19Twitter/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
