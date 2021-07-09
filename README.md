# Correlation in Python

In this project, I am working in Python to find correlations between our dependent varaible, gross revenue, and other movie feature variables.

# Motivation 

Is the movie industry dying? is Netflix the new entertainment king? Those were the first questions that lead me to create a  But, why stop there? There are more factors that intervene in this kind of thing, like actors, genres, user ratings and more. Furthermore, while I know how to run a correlation and linear regression analysis in R, I used this opportunity to practice running a correlation and regression analysis in Python. 

# Data 

The data I used was found on <a href="https://www.kaggle.com/danielgrijalvas/movies" class="icon brands alt fa-kaggle"><span class="label">Kaggle</span></a>. This dataset focuses on movie revenue over the last decade(s).
There are 6820 movies in the dataset (220 movies per year, 1986-2016). Each movie has the following attributes:
* budget: the budget of a movie. Some movies don't have this, so it appears as 0
* company: the production company
* country: country of origin
* director: the director
* genre: main genre of the movie.
* gross: revenue of the movie
* name: name of the movie
* rating: rating of the movie (R, PG, etc.)
* released: release date (YYYY-MM-DD)
* runtime: duration of the movie
* score: IMDb user rating
* votes: number of user votes
* star: main actor/actress
* writer: writer of the movie
* year: year of release

# Initial Thoughts
We will use gross revenue for films as our dependent variable (y). There are could be many variables from the list above that predict gross revenue. We want to find the independent, or predictor, variables (x) that are correlated with gross revenue out of the list shown above. When we identify the predictor variables, we then will look at what kind of correlation the variables have: negative or positive correlation, and we will inidicate an intensity: low, moderate, or high correlation. 

Before I start the analysis, I predict that the variables budget and company will both be highly correlated with gross revenue for films. At this point in time, I do not know if those two varibales are correlated with but thanks to the analysis, we will be able to find out what variables actually influence gross revenue. 

# Conclusion 
After we cleaned the data, made sure there were no duplicates, and coded string variable values to categorical values (unique identifiers) to run the analysis. 

I found I was 50% correct in my assumptions: It appears the variables budget and votes have the highest, positive correlation to gross revenue while company has a low positive correlation. 

