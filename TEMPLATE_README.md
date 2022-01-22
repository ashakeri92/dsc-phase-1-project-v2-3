# Microsoft Movie Studios Analysis

**Authors**: Armun Shakeri

## Overview

This project analyzes current movie trends, budgets, gross income, and ratings in order to help Microsoft Studios best decide which movies to produce in its new upcoming studio. Analysis shows that if Microsoft studios produces movies that are in high demand positive gross profit will be reflected.

## Business Problem

Microsoft is seeking to enter into the movie industry and does not know what movies to create. We need to analyze what types of movies are currently trending, most popular movie genres, highest grossing movies of all time, highest budgeted movies, and movie title basics. For Microsoft's new movie studio to be profitable we need to pick a movie genre that is currently in demand and which movies had highest gross incomes, doing this ensures that the movie will have a positive inception and be profitable.

## Data

For this project we gathered information about movie income, basics, and ratings from imdb. Movie production budget information was gathered from The Numbers. In these samples we only gathered information from top grossing films to identify if there were any common themes and/or patterns between top grossing films and their respective genres. The end goal of our final data was to clean this information and provide 4 variables, production budget, domestic gross income, film ratings, and count of film genres.  


## Methods

Ahead of modeling and analyzing the data, we needed to clean the information we had presented. To do so we removed movie run times, start year, release date, and worldwide gross income, and combined all the information into one complete data set which provided the movies' title, domestic_gross, production_budget, genre, and average rating. When we began to model this data we first calculated statistical methods (mean, median, mode...etc) this helped create a general idea of where the movie industry is currently at in todays market, and was a good baseline for analysis. We then modeled this data using histograms which allowed us to clearly see which movies and/or genres were the top of what was being analyzed, such as top grossing films or production budgets. 


## Results



Present your key results. For Phase 1, this will be findings from your descriptive analysis.

***
Questions to consider:
* How do you interpret the results?
* How confident are you that your results would generalize beyond the data you have?
***

Here is an example of how to embed images from your sub-folder:

### Visual 1



![graph1](./images/viz1.png)

## Conclusions

The following below are three reccomendations for Microsoft Studio's first film:

1) The film should have a maximum budget of $200,000,000. The film will need to have a large budget to allocate to  hiring top actors and having up to date visual affects. 

2) The film's genre should be action, adventure, and animation. Having aspects of several genres will help the film attract a larger audience.

3) The film should be a family type of movie. Genres that contain aspects of action, adventure, and animation  are also geard more towards the family demographic, and like point #2 if the film is geared strictly for an older audience it will have a smaller target audience. Our goal is for Microsoft's first movie to to have a broad target audience.


## For More Information

Please review our full analysis in analysis.ipynb or our [presentation](./DS_Project_Presentation.pdf).

For any additional questions, please contact Armun Shakeri ashakeri62@gmail.com 

## Repository Structure

Describe the structure of your repository and its contents, for example:

```
├── README.md                           <- The top-level README for reviewers of this project
├── dsc-phase1-project-template.ipynb   <- Narrative documentation of analysis in Jupyter notebook
├── DS_Project_Presentation.pdf         <- PDF version of project presentation
├── data                                <- Both sourced externally and generated from code
└── images                              <- Both sourced externally and generated from code
```
