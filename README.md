# Dataset-Analysis
Analyzing data to extract meaningful insights from it.

## Table of contents

* [Methods and Tools](#methods-and-tools)
* [About Dataset](#About-Dataset)
* [Conclusion](#Conclusion)
* [Acknowledgement](#Acknowledgement)
* [Contact](#contact)


## Methods and Tools

* Python 
* Jupyter Notebook
* matplotlib
* seaborn

## About Dataset

This dataset contains information about Anime (16k), Reviews (130k) and Profiles (47k) crawled from https://myanimelist.net/ at 05/01/20.

The dataset contains 3 files:

* animes.csv contains list of anime, with title, title synonyms, genre, duration, rank, populatiry, score, airing date, episodes and many other important data about individual anime providing sufficient information about trends in time about important aspects of anime. Rank is in float format in csv, but it contains only integer value. This is due to NaN values and their representation in pandas.

* profiles.csv contains information about users who watch anime, namely username, birth date, gender, and favorite animes list.

* reviews.csv contains information about reviews users x animes.


## Conclusion
We find out which anime/show is most popular or which is highly rated and in some cases if anime is highly rated it doesn't mean it is popular among viewers. We can analyze the ratings to see Anime trend and how the genre can be a trend.

## Acknowledgement
Dataset or csv file which we used is from Kaggle(<a href="https://www.kaggle.com/datasets/marlesson/myanimelist-dataset-animes-profiles-reviews">anime.csv</a>). 

## Contact
If you loved what you read here and feel like we can collaborate to produce some exciting stuff, or if you
just want to shoot a question, please feel free to connect with me on 
<a href="mailto:nimish786.kalwar@gmail.com">email</a> or 
<a href="https://www.linkedin.com/in/nimish-kalwar/" target="_blank">LinkedIn</a>
