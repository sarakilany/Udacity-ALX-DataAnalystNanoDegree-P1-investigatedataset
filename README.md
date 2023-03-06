# Udacity-ALX-DataAnalystNanoDegree-P1-investigatedataset
## by Sara Osama Kilany


## Dataset
The data of 10000 movies were collected from The Movies Database (TMDB). This dataset countains information about these movies including their titles, budget, popularity, revenue, cast, homepage, director, genre, and release_year. The information regarding both budget and revenue exist in both original and adjusted values according to the rates of 2010. Our goal is to invesitgate the revenue of movies how it relates to genre, budget, and production companeis

## Analysis Questions:
For our analysis we will answer the following questions:

Which movies have the highest and lowest revenue? How does revenue relate to revenue categories?
Which movies had greatest losses and which made largest profits? How did profit change through the years?
Which year has the largest sum of vote_count ? and which movie? How does vote_count relate to other variables?
Who are the top directors in terms of their films' revenue and popularity? How did the list of the top 3 change with time?

## Summary of Findings

Summary of Findings:

* Research Question 1: Which movies have the highest and lowest revenue? How does revenue relate to the number of movies exceeding billion dollars that year and other revenue ranges?

The movie with the highest revenue is Avatar with a revenue of 2.82712 billion dollars, while the movie with the lowest revenue is The Divide with a revenue of only 21,326.8 dollars.
Revenue has a higher correlation with movies that earned less than 0.5 billion dollars.

* Research Question 2: Which movies had the greatest losses, and which made the largest profits? How did profit change through the last 10 years?

Paranormal Activity is the movie with the highest profit, with over a million percent, while Foodfight has a loss of 99.89%.
The overall trend of mean profit values is decreasing with some peaks, and those peaks occur in 2007, 1999, 1977, and 1972. However, the peaks from 1999 to 2010 have a large number of movies produced during their years of release, while the peaks in 1977 and 1972 have a low number of movies produced, causing the shape of the mean curve.

* Research Question 3: Which year has the largest sum of vote_count? and which movie? How does vote_count relate to other variables?

2013 has the highest number of vote-count reaching 182,219 total votes. However, this result is not conclusive as the data we dropped had more movies than those we worked on.
The movie with the highest vote_count is Inception with 14075 votes.
Vote_count has a higher correlation with revenue_adj and popularity.

* Research Question 4: How does popularity correlate with other variables such as revenue, budget, and vote_count?

Revenue has the strongest correlation with popularity at 0.547, followed by vote_count at 0.801, and budget at 0.428. This indicates that popular movies tend to have higher revenues and more votes.

* Research Question 5: What are the most common genres and how have their popularity and revenue changed over time?

Drama is the most common genre, followed by Comedy and Thriller. The popularity of Drama, Comedy, and Action genres have remained consistently high over the years, while other genres such as Western and Foreign have seen a decline in popularity. The mean revenue for Action and Adventure genres has increased over the years, while the revenue for Drama and Romance genres has remained relatively stable.
