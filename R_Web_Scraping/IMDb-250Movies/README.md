<p align="center">
<img  src="http://arqmain.net/Researches/Researchs/MoviesIMDb/MoviesIMDb250.png">
</p>

Application of DATA MINING to the Internet Movie Database site IMDb, in order to dig and get information from the Top 250 Best Rating Film/Short Film of 20/21 Centuries [released between 1900-01-01 and 2019-07-01].

The objectives here are to get a database with the specif information, explore the database, study some interesting relationships and present the results by using Web Scraping, Data analysis, and Visualizations with R.

An equivalent project using Python instead of R is in a folder, but I will develop it sometime later. Anyway, some time ago I made a similar project using Python, but the master database was not the same and also I did not use web scraping to obtain the target database. You can access to this project here.

Finally, the database on the IMDB portal that defines the target population turns out to be somewhat messy, making the following quotation valid for this project as well:
“Tidy datasets are all alike but every messy dataset is messy in its own way.” - Hadley Wickham

Anyway, this is really an emulation of what the late and brilliant Russian writer Leo Tolstoy [Lev Nikolayevich Tolstoy: Sep091828-Nov20190 ] state in his book -Anna Karenina: “All happy families are alike; each unhappy family is unhappy in its own way”. 

## TABLE OF CONTENTS

## WHAT IS IT ALL ABOUT?

## DATA SOURCE, WEB SCRAPING, AND R PACKAGES
### DATA SOURCE
### WEB SCRAPING AND R PACKAGES

## FEATURE ENGINEERING
### ADDING NEW INFORMATION
### CREATION OF NEW VARIABLES
### FINAL DATASET

## DATA ANALYSIS
### 1 INDIVIDUAL GLOBAL DISTRIBUTIONS
#### 11 What about the 10 movies with the highest profits?
#### 12 What about the 10 most voted movies?
#### 13 What about 10 most highly rated movies?
#### 14 What about 10 movies most highly ranked?
#### 15 How about 10 movies with the highest metascore?
#### 16 How about 10 longer movies?

### 2 GROUPED DISTRIBUTIONS by Oscar winner, Ngenre, Ndirectors, Nstarts
#### 21 Group by Oscar winners
#### 22 Group by Ngenre
#### 23 Group by Ndirectors

### 3 HOW ABOUT SOME TEST OF HYPOTHESIS ON FEATURES MEAN EQUALITY AND POST HOC ANALYSIS?
#### 31 Oscar winners category
##### 311 How about revenue’s averages troughout Oscar?
##### 312 How about vote’s averages troughout Oscar?
##### 312 How about vote’s averages troughout Oscar?

#### 32 Ngenre category
##### 321 How about revenue’s averages troughout Ngenre?
##### 322 How about vote’s averages troughout Ngenre?
##### 323 How about rating’s averages troughout Ngenre?

#### 33 Ndirectors category
##### 331 How about revenue’s averages troughout Ndirectors?
##### 332 How about vote’s averages troughout Ndirectors?
##### 333 How about rating’s averages troughout Ndirectors?

#### 34 Summary table of the means analysis

### 4 HOW ABOUT CORRELATION AND SOME VISUALIZATIONS ABOUT IT?
#### 41Features Distribution and Pearson’s Correlations
#### 42 Some Scatter Global and Grouped Visualizations
##### 421 By Oscar
###### 4211 Visualizations revenue (x) v/s votes (y) by Oscar [Si / No]
###### 4212 Visualizations revenue (x) v/s rating (y) by Oscar [Si / No]

##### 422 By Ngenre
###### 4221 Visualizations revenue (x) v/s votes (y) by Ngenre [1, 2, 3]
###### 4222 Visualizations revenue (x) v/s rating (y) by Ngenre [1, 2, 3]

##### 423 By Ndirectors
###### 4231 Visualizations revenue (x) v/s votes (y) by Ndirectors [1, 2]
###### 4232 Visualizations revenue (x) v/s rating (y) by Ndirectors [1, 2]

### 5 HOW ABOUT GENDERS, DIRECTORS AND STARS DISTIBUTION IN THE 250 FILMS?
#### 51 Genders of films used in the 250 movies?
#### 52 Combination of movie genders used in the 250 films?
#### 53 Film directors of the 250 movies?
#### 54 Movie stars in the 250 films?

## DISCUSSION

<hr>

><i>Hector Alvaro Rojas<br>
>Data Science, Visualizations and Applied Statistics / August 10, 2019<br>
>Email: <arqmain2010@gmail.com> <br>
>Url: [http://www.arqmain.net]   /   GitHub: [https://github.com/arqmain]</i>
