# MovieRecommendation

#### Project3 for EECS 731

Data for movies, ratings and tags are downloaded from 

https://grouplens.org/datasets/movielens/ <br>



Part I: Data Preparation and Overview  <br>

  * Load all three data sets into panda data frames and get general infomations about their data shape

  * Drop timestamps for rating and tags data sets

  * Drop not available datas in all three data sets


Part II: General movie recommendation

  * Combine movies and tags into one data set showing users' tags for all movies
  
  * Calculate average rating for all movies from ratings data and combine them with movie infomations
  
  * Built filter for movie in genre 'Adventrue'
  
  * Built filter for high-rating(rating greater than or equal to 4) movies
  
  * Show numbers of high-rating movies in each genre


Part III: Combination of ratings and tags - most frequently used tags

  * Combine ratings and tags into one data set showing users' ratings and tags for different movies
  
  * Counts for number of all tags and show the top 20 most frequently-used tags in bar chart 
  

Part IV: Recommend movies with similar tag and genre feature

  * Extract releasing year info and genre info into data form

  * K-means Clustering:

    > Set number of clusters as total types of genres <br>

    > Visualizing the first 3 clusters

  * K-Nearest neighbors Clustering:  

    > Set 10 movies to recommend for a given movie: neighborsize = 10
    
    > Taking Titanic(1998) as example, give 10 movie recommendation <br>




Discussion

   * Both models are based on distance to cluster center

   * K-means model needs a given number of clusters while KNN model doesn't


More details could be found in code comments.
