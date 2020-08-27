![Header](https://github.com/SalimAmarti/OTT_movies_Project/blob/master/OTT_header.gif)

Motivations
-------

I am a big fan of movies. I always wanted to do a movie project. When I came across this dataset on Kaggle, I realized that the use of OTT platforms was quite a hot topic during this lockdown period.

In this project, my goal is to spot the differences between each OTT platform: Netflix, Hulu, Prime Video and Disney+. But I believe it is also interesting to consider this dataset as a whole and find global movie insights.

Sources
-------

I used a Kaggle dataset posted by Ruchi Bhatia.

*https://www.kaggle.com/ruchi798/movies-on-netflix-prime-video-hulu-and-disney*

I also would like to thank ZhongTr0n for his tutorial on how to create a map from categorical data with Python.

*https://towardsdatascience.com/create-categorical-choropleth-with-python-122da5ae6764*

The code
-------

Click [here](https://github.com/SalimAmarti/OTT_movies_Project/blob/master/OTT%20project.ipynb) to view the code.

Executive Summary
-------

Throughout the analysis, I was able to pull out several interesting insights:
- *Prime Video is the platform with most movies*
- *Disney+ has more well-rated movies*
- *Disney+ has more 'old' movies, Netflix and Hulu have the most recent content*
- *Netflix movies are longer on average*
- *Disney+ stands out with a completely different movie landscape aimed towards families*
- *Drama is the most produced genre across most countries and over time*
- *News, Documentary and Biography are the most well-rated genres on average*
- *The top 3 of most well-rated directors are: Rocco Urbisci (he directed George Carlin's - a famous US comedian - comedy shows), Hrishikesh Mukherjee (he is one of the most famous Indian directors) and Martin Scorsese (you probably know him)*

Exploratory Data Analysis (EDA)
-------

In this project, my goal was to exploit the data in all possible ways. After performing some data cleaning (handling null values, etc.), I answered to these questions: 
- *What is the OTT platform with the most movies?*
- *What is the rating distribution on OTT platforms?*
- *How old are movies on OTT platforms?*
- *How long are movies on OTT platforms?*
- *What is the top genre per OTT platform?*

Then I wanted to push the analysis further and consider the dataset as a whole without splitting OTT plaforms:
- *What is the top genre per country?*
- *What is the top genre per year?*
- *What is the genre with the highest average rating?*
- *Who is the most well-rated director?*

Here are the variables available in the dataset:

| Variable        | Definition                                | Key           |
|-----------------|-------------------------------------------|---------------|
| ID              | Unique movie ID                           |               |
| Title           | Title of the movie                        |               |
| Year            | Year when the movie was produced          |               |
| Age             | Target age group                          |               |
| IMDb            | IMDb rating                               |               |
| Rotten Tomatoes | Rotten Tomatoes %                         |               |
| Netflix         | Whether the movie is found on Netflix     | 1: Yes, 0: No |
| Hulu            | Whether the movie is found on Hulu        | 1: Yes, 0: No |
| Prime Video     | Whether the movie is found on Prime Video | 1: Yes, 0: No |
| Disney+         | Whether the movie is found on Disney+     | 1: Yes, 0: No |
| Type            | Movie or TV series                        |               |
| Directors       | Directors of the movie                    |               |
| Genres          | Genres of the movie                       |               |
| Country         | Country where the movie was produced      |               |
| Language        | Languages available for the movie         |               |
| Runtime         | Length of the movie                       |               |


For more details, feel free to go through [the code](https://github.com/SalimAmarti/OTT_movies_Project/blob/master/OTT%20project.ipynb).


Next steps / Improvements
-------

- Try to predict movie ratings based on relevant features
- Figure out which country has the most well-rated movie productions
