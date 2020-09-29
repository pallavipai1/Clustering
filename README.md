# project3
Data set used:
https://grouplens.org/datasets/movielens/

1. Data Cleaning

  Loaded the movies.csv and rating.csv using pandas library

  Performed data cleaning in movies data and removed the redundant records, null records and records without any movie ratings


2. Data Transformation

   Mapped movies data to average user rating based on 'movieId' as a key
  
   Merged 'movies' and 'ratings' dataframe to include movie title and ratings in a single dataframe
   
   Transformed movies data using ther movieID and the genre they are a part of
   
   Using dimentionality reduction, created a dataframe consisting of movieID and average movie rating 
  
3. Data Analysis
  
   Analyzed the data and calculated average rating for each movie based on the each user ratings for each movie
   
   Analyzed the relation between users and ratings given by them
   
   Analyzed the relation between number of movies and ratings
   
   Performed k-means clustering on this dataset for a cluster size of 17 for 17 genres and Displayed movies pertaining to one cluster 
   
   Using k-means clustering, formed 5 clusters of movie ratings
   

4. Data Plotting
   
   Plotted relation between user and ratings given in a histogram
   
   Plotted relation between number of movies and ratings in a histogram
   
   Plotted all the clusters as per genres using a scatter plot
   
   Plotted all the clusters as per ratings using a scatter plot

5. Conclusion/Inferences
   
   (Feature Engineering)
   Derived the movies with maximum user ratings and noted that 'Forrest Grump' topped the list with 3518 user ratings followed by 'Shawshank Redemption' with 3488 user ratings
   
   Most users give a rating of 4 stars for movies.
   
   Most movies received a rating between 3 to 4 stars








