<p align="center">
<img  src="http://arqmain.net/Researches/Researchs/Amazon_Reviews/images/amazon1.gif">
</p>

 # Data Science: Text Mining and Sentiment Analysis on Amazon Reviews 

On this project, we deal with an application of TEXT MINING and SENTIMENT ANALYSIS to the internet AMAZON web portal in order to dig and get information about its Reviews.

The target population corresponds to the Amazon's reviews by September 10, 2019.

I use the rvest r package and a double and a for loop script to get all the information from the website. This script allows capturing the data quickly from all the pages throughout the website.

For the treatment of the text (characters) the “stringr” and “tidyr” libraries are preferably used through many of the functions that both incorporate.

The data wrangling and data processing are covered with various libraries but, preferably, dplyr, tydiverse, lubridate, tidytext, SnowballC, wordcloud, RColorBrewer, corpus,  drlib, and tm are used. The visualization of the results is generated through tidytext, gridExtra, hrbrthemes, ggplot2 or some of its extensions.

The specifics objectives are:
1) To web scrape the site in order to get the full database available online.
2) Perform traditional text mining based on data obtained with web scraping.
3) Develop sentiment analysis generating global results and by grouping

There are many applications that the area of text mining can address. The techniques applied in this project can be extrapolated to various situations and problems typical of human development in general, and scientific research in particular. Research Analysis in all its wide range of possibilities is especially benefited with the implementation and use of these text mining and sentiment analysis techniques as a material of high value in its daily development.


### TABLE OF CONTENTS

### WHAT IS IT ALL ABOUT?

### DATA SOURCE, WEB SCRAPING, AND R PACKAGES
#### DATA SOURCE
#### WEB SCRAPING AND R PACKAGES

### FEATURE ENGINEERING
#### CREATION OF NEW VARIABLES
#### FINAL DATASET

### SOME CLASSICAL TEXT MINING RESULTS
#### What about top 10 words with major frequence?
#### What about frequent terms and their associations with word “amazon”?
#### What about Word cloud of the 200 most frequent words?
#### What about Word cloud of the 200 most frequent words?
#### What about Top 5 Common Words by months?
#### What about Top 5 Common Words by week days?
#### What about Top 5 Common Words by day?

### SOME SENTIMENT ANALYSIS RESULTS
#### What about Top 10 positive and negative sentiment contribution words?
#### What about the contribution to positive and negative sentiment of words with frequency 100 or more?
#### What about Word cloud of the 200 positive and negative sentiment contribution words?
#### What about the evolution of the Net Sentiment Ratio over the years?
#### What about Comparing the word frequencies of 2018 with other years?
#### How correlated are the word frequencies between 2018 and other years?
#### Evolution of Net Sentiment Ratio (NSR) in total terms

### DISCUSSION

