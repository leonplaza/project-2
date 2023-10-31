# Project II - Music & Mental Health Survey 

## Overview

For this project I analyze a dataset of a Mental Health survey that provides data about Music preferences and mental health of the participants with the purpose of finding possible correlations. The objective of this project is to find insights and conclusions about the correlation between mental problems and music taste or habits with additional analysis using age to find correlations with the variables mentioned before.

## Requirements/Libraries Used:

Libraries used in this script:
- Pandas
- Requests
- Seaborn
- Beautiful (from bs4)

## Web Scraping: What is the generation of the participants of the survey?

As age of the participants was provided, it is possible to classify the age in a categorical way by defining what generation they belong. The information of the generations and the birthyear asociated was extracted from this website: "https://www.careerplanner.com/career-articles/generations.cfm". 


## 1.- Mental Health indicators by generation

This table shows the average score of the mental health indicators and additional variables. The values represent from a scale from 0 to 10 on how regularly they experience this type of feelings or issues related to mental health. 

table

The next plots corresponds to the boxplots with the information about the distribution (quantiles) of the mental health indicators 

the results suggest that younger generations are more prone to have mental problems compared to older generations. Another discovery is that the ratio of instrumentalist or composers is quiet equal to every generation, so that could suggest that the age doesn't have a correlation or impact on the probability of playing instruments or being a composer.




## 2.- Mental Health indicators by favorite music genre listened

The purpose of this section is to find if there is a correlation between the type of music the participant listen to and their mental health. 

The following tables show the ranking of genres that averages the highest and lowest score for each one of the 4 mental health indicators respectly. 

table 1

table 2

The result indicates that "LoFi" listeners have the highest average in all mental health indicators with the exception of the anxiety indicator. On the other hand, "Rap" and "Classical" listeners are the ones with the lowest averages of part of the indicators. 

## 3.- Additional analysis: Are Instrumentalists more common in certain genres?

The purpose of this section is to find if having a specific favorite genre makes you more prone to play an instrument

As data about if they play instrument is a binary variable (Yes or No), the average of the data represents the ratio of the total of participants that plays an instrument and the total participants. 

Table

The results shows that more than half of the classical and jazz music listeners play an instrumental, which kinda makes considering that those type of music is characterized by their high technical level and complexity. On the bottom of the list the genres R&B, LoFi and Hip-Hop shows the lowest ratio of intrumentalist, which kinda makes sense as those genres are more "voice/liric" centered rather than instrumental centered, and in addition both LoFi and Hip-Hop doesn't strictly need instruments (those genres use softwares instead) to be played or produced.



## 4.- Additional analysis: Are composers more common in certain genres?


The purpose of this section is to find if having a specific favorite genre makes you more prone to being a composer

Similar to the previous section, the average of the data represents the ratio of the total of participants that are composer and the total participants. 

Table

The results are similar quite similar to the previous section, classical and jazz music listeners shows the highest ratio of composer, althouth this time both ratios are below the 50%. On the bottom of the list the genres Pop, R&B, and K-Pop shows the lowest ratio of composer, which kinda makes sense as pop genre and its derivates focused more on popularity rather than creativity.



## 5.- Additional analysis: What genre has the most loyal listeners?

The participants of this survey responded how frequently do they listen to all 16 genres pointed in the survey. With this information we can see how "loyal" are music listeners toward their favorite genre, with loyal meaning that they listen mainly to one genre (their favorite). So for example, a participant who's favorite music is rock music but listen to other genre with the same frequency as rock wouldn't be considered as a "loyal" fan, but if he listen to rock with significant more frequency than other music, then that would be considered loyal. Loyalty to a genre could also be interpreted as if the favorite genre of the contestant is the same as the genre that he listen to the most.

By changing the frequency from categorical (Never, Rarely, Sometimes, Very frequently) to a numeric scale (0, 1, 2 & 3 respectly) we can quantify the frequency. Now that the data is numeric, we can sum the values of each 14 genres frequency from a specific row, and if the frequency of a certain genre is divided by this sum we obtain the percentage of time listening to the genre from the total of music listened. 

table

The top of the table suggest that Country, Classical and Metal fans consume their genre more than 25% of the total of music they listen, making them the top most "loyal" fans, according to this metric. The bottom of the table suggest that Hip-Hop, Jazz and LoFi listeners , this could suggest this genre fans tend to listen more to other genres





















