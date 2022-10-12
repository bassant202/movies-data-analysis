# movies-data-analysis
# Dataset Description:
This data set contains information about +9000 movies extracted from TMDB API.

# Columns Descriptions:
Release_Date: Date when the movie was released.
Title: Name of the movie.
Overview: Brief summary of the movie.
Popularity: It is a very important metric computed by TMDB developers based on the number of views per day, votes per day, number of users marked it as "favorite" and "watchlist" for the data, release date and more other metrics.
Vote_Count: Total votes received from the viewers.
Vote_Average: Average rating based on vote count and the number of viewers out of 10.
Original_Language: Original language of the movies. Dubbed version is not considered to be original language. Genre: Categories the movie it can be classified as.
Poster_Url: Url of the movie poster
# Exploration Summarey
we have a dataframe consisting of 9827 rows and 9 columns.
our dataset looks a bit tidy with no NaNs nor duplicated values.
in Release_Date column we need to extract only the year value.
Overview and Poster-Url wouldn't be so useful during analysis, so we dropped them.
there is noticable outliers in Popularity column
Genre column has comma saperated values and white spaces that needs to be handled and casted into category.
# conclusion
the most frequent genre is drama
we can see that Spider-Man: No Way Home has the highest popularity rate in our dataset and it has genres of Action.
2020 has the most filmed movies 
the most frequent language is english
