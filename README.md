# Microsoft Movie Analysis Project

![microsoft.png](https://github.com/yesimcebeci/Movie_Analysis_PROJECT_1/blob/main/images/microsoft.png)

## Project Overview

In this analysis, I will perform an analysis on a large data set of approximately 3,000 movies. The data includes many different types of information about each movie, ranging from the the director, the studio, the genre to other information like the budget, the box office earnings from different datas. I will analyze this data set to determine what contributes to a movie being a “success”. For this analysis, I will define success in financial terms, basing the success of a movie on the amount of money it earns in comparison to the movie’s budget.
I decided to use data collected from IMDB and The Numbers (TN) and Box Office Mojo(BOM) websites. The original datasets contained information about 11 data files which have more then 100000 data movies. I decided to use 6 different datasets and decided to focus on three categories:

1) Genres 2) Studios 3) Directors

For those 3 catagories I decided to sort by ROI, Budget and Numbers to make some prediction and recommendation

![movie.png](https://github.com/yesimcebeci/Movie_Analysis_PROJECT_1/blob/main/images/movie.png)

### Business Problem

Microsoft sees all the big companies creating original video content and they want to get in on the fun. They have decided to create a new movie studio, but they don’t know anything about creating movies. You are charged with exploring what types of films are currently doing the best at the box office. You must then translate those findings into actionable insights that the head of Microsoft's new movie studio can use to help decide what type of films to create.

### The Data

In the folder `Data` are movie datasets from:

* imdb.title.basics
* imdb.name.basics.csv
* bom.movie_gross
* imdb.title.crew.csv.gz
* imdb.title.principals.csv
* tn.movie_budgets.csv

### Methods

* This project uses descriptive analysis and visualizations including trends over time. It also provides Microsoft a useful overview of a genre's R.O.I. The Return On Investment metric was heavily utilized for this analysis and to ensure stakeholders are on the same page: the definition for R.O.I. is (Net Profit / Cost of Investment) x 100. In this analysis, Net Profit is Domestic, Foreign, Worldwide gross and Cost of Investment is Production Budget. The three questions explored are:

1) Which genres should we create films in?

2) Which studios provide the highest average ROI?

3) Which directors made highest profit by genre?


## Results


![Top_5_Genres.png](https://github.com/yesimcebeci/Movie_Analysis_PROJECT_1/blob/main/images/Top_5_Genres.png)


![Top_5_Directors.png](https://github.com/yesimcebeci/Movie_Analysis_PROJECT_1/blob/main/images/Top_5_Directors.png)


![Top_5_Jason_Blum.png](https://github.com/yesimcebeci/Movie_Analysis_PROJECT_1/blob/main/images/Top_5_Jason_Blum.png)


![Top_5_Studios.png](https://github.com/yesimcebeci/Movie_Analysis_PROJECT_1/blob/main/images/Top_5_Studios.png)


![Top_5_Low_Budget_Genres_for_WB_Studio.png](https://github.com/yesimcebeci/Movie_Analysis_PROJECT_1/blob/main/images/Top_5_Low_Budget_Genres_for_WB_Studio.png)



## Conclusions

According to the above my analysis, here are my recommendations for Microsoft as they begin to work on their new movie studio. I will make three recommendation for each category.

1) First of all for genre category , I will recommend 'Romance' genres. It looks like , it is a good idea start with 'Romance' genre. If we look at the highest mean ROI according to my analysis, Romance genre has the highest mean ROI. Second one is follow with 'Sport' genre and if we compare the result of Romance genre and Sport genre there is pretty much difference between the numbers. And also if we look at the director who has the highest mean ROI,Jason Blum's first two highest ROI movies is Romance genre.

2) My second recommendation will be for directors. My analysis shows that the director who has the highest mean ROI is Jason Blum.And also while checking the numbers according to datas Jason Blum made about 42 movies, He has pretty low mean production budget.it might be good idea to start working with on Microsoft's new studio.

3) My third recommendation will be for the studio. As we can see the one who has highest ROI is Warner Bros. WB studio's most succesfull genre is Romance as well. And if we deep into avarage production budget by genre we can see that Romance genre also has the lowest avarage budget.And of course Microsoft will be one of the studios in the market but WB's strategies can be implemented during creating movie by Microsoft.It can be considerable in terms of releasing succesful movie.


## Next Steps

Further analyses could yield additional insights for Microsoft's Movie Studios

1) I would next like to analyze the correlations between the genres and directors in these categories. For example, which directors have the highest mean ROI when working with certain genres

2) I would like to see is there a correlation between production budget and studios. For example budget range might affect movie's success

3) What other metrics determine success aside from Profits and ROI What affect does a movie's ratings or the number of times it has been viewed?











