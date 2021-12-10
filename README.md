# Proposal for Microsoft Studios
Contributing Members: Matthew Samson, Jeff Beech, and Grace Arina
![image](https://user-images.githubusercontent.com/93217519/145618350-99e5d97e-3ca9-44ca-980c-59b7529f3bf7.png)

## Project Overview
The aim of this project is to analyze the trends in the movie industry to discover ways for Microsoft to break into the industry and stand out amongst its well-established competitors. We analyzed the top 100 films between 2008 and 2018, their production budgets, return on investment, the most consistently profitable genres and the comparative review of domestic and worldwide data.

## Data
The datasets of this project are from the following websites:
 - Box Office Mojo
 - IMDB
 - The Numbers

## Methods
We performed exploratory data analysis with visualizations to better understand the different information from the datasets. We restricted the data to an eleven year period (2008-2018).
We had several questions that we wanted to explore to improve the accuracy of our results:
 - What are the top 100 films by gross returns over the time period? What are their genres? If we aggregate, what are the three most common genres? Who directed them?
 - Are the relative profits of big budget movies higher or lower than low budget movies? Are the relative profits of one category more dispersed than the other categories?

## Results
### What budget levels are profitable?
While traditionally it is common to look only at net profits as a measure of success and try to extrapolite trends from that metric, we've determined that a potentially much more important metric than “most profitable” is “most often profitable.” To get a sense for this, the following two graphs illustrate the distribution of net profits across different budget sizes. Most of note is that only 56% of low-budget films are profitable, while over 93% of big-budget films are profitable. That combined with a high median profit for big-budget movies suggests that Microsoft would do best to focus the largest share of their efforts and resources on big-budget films.
![image](https://github.com/snakeeyes021/movies-by-microsoft/raw/main/Images/lowbudgetdistribution.png)
![image](https://github.com/snakeeyes021/movies-by-microsoft/raw/main/Images/bigbudgetdistribution.png)

### What Genres should Microsoft Studios focus on?
If we examine the median profits of each individual genre, we see that animation and adventure have the highest two median profits, by considerable margins. We found that the top two most consistently profitable genres below animation are adventure and fantasy movies. Moreover, we discovered animation is consistently profitable with 83% of films produced under this category yielding profits.
![image](https://github.com/snakeeyes021/movies-by-microsoft/raw/main/Images/genre_profit_medians.png)

### Top 6 Grossing Studios: 2008 - 2018
In terms of revenue, it may not necessarily be productive for Microsft to focus its efforts domestically. The data in this section shows that worldwide gross earnings represent a larger portion of total gross in most instances.
Microsoft should target international markets to capture the greatest revenue generating potential, while also leveraging its global influence to create a dominant brand name in the film industry.

![image](https://github.com/snakeeyes021/movies-by-microsoft/raw/main/Images/top_grossing_movies_by_studio.jpg)


### When should we release the movies?

These findings suggest that big-budget movies are generally released in the summer and also leading up to the holidays, while mid-budget movies avoid the summer and low-budget movies avoid the holidays.
![image](https://github.com/snakeeyes021/movies-by-microsoft/raw/main/Images/bigbudget_vs_time.png)



## Conclusion
This analysis leads to three recommendations to Microsoft for entering the film studios industry:


1. Focus the largest share of your resources and energies on big-budget tent-pole releases: not only do they tend to be more profitable, but they also tend to more consistently be profitable in the first place.

2. Open or acquire an animation arm that focuses on the same genres as the parent studio–adventure and fantasy–as these are the most consistently profitable with high median profits.

3. In choosing scripts, stars, shooting locations, and the like, consider the impact or appeal to specific international markets. They will generate the vast majority of your profits.





## For More Information
See the full analysis in the [Jupyter Notebook](https://github.com/snakeeyes021/movies-by-microsoft/blob/main/Combined%20Notebook.ipynb) or review [this presentation](https://github.com/snakeeyes021/movies-by-microsoft/raw/main/Presentation.pdf).
