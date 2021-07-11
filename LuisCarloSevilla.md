---
title: "First Markdown Activity"
author: "Luis Carlo Sevilla"
date: "7/10/2021"
output: html_document
---

## Studying Data

As Professor Raymark mentioned, we generate almost **petabytes** of data per day. These data are now considered as goldmines to not only just Data Scientist but also people in businesses, politics, medical field, and many more. Data can be used to solidify studies and help create solutions to modern day problems and can even be used for personal use but in order to do so the process of analyzing data must be done to draw meaningful information out of the pool of unsorted data. 

***

## Application of Data Science
![](https://miro.medium.com/max/700/1*209COHJ1LFfInRPuWQFylQ.png)

Every content we consume in the internet---or anything technology related--- has been influenced or structured by Data Science to be optimized to its greatest capability. One application that we hold near and dear to our hearts is the **Autocomplete** function that we can find in search engines such as Google, Bing, DuckduckGO, and many more. The autocomplete function was first developed by Kevin Gibbs who sought to create a URL Completion algorithm but later developed to be the autocomplete function we know and love. It was created with the intention of taking advantage of the technological affordances of time to make web navigation more efficient. The algorithm of this function is based on the numerous search queries of millions of the Google search engines users. It was later then optimized with the help of **Artificial Intelligence** to be further accurate not only based on the queries of other users but to also cater the interest and search history of the user. 

*** 

## Data Science and Chess

Chess can be a rather difficult and complex game and is played by millions of people all over the world. Recently, there has been a massive spike of players in online chess sites such as [Lichess.com](lichess.com), [Chess.com](Chess.com), and many more. [Lichess.com](lichess.com) has given a online data set of game statistics that is free to use. This data set includes the following:

* Win rate of White and Black
* Opening Strategy Used 
* Number of Turns per Game
* Player's Rating

Here is a snippet of data values:

```{r, echo=FALSE}
chess <- read.csv("chess-game - chess-game.csv", header = TRUE, sep = ",")
kable(chess)
```

I propose to use these inf



## Including Plots

You can also embed plots, for example:

```{r pressure, echo = FALSE}
plot(pressure)
```

Note that the `echo = TRUE` parameter was added to the code chunk to prevent printing of the R code that generated the plot.
