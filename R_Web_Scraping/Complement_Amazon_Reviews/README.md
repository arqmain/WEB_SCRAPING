<p align="center">
<img  src="http://arqmain.net/Researches/Researchs/Complement_Amazon_Reviews/images/amazon3.gif">
</p>

 # Data Science: Complement Project on Text Mining and Sentiment Analysis on Amazon Reviews

On this project, we deal with an application of TEXT MINING and SENTIMENT ANALYSIS to the internet AMAZON web portal in order to dig and get information about its Reviews.

The present project is a complement to the one previously developed by me [https://www.linkedin.com/pulse/data-science-text-mining-sentiment-analysis-amazon-reviews-rojas] on a similar theme, which was only addressed in a general way. The current article incorporates a more refined treatment of sentiment analysis adding much more value to the analysis of the data in the respective subject.

More specifics methods have been applied to develop this article than the ones used on the first project: Lexical diversity and density, TF-IDF, word trending, N-grams, and Sentiment analysis. All these paths allow reaching several results considering the information resident on the Amazon reviews web site as of September 10, 2019.

The data wrangling and data processing are covered with various libraries but, preferably, dplyr, tydiverse, lubridate, tidytext, SnowballC, wordcloud, RColorBrewer, corpus, drlib, ggrepel, igraph, ggraph, reshape2, knitr, kableExtra, and tm. The visualization of the results is generated through gridExtra, ggplot2 or some of its extensions.

The specifics objectives are:

1) Perform traditional text mining.
2) Develop traditional n-grams analysis.
3) Develop sentiment analysis generating global results and by grouping.
4) Use n-grams to provide a context in sentiment analysis.

There are many applications that the area of text mining can address. The techniques applied in this project can be extrapolated to various situations and problems typical of human development in general, and scientific research in particular. Research Analysis in all its wide range of possibilities is especially benefited with the implementation and use of these text mining and sentiment analysis techniques as a material of high value in its daily development.


## TABLE OF CONTENTS   (  [  Link to project results ]( http://arqmain.net/Researches/Researchs/Complement_Amazon_Reviews/Complement_AMAZON_Reviews.html))

### WHAT IS IT ALL ABOUT?

### DATA SOURCE  AND  R PACKAGES
#### DATA SOURCE
#### R PACKAGES

### FEATURE ENGINEERING
#### CREATION OF NEW VARIABLES
#### FINAL DATASET

### SOME CLASSICAL TEXT MINING RESULTS
#### What about reviews per week?
#### What about most common words in reviews?
#### What about yearly popular words?
#### What about monthly popular words?
#### What about week day popular words?
#### What about word length?
#### What about word length global?
#### What about wordcloud words with “word_length” [10, 20]?
#### What about word Lexical Diversity?
#### What about Lexical Density?
#### What about TF-IDF?
#### What about Pairwise Comparisons?
#### Important words trending in reviews

### SOME NGRAMS ANALYSIS RESULTS
#### What about Bigrams?
#### What about Trigrams?

### SOME SENTIMENT ANALYSIS RESULTS
#### Sentiment Analysis based on BING Lexicon
#### Sentiment Analysis based on AFINN Lexicon
#### Comparison of Bing and Afinn sentiment dictionaries results

### USING BIGRAMS TO PROVIDE CONTEXT IN SENTIMENT ANALYSIS
#### Words contributed the most in the wrong direction
#### Checking most common negation words

### SOME SPECIAL RESULTS
#### The shortest reviews
#### The Longest Reviews
#### The Most Positive Review
#### The Most Negative Reviews

### DISCUSSION

<hr>

><i>Hector Alvaro Rojas<br>
>Data Science, Visualizations and Applied Statistics / October 08, 2019<br>
>Email: <arqmain2010@gmail.com> <br>
>Url: [http://www.arqmain.net]   /   GitHub: [https://github.com/arqmain]</i>

