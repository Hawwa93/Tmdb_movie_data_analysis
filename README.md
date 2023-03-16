# (TMDb movie data)
## by (Hauwa Musa Hameed)


## Dataset Description
> This data set contains information about 10,000 movies collected from the Movie Database (TMDb). It includes information such as movie user ratings, budgets, genres, revenue, release year, and many other relevant information. It contains 10866 rows and 21 columns.

## Conclusions
After carefully carrying out my analysis of the TMDb dataset, the foolowing finding was made

1. The highest revenue was generated in 2015.
2. producing animation movies has the highest budget cost
3. Over the years drama movies are more produced and Tv movies are least produced
4. There is a strong positive relationship between budget and revenue. The more the budget cost of a movie the more revenue it generated
5. there is also a positive relationship between vote count and popularitiy. The vote count increases as the popularity increase


## Limitation

This data set was large enough to answer the questions abiut the TMDb movie data set but more than 50% of the data sample was droped due to high number of null values and 0 entries in both budget and revenue column, and this I consider a major set back in the course of my analysis.

The genre column contains multiple genre for each movie seperated by '|', which I had to split and extract the first genre in order to make my analysis more effective.
