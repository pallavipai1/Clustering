# project3
Data set used:
https://grouplens.org/datasets/movielens/

Loaded the movies.csv and rating.csv on pandas library

Analyzed the data and calculated average rating for each movie based on the each user ratings for each movie

Performed data cleaning in movies data and removed the redundant records and records without any movie ratings

Mapped movies data to average user rating based on 'movieId' as a key

Merged 'movies' and 'ratings' dataframe to include movie title and ratings in a single dataframe


Derived the movies with maximum user ratings and noted that 'Forrest Grump' topped the list with 3518 user ratings followed by 'Shawshank Redemption' with 3488 user ratings

Analyzed the relation between users and ratings given by then and concluded that most users give a rating of 4 stars for movies.

Plotted this data on a histogram


Analyzed the relation between number of movies and ratings received and concluded that most movies received a rating between 3 to 4 stars

Plotted this data on a histogram


Diplayed movied using ther movieID and the genre they are a part of

Performed k-means clustering on this dataset for a cluster size of 17 for 17 genres

Displayed movies pertaining to one one cluster 

Plotted all the clusters as per genres using a scatter plot


Using dimentionality reduction, created a dataframe consisting of movieID and average movie rating 

Using k-means clustering, formed 5 clusters of movie ratings

Plotted all the clusters as per genres using a scatter plot
